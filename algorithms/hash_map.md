# Hash Map
**reduce time complexity, o(n^2) -> o(n)**  
**C++ unordered_map, look up o(1), insert o(1)**  
**unordered list**  
## Leetcode
**1.[two Sums](https://leetcode.com/problems/two-sum/)**
- Use `mp.find()` instead of `mp.count` as `mp.find()` would return an iterator, can use
  ```cpp
  auto it = mp.find(complement);
  if (it != mp.end()) {
  return {it->second, i};
  }
  ```
  Which is faster than
  ```cpp
  if (mp.count(complement)){
  return{mp[complement],i}
  }
  ```


