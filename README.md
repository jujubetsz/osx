# osx sysbench v0

sysbench quick tests with some osx configs.

## Memory tests

Config: 
```sysbench memory --memory-block-size=1M --memory-total-size=80G```


### Macbook PRO Retina 2012, i7@2.3 8GB@1600 SSD 256GB m.2

```
sysbench 1.0.20 (using system LuaJIT 2.1.0-beta3)

  block size: 1024KiB
  total size: 81920MiB
  operation: write
  scope: global

Total operations: 81920 (11925.04 per second)

81920.00 MiB transferred (11925.04 MiB/sec)

General statistics:
    total time:                          6.8678s
    total number of events:              81920

Latency (ms):
         min:                                    0.08
         avg:                                    0.08
         max:                                    0.33
         95th percentile:                        0.11
         sum:                                 6838.78

Threads fairness:
    events (avg/stddev):           81920.0000/0.00
    execution time (avg/stddev):   6.8388/0.00
```

### Macbook PRO 2021 m1 16GB 512 ssd

```
sysbench 1.0.20 (using system LuaJIT 2.1.0-beta3)

  block size: 1024KiB
  total size: 81920MiB
  operation: write
  scope: global

Total operations: 81920 (23923.65 per second)

81920.00 MiB transferred (23923.65 MiB/sec)

General statistics:
    total time:                          3.4238s
    total number of events:              81920

Latency (ms):
         min:                                    0.04
         avg:                                    0.04
         max:                                    2.07
         95th percentile:                        0.00
         sum:                                 3417.70

Threads fairness:
    events (avg/stddev):           81920.0000/0.00
    execution time (avg/stddev):   3.4177/0.00
```

### Ryzen5 3600x @3.8 16GB DDR4@2666 480 SSD/S.ATA

```
sysbench 1.0.20 (using system LuaJIT 2.1.0-beta3)

  block size: 1024KiB
  total size: 81920MiB
  operation: write
  scope: global

Total operations: 81920 (18062.25 per second)

81920.00 MiB transferred (18062.25 MiB/sec)

General statistics:
    total time:                          4.5345s
    total number of events:              81920

Latency (ms):
         min:                                    0.05
         avg:                                    0.06
         max:                                    0.48
         95th percentile:                        0.06
         sum:                                 4514.49

Threads fairness:
    events (avg/stddev):           81920.0000/0.00
    execution time (avg/stddev):   4.5145/0.00
```

### Macbook Air M1 2020 8GB 256M2

```
sysbench 1.0.20 (using system LuaJIT 2.1.0-beta3)

  block size: 1024KiB
  total size: 81920MiB
  operation: write
  scope: global

Total operations: 81920 (14733.92 per second)

81920.00 MiB transferred (14733.92 MiB/sec)

General statistics:
    total time:                          5.5594s
    total number of events:              81920

Latency (ms):
         min:                                    0.07
         avg:                                    0.07
         max:                                    0.52
         95th percentile:                        0.00
         sum:                                 5549.56

Threads fairness:
    events (avg/stddev):           81920.0000/0.00
    execution time (avg/stddev):   5.5496/0.00
```
