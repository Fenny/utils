```go
Benchmark_GetMIME                     23092065                49.1 ns/op             0 B/op          0 allocs/op
Benchmark_GetMIME                     23079230                48.7 ns/op             0 B/op          0 allocs/op

Benchmark_ToLower/fiber               22987184                48.2 ns/op            48 B/op          1 allocs/op
Benchmark_ToLower/fiber               24491794                49.6 ns/op            48 B/op          1 allocs/op
Benchmark_ToLower/default              9232608               123 ns/op              48 B/op          1 allocs/op
Benchmark_ToLower/default              9454870               123 ns/op              48 B/op          1 allocs/op

Benchmark_ToLowerBytes/fiber          44463876                26.1 ns/op             0 B/op          0 allocs/op
Benchmark_ToLowerBytes/fiber          39997200                26.1 ns/op             0 B/op          0 allocs/op
Benchmark_ToLowerBytes/default        14879088                77.6 ns/op            48 B/op          1 allocs/op
Benchmark_ToLowerBytes/default        14631433                79.2 ns/op            48 B/op          1 allocs/op

Benchmark_ToUpper/fiber               22648730                49.4 ns/op            48 B/op          1 allocs/op
Benchmark_ToUpper/fiber               23084425                48.6 ns/op            48 B/op          1 allocs/op
Benchmark_ToUpper/default              9520122                 124 ns/op            48 B/op          1 allocs/op
Benchmark_ToUpper/default              9375014                 133 ns/op            48 B/op          1 allocs/op

Benchmark_ToUpperBytes/fiber          44439176                25.6 ns/op             0 B/op          0 allocs/op
Benchmark_ToUpperBytes/fiber          44458934                25.5 ns/op             0 B/op          0 allocs/op
Benchmark_ToUpperBytes/default        15347073                74.1 ns/op            48 B/op          1 allocs/op
Benchmark_ToUpperBytes/default        15511370                74.2 ns/op            48 B/op          1 allocs/op

Benchmark_EqualFolds/fiber            34297864                33.8 ns/op             0 B/op          0 allocs/op
Benchmark_EqualFolds/fiber            34285322                34.0 ns/op             0 B/op          0 allocs/op
Benchmark_EqualFolds/default          12756945                91.8 ns/op             0 B/op          0 allocs/op
Benchmark_EqualFolds/default          13015282                91.1 ns/op             0 B/op          0 allocs/op

Benchmark_Trim/fiber                  207314002                5.85 ns/op            0 B/op          0 allocs/op
Benchmark_Trim/fiber                  207386125                5.78 ns/op            0 B/op          0 allocs/op
Benchmark_Trim/default                16506302                 68.5 ns/op           32 B/op          1 allocs/op
Benchmark_Trim/default                16669119                 68.9 ns/op           32 B/op          1 allocs/op
Benchmark_Trim/default.trimspace      165073046                7.27 ns/op            0 B/op          0 allocs/op
Benchmark_Trim/default.trimspace      165796213                7.32 ns/op            0 B/op          0 allocs/op

Benchmark_TrimLeft/fiber              343254828                3.47 ns/op            0 B/op          0 allocs/op
Benchmark_TrimLeft/fiber              344407171                3.45 ns/op            0 B/op          0 allocs/op
Benchmark_TrimLeft/default            24999790                 46.4 ns/op            32 B/op         1 allocs/op
Benchmark_TrimLeft/default            25001926                 45.3 ns/op            32 B/op         1 allocs/op

Benchmark_TrimRight/fiber             374543056                3.15 ns/op            0 B/op          0 allocs/op
Benchmark_TrimRight/fiber             336067616                3.15 ns/op            0 B/op          0 allocs/op
Benchmark_TrimRight/default           20868186                 52.8 ns/op            32 B/op         1 allocs/op
Benchmark_TrimRight/default           21434695                 55.1 ns/op            32 B/op         1 allocs/op
```
