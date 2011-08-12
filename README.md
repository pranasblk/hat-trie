
Hat-Trie
========

This a ANSI C99 implementation of the HAT-trie data structure of Askitis and
Sinha, an extremely efficient (space and time) modern variant of tries.

The version implemented here maps null-terminated strings to words (i.e.,
unsigned longs), which can be used to store counts, pointers, etc, or not used
at all if you simply want to maintain a set of unique strings.

For details see,

  1. Askitis, N., & Sinha, R. (2007). HAT-trie: a cache-conscious trie-based data
     structure for strings. Proceedings of the thirtieth Australasian conference on
     Computer science-Volume 62 (pp. 97–105). Australian Computer Society, Inc.

  2. Askitis, N., & Zobel, J. (2005). Cache-conscious collision resolution in
     string hash tables. String Processing and Information Retrieval (pp.
     91–102). Springer.



