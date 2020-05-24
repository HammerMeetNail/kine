# SQLite 3.22.0
`kine`

## benchmark mvcc put
```
Summary:
  Total:	0.0006 secs.
  Slowest:	0.0002 secs.
  Fastest:	0.0000 secs.
  Average:	0.0000 secs.
  Stddev:	0.0000 secs.
  Requests/sec:	178264.8766

Response time histogram:
  0.0000 [1]	|
  0.0000 [97]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0000 [0]	|
  0.0000 [1]	|
  0.0001 [0]	|
  0.0001 [0]	|
  0.0001 [0]	|
  0.0001 [0]	|
  0.0001 [0]	|
  0.0001 [0]	|
  0.0002 [1]	|

Latency distribution:
  10% in 0.0000 secs.
  25% in 0.0000 secs.
  50% in 0.0000 secs.
  75% in 0.0000 secs.
  90% in 0.0000 secs.
  95% in 0.0000 secs.
  99% in 0.0002 secs.
```

## benchmark range 100
```
bench with linearizable range
 10000 / 10000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 5s

Summary:
  Total:	5.3977 secs.
  Slowest:	0.0132 secs.
  Fastest:	0.0003 secs.
  Average:	0.0005 secs.
  Stddev:	0.0003 secs.
  Requests/sec:	1852.6458

Response time histogram:
  0.0003 [1]	|
  0.0016 [9949]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0029 [16]	|
  0.0042 [9]	|
  0.0055 [9]	|
  0.0068 [9]	|
  0.0081 [3]	|
  0.0094 [3]	|
  0.0106 [0]	|
  0.0119 [0]	|
  0.0132 [1]	|

Latency distribution:
  10% in 0.0004 secs.
  25% in 0.0005 secs.
  50% in 0.0005 secs.
  75% in 0.0005 secs.
  90% in 0.0006 secs.
  95% in 0.0007 secs.
  99% in 0.0010 secs.
  99.9% in 0.0061 secs.
```

## benchmark watch
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.3660 secs.
  Slowest:	0.1044 secs.
  Fastest:	0.0002 secs.
  Average:	0.0036 secs.
  Stddev:	0.0100 secs.
  Requests/sec:	2732.4652

Response time histogram:
  0.0002 [1]	|
  0.0106 [953]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0210 [31]	|∎
  0.0315 [5]	|
  0.0419 [0]	|
  0.0523 [0]	|
  0.0627 [0]	|
  0.0732 [0]	|
  0.0836 [0]	|
  0.0940 [0]	|
  0.1044 [10]	|

Latency distribution:
  10% in 0.0007 secs.
  25% in 0.0010 secs.
  50% in 0.0017 secs.
  75% in 0.0033 secs.
  90% in 0.0053 secs.
  95% in 0.0104 secs.
  99% in 0.0975 secs.
  99.9% in 0.1044 secs.
```

# MySQL 5.7.30 
`docker run -p 3306:3306 -e MYSQL_ROOT_PASSWORD=password mysql:5.7.30`
`kine --endpoint "mysql://root:password@tcp(localhost:3306)/kine"`

## benchmark mvcc put
```
Summary:
  Total:	0.0003 secs.
  Slowest:	0.0000 secs.
  Fastest:	0.0000 secs.
  Average:	0.0000 secs.
  Stddev:	0.0000 secs.
  Requests/sec:	311189.1158

Response time histogram:
  0.0000 [1]	|
  0.0000 [89]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0000 [5]	|∎∎
  0.0000 [2]	|
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [1]	|
  0.0000 [1]	|
  0.0000 [1]	|

Latency distribution:
  10% in 0.0000 secs.
  25% in 0.0000 secs.
  50% in 0.0000 secs.
  75% in 0.0000 secs.
  90% in 0.0000 secs.
  95% in 0.0000 secs.
  99% in 0.0000 secs.
```

## benchmark range 100
```
bench with linearizable range
 10000 / 10000 Boooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 15s

Summary:
  Total:	15.6510 secs.
  Slowest:	0.0167 secs.
  Fastest:	0.0011 secs.
  Average:	0.0016 secs.
  Stddev:	0.0007 secs.
  Requests/sec:	638.9385

Response time histogram:
  0.0011 [1]	|
  0.0026 [9756]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0042 [124]	|
  0.0058 [37]	|
  0.0073 [39]	|
  0.0089 [23]	|
  0.0104 [9]	|
  0.0120 [6]	|
  0.0135 [2]	|
  0.0151 [2]	|
  0.0167 [1]	|

Latency distribution:
  10% in 0.0012 secs.
  25% in 0.0013 secs.
  50% in 0.0014 secs.
  75% in 0.0016 secs.
  90% in 0.0019 secs.
  95% in 0.0022 secs.
  99% in 0.0051 secs.
  99.9% in 0.0107 secs.
```

## benchmark watch
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.1924 secs.
  Slowest:	0.0178 secs.
  Fastest:	0.0001 secs.
  Average:	0.0019 secs.
  Stddev:	0.0019 secs.
  Requests/sec:	5198.0511

Response time histogram:
  0.0001 [1]	|
  0.0019 [713]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0036 [167]	|∎∎∎∎∎∎∎∎∎
  0.0054 [65]	|∎∎∎
  0.0072 [17]	|
  0.0089 [29]	|∎
  0.0107 [1]	|
  0.0125 [1]	|
  0.0142 [5]	|
  0.0160 [0]	|
  0.0178 [1]	|

Latency distribution:
  10% in 0.0005 secs.
  25% in 0.0008 secs.
  50% in 0.0012 secs.
  75% in 0.0021 secs.
  90% in 0.0039 secs.
  95% in 0.0057 secs.
  99% in 0.0087 secs.
  99.9% in 0.0178 secs.
```

# etcd 3.4.9 
`docker run -p 2379:2379 -e ALLOW_NONE_AUTHENTICATION=yes bitnami/etcd:3.4.9`

## benchmark mvcc put
```
Summary:
  Total:	0.0003 secs.
  Slowest:	0.0000 secs.
  Fastest:	0.0000 secs.
  Average:	0.0000 secs.
  Stddev:	0.0000 secs.
  Requests/sec:	301706.4517

Response time histogram:
  0.0000 [1]	|
  0.0000 [92]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0000 [5]	|∎∎
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [1]	|
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [0]	|
  0.0000 [1]	|

Latency distribution:
  10% in 0.0000 secs.
  25% in 0.0000 secs.
  50% in 0.0000 secs.
  75% in 0.0000 secs.
  90% in 0.0000 secs.
  95% in 0.0000 secs.
  99% in 0.0000 secs.
```

## benchmark range 100
```
bench with linearizable range
 10000 / 10000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 3s

Summary:
  Total:	3.9830 secs.
  Slowest:	0.0133 secs.
  Fastest:	0.0002 secs.
  Average:	0.0004 secs.
  Stddev:	0.0003 secs.
  Requests/sec:	2510.6565

Response time histogram:
  0.0002 [1]	|
  0.0015 [9951]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0028 [34]	|
  0.0041 [2]	|
  0.0054 [5]	|
  0.0068 [4]	|
  0.0081 [0]	|
  0.0094 [1]	|
  0.0107 [0]	|
  0.0120 [1]	|
  0.0133 [1]	|

Latency distribution:
  10% in 0.0003 secs.
  25% in 0.0003 secs.
  50% in 0.0004 secs.
  75% in 0.0004 secs.
  90% in 0.0005 secs.
  95% in 0.0006 secs.
  99% in 0.0011 secs.
  99.9% in 0.0047 secs.
```

## benchmark watch
```
 1000 / 1000 Booooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo! 100.00% 0s
Watch creation summary:

Summary:
  Total:	0.0752 secs.
  Slowest:	0.0134 secs.
  Fastest:	0.0002 secs.
  Average:	0.0007 secs.
  Stddev:	0.0008 secs.
  Requests/sec:	13292.2272

Response time histogram:
  0.0002 [1]	|
  0.0015 [935]	|∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎∎
  0.0028 [37]	|∎
  0.0041 [19]	|
  0.0055 [5]	|
  0.0068 [0]	|
  0.0081 [2]	|
  0.0094 [0]	|
  0.0107 [0]	|
  0.0121 [0]	|
  0.0134 [1]	|

Latency distribution:
  10% in 0.0003 secs.
  25% in 0.0004 secs.
  50% in 0.0005 secs.
  75% in 0.0006 secs.
  90% in 0.0012 secs.
  95% in 0.0020 secs.
  99% in 0.0041 secs.
  99.9% in 0.0134 secs.
```
