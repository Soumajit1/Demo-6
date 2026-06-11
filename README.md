
class Solution {
 public:
  string longestCommonPrefix(vector<string>& strs) {
    if (strs.empty())
      return "";

    for (int i = 0; i < strs[0].length(); ++i)
      for (int j = 1; j <
    return strs[0];
  }
};
