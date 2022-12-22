# Temporary Memory Allocator
The user can allocate a large pool of memory from the heap at startup and then allocate from the pool as needed. The memory allocation happens only once, obviating the need for subsequent calls to the OS.
