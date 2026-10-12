
# DNA String Matching Algorithms

This module focuses on implementing DNA motif-searching algorithms to find occurrences of DNA patterns in genome sequences.

## Algorithms
- PatternMatcher
- NaiveMatcher
- KMPMatcher
- RabinKarpMatcher
- ZMatcher
- AhoCorasick
- SuffixArrayIndex
- SuffixArrayMatcher

## Responsibilities
- Implement DNA motif-searching algorithms.
- Find occurrences of DNA patterns in genome sequences.
- Compare the results produced by different algorithms.
- Explain how the matching algorithms work and analyze their time complexity.

## Time Complexity

| Algorithm | Time Complexity |
|---|---|
| Naive Matching | O(nm) |
| KMP | O(n + m) |
| Rabin–Karp | Average O(n + m), worst O(nm) |
| Z Algorithm | O(n + m) |
| Aho–Corasick | Depends on preprocessing, text length, and matches |
| Suffix Array | Depends on construction and search methods |

Here, `n` represents the genome sequence length and `m` represents the DNA pattern length. These are standard theoretical complexities; actual complexity depends on the implementation.

## Contribution
**GitHub Commit Message:** `Add DNA string matching algorithms`
