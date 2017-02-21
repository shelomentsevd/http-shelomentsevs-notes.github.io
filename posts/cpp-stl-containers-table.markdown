# C++ note about Standard Template Library containers
## Sequence containers
Sequence containers implement data structures which can be accessed sequentially.

| Container | Data structure |
|-----------|----------------|
|array|static contiguous array|
|vector|dynamic contiguous array|
|deque|sequence of individually allocated fixed-size arrays|
|forward_list|single-linked list|
|list|double-linked list|

## Associative containers
Associative containers implement sorted data structures that can be quickly searched (O(log n) complexity). 

| Container | Data structure |
|-----------|----------------|
|set|red-black tree|
|map|red-black tree|
|multiset|red-black tree|
|multimap|red-black tree|

## Unordered associative containers
Unordered associative containers implement unsorted (hashed) data structures that can be quickly searched (O(1) amortized, O(n) worst-case complexity). 

| Container | Data structure |
|-----------|----------------|
|unordered_set|hash table|
|unordered_map|hash table|
|unordered_multiset||
|unordered_multimap||

## Container adaptors
Container adaptors provide a different interface for sequential containers. 

| Container | Data structure |
|-----------|----------------|
| stack ||
| queue ||
| priority_queue ||
