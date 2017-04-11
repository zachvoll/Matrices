# Y86
csim.c - a LRU cache simulator that replays traces from Valgrind and outputs stats (hits, misses, evictions).

trans.c - contains a matrix wavefront function that attempts to minimize misses for specific sizes (32 sets and 256 sets).

matrix_xor.ys - takes xor of two matrices between 1-8 NxN sizes, optimized some with loop unrolling.
