
"Top-down" means that in each recursive call, we will visit the node first to come up with some values, and pass these values to its children when calling the function recursively. So the "top-down" solution can be considered as a kind of preorder traversal. 

"Bottom-up" is another recursive solution. In each recursive call, we will firstly call the function recursively for all the children nodes and then come up with the answer according to the returned values and the value of the current node itself. This process can be regarded as a kind of postorder traversal.

lc 250 Count Univalue Subtree
  Count Univalue Subtrees
  Given a binary tree, count the number of uni-value subtrees.

A Uni-value subtree means all nodes of the subtree have the same value.

Input:  root = [5,1,5,5,5,null,5]

              5
             / \
            1   5
           / \   \
          5   5   5

Output: 4
class Solution {
    int ans = 0;
    public int countUnivalSubtrees(TreeNode root) {
        if (root == null) return 0;
        isUni(root);
        return ans;
    }
    public boolean isUni(TreeNode root) {
        if (root == null) return true;
        if (root.left == null && root.right == null) {
            ans++;
            return true;
        }
        boolean flag = true;
        if (!isUni(root.left) || (root.left != null && root.left.val != root.val)) {
            flag = false;
        }
        if (!isUni(root.right) || (root.right != null && root.right.val != root.val)) {
            flag = false;
        }
        if (flag) {
            ans++;
            return true;
        }
        return false;
        
    }
}

When your have to judge root.val == root.left and root.val == root.right recursively, you should use a boolean flag. Because you might end up in left subtree because you directly return false when root.val != root.left.val
