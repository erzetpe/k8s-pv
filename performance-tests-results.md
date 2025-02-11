# Rook

## Cluster of 3 Standard_D2s_v3 machines having 10G data disks 

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:              3,251 / 670
    Sequential:              1,486 / 720
  CPU Idleness:                      32%

Bandwidth in KiB/sec (Read/Write)
        Random:          12,261 / 13,263
    Sequential:          11,295 / 16,142
  CPU Idleness:                      72%

Latency in ns (Read/Write)
        Random:   2,477,795 / 23,194,670
    Sequential:   3,812,515 / 19,584,030
  CPU Idleness:                      48%
```

## Cluster of 3 Standard_D2s_v3 machines having 520G data disks

### run 1

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:            5,502 / 1,043
    Sequential:            2,048 / 1,000
  CPU Idleness:                      36%

Bandwidth in KiB/sec (Read/Write)
        Random:           11,357 / 8,482
    Sequential:            8,321 / 9,489
  CPU Idleness:                      79%

Latency in ns (Read/Write)
        Random:   1,582,506 / 19,940,795
    Sequential:   2,396,627 / 18,736,267
  CPU Idleness:                      61%
```

### run 2

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:              3,752 / 945
    Sequential:            2,003 / 1,028
  CPU Idleness:                      36%

Bandwidth in KiB/sec (Read/Write)
        Random:         243,478 / 50,182
    Sequential:         194,908 / 48,013
  CPU Idleness:                      36%

Latency in ns (Read/Write)
        Random:   3,286,926 / 23,785,866
    Sequential:   3,565,337 / 23,334,738
  CPU Idleness:                      58%
```

### run 3

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:              4,185 / 874
    Sequential:              1,939 / 945
  CPU Idleness:                      35%

Bandwidth in KiB/sec (Read/Write)
        Random:         248,741 / 52,498
    Sequential:         196,253 / 50,359
  CPU Idleness:                      31%

Latency in ns (Read/Write)
        Random:   3,385,304 / 24,696,991
    Sequential:   3,156,543 / 23,944,356
  CPU Idleness:                      60%
```

### run 4 

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:              4,121 / 857
    Sequential:              1,971 / 940
  CPU Idleness:                      36%

Bandwidth in KiB/sec (Read/Write)
        Random:         243,074 / 44,169
    Sequential:         193,588 / 44,671
  CPU Idleness:                      30%

Latency in ns (Read/Write)
        Random:   3,027,055 / 24,088,501
    Sequential:   2,975,124 / 22,944,103
  CPU Idleness:                      53%
```

## Cluster of 3 Standard_D8s_v3 machines having 520G data disks

### run 1
```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:            7,127 / 1,665
    Sequential:            2,220 / 1,661
  CPU Idleness:                      73%

Bandwidth in KiB/sec (Read/Write)
        Random:          12,112 / 11,063
    Sequential:           19,063 / 9,880
  CPU Idleness:                      83%

Latency in ns (Read/Write)
        Random:   2,399,861 / 19,015,768
    Sequential:   2,797,465 / 19,399,847
  CPU Idleness:                      78%
```
### run 2
```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:           10,177 / 1,715
    Sequential:            5,086 / 1,774
  CPU Idleness:                      85%

Bandwidth in KiB/sec (Read/Write)
        Random:         379,670 / 74,624
    Sequential:         332,010 / 61,974
  CPU Idleness:                      83%

Latency in ns (Read/Write)
        Random:   1,945,113 / 19,704,932
    Sequential:   1,949,226 / 17,767,582
  CPU Idleness:                      92%
```

### run 3

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:            6,070 / 1,592
    Sequential:            2,142 / 1,576
  CPU Idleness:                      78%

Bandwidth in KiB/sec (Read/Write)
        Random:         367,727 / 68,259
    Sequential:         283,939 / 64,873
  CPU Idleness:                      72%

Latency in ns (Read/Write)
        Random:   2,981,756 / 20,505,163
    Sequential:   3,021,128 / 20,583,944
  CPU Idleness:                      87%
```

### run 4

```
TEST_FILE: /volume/test
TEST_OUTPUT_PREFIX: test_device
TEST_SIZE: 2G
Benchmarking iops.fio into test_device-iops.json
Benchmarking bandwidth.fio into test_device-bandwidth.json
Benchmarking latency.fio into test_device-latency.json

=====================
FIO Benchmark Summary
For: test_device
SIZE: 2G
QUICK MODE: DISABLED
=====================
IOPS (Read/Write)
        Random:            5,593 / 1,636
    Sequential:            2,156 / 1,568
  CPU Idleness:                      77%

Bandwidth in KiB/sec (Read/Write)
        Random:         401,413 / 68,591
    Sequential:         336,813 / 68,321
  CPU Idleness:                      73%

Latency in ns (Read/Write)
        Random:   2,882,205 / 19,496,418
    Sequential:   3,640,014 / 20,598,309
  CPU Idleness:                      87%
```
