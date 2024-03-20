# CMPS 2200 Reciation 5
## Answers

**Name:**___Sam Cohen, Andrew Zimmerman______________________


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
Fixed and Random q sort have upper bounds of O(nlogn) and selection sort has upper bounds of O(n^2). The running times for fixed and random sort are much faster then the running times of selection sort.



- **1c.**
n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|--------|---------------------|----------------------|------------|
|    100 |               0.611 |                2.677 |      0.018 |
|    200 |               1.738 |                1.868 |      0.037 |
|    500 |               4.542 |                2.458 |      0.062 |
|   1000 |               5.073 |                5.326 |      0.135 |
|   2000 |              64.390 |               18.139 |      0.503 |
|   5000 |              93.954 |               97.139 |      1.011 |
|  10000 |             206.660 |              195.457 |      3.183 |
|  20000 |             436.306 |              577.021 |      5.043 |
|  50000 |            1474.657 |              904.392 |     11.873 |
| 100000 |            2404.423 |             2486.044 |     27.006 |
