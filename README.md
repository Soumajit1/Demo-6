class Solution {
public:
    bool isPalindrome(int x) {
        // Negative numbers are not palindromes
        // Numbers ending with 0 (except 0 itself) are not palindromes
        if (x < 0 || (x != 0 && x % 10 == 0)) {
            return false;
        }
        // Reverse the second half of the number
        int reversedHal than or equal to the remaining part
        while (reversedHalf < x) {
            // Extra
        // For odd length numbers: check if x equals reversedHalf without the middle digit
        return x == reversedHalf || x == reversedHalf / 10;
    }
};

