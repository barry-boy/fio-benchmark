|    | Job               |   iodepth |   procs |     IOPS |   BW (GiB/s) |
|---:|:------------------|----------:|--------:|---------:|-------------:|
|  1 | 1-proc-read-4k-1  |         1 |       1 |  5149    |    0.0196409 |
|  8 | 1-proc-read-4k-2  |         2 |       1 |  9386.19 |    0.0358047 |
|  4 | 1-proc-read-4k-4  |         4 |       1 | 16064.8  |    0.0612822 |
|  5 | 1-proc-read-4k-8  |         8 |       1 | 24309.6  |    0.0927334 |
|  2 | 1-proc-read-4k-16 |        16 |       1 | 30040.8  |    0.114596  |
|  0 | 4-proc-read-4k-1  |         1 |       4 | 15780.1  |    0.0601959 |
|  9 | 4-proc-read-4k-2  |         2 |       4 | 32120.7  |    0.12253   |
|  6 | 4-proc-read-4k-4  |         4 |       4 | 51321.4  |    0.195775  |
|  7 | 4-proc-read-4k-8  |         8 |       4 | 73483.6  |    0.280317  |
|  3 | 4-proc-read-4k-16 |        16 |       4 | 92430.2  |    0.352592  |