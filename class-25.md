# Class-25
## DSA: Hashtables

### Links
- [Intro to HashTables](https://www.youtube.com/watch?v=MfhjkfocRR0) (video)
- [Basics of HashTables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
- [Wiki: Hash Table](https://en.wikipedia.org/wiki/Hash_table)


### Discussion Questions
1. **Is a HashTable useful for search or sorting operations? Why?** Very useful for searching, as long as you have the index, the time complexity is always O(1).
2. **What makes a good hash function?** Fewer numbers of collisions.
3. **Why should you try to reduce the number of collisions?** It could make it more difficult to find information if multiple key/values are hashed to the same index.
4. **What is stored at each index of a HashTable? Why?** A key/value pair is stored at an index so that it is possible to determine which value to return when a key led you to an index.


#### [Back to Home](README.md)