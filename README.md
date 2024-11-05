# spatial-reuse-detection
LLVM-based analyzer for detecting self-spatial reuses in loop nests to enhance cache-aware optimizations.

## LLVM Self-Spatial Reuse Analyzer
This project extends the LLVM compiler infrastructure to enhance dependence analysis by detecting self-spatial reuses in loop nests. The custom functions identifies memory references where the stride between consecutive accesses in the innermost loop is smaller than the cache line size.
