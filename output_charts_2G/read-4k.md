|    | Job               |   iodepth |   procs |     IOPS |   BW (GiB/s) |
|---:|:------------------|----------:|--------:|---------:|-------------:|
|  1 | 1-proc-read-4k-1  |         1 |       1 |  4881.94 |    0.0186224 |
|  8 | 1-proc-read-4k-2  |         2 |       1 |  9132.63 |    0.0348377 |
|  4 | 1-proc-read-4k-4  |         4 |       1 | 15974    |    0.060935  |
|  5 | 1-proc-read-4k-8  |         8 |       1 | 24687.2  |    0.0941734 |
|  2 | 1-proc-read-4k-16 |        16 |       1 | 32330    |    0.123328  |
|  0 | 4-proc-read-4k-1  |         1 |       4 | 19248.1  |    0.0734253 |
|  9 | 4-proc-read-4k-2  |         2 |       4 | 34948.5  |    0.133318  |
|  6 | 4-proc-read-4k-4  |         4 |       4 | 55220    |    0.210647  |
|  7 | 4-proc-read-4k-8  |         8 |       4 | 71988.7  |    0.274614  |
|  3 | 4-proc-read-4k-16 |        16 |       4 | 84128.6  |    0.320925  |