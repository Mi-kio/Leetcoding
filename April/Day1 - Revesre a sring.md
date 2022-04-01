## [problem](https://leetcode.com/problems/reverse-string/)

# Code

```
class Solution {
public:
    void reverseString(vector<char>& s) {
        int start = 0;
        int end = s.size();
        end = end - 1;
        
        while(start <= end){
            char st  = s[start];
            s[start] = s[end];
            s[end] = st;
            
            start++; end--;
        }
        
    }
};

```
