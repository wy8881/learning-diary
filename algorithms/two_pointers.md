# Two Pointers
**Reduce time complexity**  
**The array has to be sorted**
## Left to Right Pointers
**1.[Three Sum](https://leetcode.com/problems/3sum/)**
- **Outer-layer deduplication (on `i`)**: Skip repeated starting values so each distinct number is used only once as the first element.
- **Inner-layer deduplication (on `l` and `r`)**: After finding a triplet, skip repeated values at the left and right pointers so each triplet is produced only once.

