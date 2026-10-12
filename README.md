
# DNA Sequence Analysis Tool — String Matching Algorithms

**Course:** Data Structures and Algorithms - 3 (25CS2103E)

**Team Member:** Nehasree Padamati  
**Roll Number:** 2520030174

## My Contribution

My contribution focuses on implementing DNA motif-searching algorithms, finding pattern occurrences in genome sequences, comparing algorithm results, and analyzing their time complexity.

### Files Implemented

- `PatternMatcher.java` — Provides the pattern-matching abstraction.
- `NaiveMatcher.java` — Searches for DNA patterns by checking each possible position.
- `KMPMatcher.java` — Uses prefix information to avoid redundant comparisons.
- `RabinKarpMatcher.java` — Uses hashing to identify potential pattern matches.
- `ZMatcher.java` — Uses the Z-algorithm to find pattern occurrences.
- `AhoCorasick.java` — Searches for multiple patterns using a trie and failure links.
- `SuffixArrayIndex.java` — Provides suffix-array indexing for genome sequences.
- `SuffixArrayMatcher.java` — Searches for DNA patterns using a suffix array.

### Algorithm Analysis

The algorithms are compared based on their matching results and time complexity to understand their efficiency in DNA motif searching.

### Project Goal

These modules support the DNA Sequence Analysis Tool by providing different string-matching approaches to identify DNA motifs in genome sequences and compare their performance.
