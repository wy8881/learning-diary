# Two Pointers
**Reduce time complexity**  

## Left to Right Pointers
**The array has to be sorted**  
**1.[Three Sum](https://leetcode.com/problems/3sum/)**
- **Outer-layer deduplication (on `i`)**: Skip repeated starting values so each distinct number is used only once as the first element.
- **Inner-layer deduplication (on `l` and `r`)**: After finding a triplet, skip repeated values at the left and right pointers so each triplet is produced only once.
## Sliding Window  
**Check the condition between one window**  
**Don't need to be ordered**  
**1.[Longest Substring without Repetition](https://leetcode.com/problems/longest-substring-without-repeating-characters/)**  
- `vector<int> last(256,-1)` records the last position of a character, 255 characters max
- `last[c] >= l` as c has to be within the **[l,r]**
