# SQLite 3.22.0
## benchmark watch mvcc put
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.1733 secs.
  Slowest:	0.0091 secs.
  Fastest:	0.0002 secs.
  Average:	0.0017 secs.
  Stddev:	0.0009 secs.
  Requests/sec:	5770.3731

Response time histogram:
  0.0002 [1]	|
  0.0011 [235]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0020 [459]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0029 [222]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0038 [55]	|∎∎∎∎
  0.0047 [14]	|∎
  0.0055 [5]	|
  0.0064 [7]	|
  0.0073 [0]	|
  0.0082 [1]	|
  0.0091 [1]	|

Latency distribution:
  10% in 0.0008 secs.
  25% in 0.0011 secs.
  50% in 0.0016 secs.
  75% in 0.0021 secs.
  90% in 0.0027 secs.
  95% in 0.0032 secs.
  99% in 0.0053 secs.
  99.9% in 0.0091 secs.
```

## benchmark watch lease-keepalive
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.1302 secs.
  Slowest:	0.0157 secs.
  Fastest:	0.0001 secs.
  Average:	0.0013 secs.
  Stddev:	0.0018 secs.
  Requests/sec:	7679.4291

Response time histogram:
  0.0001 [1]	|
  0.0017 [885]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0032 [62]	|∎∎
  0.0048 [11]	|
  0.0063 [21]	|
  0.0079 [1]	|
  0.0095 [3]	|
  0.0110 [2]	|
  0.0126 [6]	|
  0.0142 [6]	|
  0.0157 [2]	|

Latency distribution:
  10% in 0.0004 secs.
  25% in 0.0006 secs.
  50% in 0.0008 secs.
  75% in 0.0012 secs.
  90% in 0.0017 secs.
  95% in 0.0034 secs.
  99% in 0.0124 secs.
  99.9% in 0.0157 secs.
```

## benchmark range 100
```
bench with linearizable range
 10000 / 10000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 5s

Summary:
  Total:	5.3294 secs.
  Slowest:	0.0125 secs.
  Fastest:	0.0004 secs.
  Average:	0.0005 secs.
  Stddev:	0.0003 secs.
  Requests/sec:	1876.3991

Response time histogram:
  0.0004 [1]	|
  0.0016 [9972]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0028 [10]	|
  0.0040 [1]	|
  0.0052 [4]	|
  0.0064 [10]	|
  0.0076 [0]	|
  0.0089 [1]	|
  0.0101 [0]	|
  0.0113 [0]	|
  0.0125 [1]	|

Latency distribution:
  10% in 0.0005 secs.
  25% in 0.0005 secs.
  50% in 0.0005 secs.
  75% in 0.0005 secs.
  90% in 0.0006 secs.
  95% in 0.0007 secs.
  99% in 0.0009 secs.
  99.9% in 0.0054 secs.
```

## benchmark watch
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.3657 secs.
  Slowest:	0.0389 secs.
  Fastest:	0.0002 secs.
  Average:	0.0035 secs.
  Stddev:	0.0053 secs.
  Requests/sec:	2734.3543

Response time histogram:
  0.0002 [1]	|
  0.0040 [750]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0079 [142]	|∎∎∎∎∎∎∎
  0.0118 [65]	|∎∎∎
  0.0156 [15]	|
  0.0195 [7]	|
  0.0234 [0]	|
  0.0272 [5]	|
  0.0311 [2]	|
  0.0350 [1]	|
  0.0389 [12]	|

Latency distribution:
  10% in 0.0006 secs.
  25% in 0.0009 secs.
  50% in 0.0016 secs.
  75% in 0.0040 secs.
  90% in 0.0084 secs.
  95% in 0.0110 secs.
  99% in 0.0368 secs.
  99.9% in 0.0389 secs.
```

# MySQL 5.7.30
## benchmark watch mvcc put
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.1771 secs.
  Slowest:	0.0100 secs.
  Fastest:	0.0001 secs.
  Average:	0.0017 secs.
  Stddev:	0.0014 secs.
  Requests/sec:	5647.5686

Response time histogram:
  0.0001 [1]	|
  0.0011 [424]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0021 [327]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0031 [131]	|∎∎∎∎∎∎∎∎∎∎∎∎
  0.0041 [44]	|∎∎∎∎
  0.0051 [32]	|∎∎∎
  0.0061 [13]	|∎
  0.0070 [25]	|∎∎
  0.0080 [2]	|
  0.0090 [0]	|
  0.0100 [1]	|

Latency distribution:
  10% in 0.0004 secs.
  25% in 0.0008 secs.
  50% in 0.0013 secs.
  75% in 0.0021 secs.
  90% in 0.0037 secs.
  95% in 0.0048 secs.
  99% in 0.0065 secs.
  99.9% in 0.0100 secs.
```

## benchmark watch lease-keepalive
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.1784 secs.
  Slowest:	0.0156 secs.
  Fastest:	0.0001 secs.
  Average:	0.0017 secs.
  Stddev:	0.0017 secs.
  Requests/sec:	5605.7025

Response time histogram:
  0.0001 [1]	|
  0.0016 [649]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0032 [252]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0047 [38]	|∎∎
  0.0063 [35]	|∎∎
  0.0078 [14]	|
  0.0094 [3]	|
  0.0109 [0]	|
  0.0125 [0]	|
  0.0140 [7]	|
  0.0156 [1]	|

Latency distribution:
  10% in 0.0005 secs.
  25% in 0.0009 secs.
  50% in 0.0013 secs.
  75% in 0.0020 secs.
  90% in 0.0032 secs.
  95% in 0.0050 secs.
  99% in 0.0085 secs.
  99.9% in 0.0156 secs.
```

## benchmark range 100
```
 10000 / 10000 Boooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 13s

Summary:
  Total:	13.5941 secs.
  Slowest:	0.0146 secs.
  Fastest:	0.0010 secs.
  Average:	0.0014 secs.
  Stddev:	0.0005 secs.
  Requests/sec:	735.6143

Response time histogram:
  0.0010 [1]	|
  0.0024 [9894]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0037 [37]	|
  0.0051 [11]	|
  0.0064 [37]	|
  0.0078 [13]	|
  0.0092 [2]	|
  0.0105 [0]	|
  0.0119 [2]	|
  0.0132 [2]	|
  0.0146 [1]	|

Latency distribution:
  10% in 0.0012 secs.
  25% in 0.0012 secs.
  50% in 0.0013 secs.
  75% in 0.0014 secs.
  90% in 0.0015 secs.
  95% in 0.0016 secs.
  99% in 0.0024 secs.
  99.9% in 0.0073 secs.
```

## benchmark watch
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.1874 secs.
  Slowest:	0.0177 secs.
  Fastest:	0.0001 secs.
  Average:	0.0018 secs.
  Stddev:	0.0023 secs.
  Requests/sec:	5335.9095

Response time histogram:
  0.0001 [1]	|
  0.0019 [757]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0036 [162]	|∎∎∎∎∎∎∎∎
  0.0054 [28]	|∎
  0.0072 [18]	|
  0.0089 [7]	|
  0.0107 [7]	|
  0.0124 [8]	|
  0.0142 [3]	|
  0.0160 [0]	|
  0.0177 [9]	|

Latency distribution:
  10% in 0.0005 secs.
  25% in 0.0008 secs.
  50% in 0.0012 secs.
  75% in 0.0019 secs.
  90% in 0.0029 secs.
  95% in 0.0054 secs.
  99% in 0.0125 secs.
  99.9% in 0.0177 secs.
```
