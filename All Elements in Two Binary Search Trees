/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode() {}
 *     TreeNode(int val) { this.val = val; }
 *     TreeNode(int val, TreeNode left, TreeNode right) {
 *         this.val = val;
 *         this.left = left;
 *         this.right = right;
 *     }
 * }
 */
class Solution {
    public List<Integer> getAllElements(TreeNode root1, TreeNode root2) {
        List<Integer> list = new ArrayList<Integer>();
        traversal1(root1,list);
        traversal1(root2,list);
        Collections.sort(list);
        return list;
    }
    
    public void traversal1(TreeNode root, List<Integer> list) {
        if(root != null){
        traversal1(root.left, list);   
        list.add(root.val);
        traversal1(root.right,  list);
        }
    }
}
