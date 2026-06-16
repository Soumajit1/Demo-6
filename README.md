class Solution {
 public:
  vector<int> inorderTraversal(TreeNode* root) {
    vector<int> ans;
    stack<TreeNode*> stack;
    while (root != nullptr || !stack.empty()) {
      while (root != nullptr) {
        stack.push(roo
      root = root->right;

