# cplusplus11-thread-safe-containers

STL containers that are thread-safe.

1. Conditioned List
  A list that can be pushed to and popped from by multiple
  threads.
  A single thread can wait on new pushes.

2. Dual Conditioned Lists
  A pair of thread-safe lists.
  A single thread can wait on new pushes to either of them.

3. Dual Conditioned Lists Ordered
  A pair of thread-safe lists.
  A single thread can wait on new pushes to either of them,
  and pop items in the order they were pushed.
  Each list type must have a default constructor.

