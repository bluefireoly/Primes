# Kotlin solution by Jakob K

![Algorithm](https://img.shields.io/badge/Algorithm-base-green)
![Faithfulness](https://img.shields.io/badge/Faithful-yes-green)
![Parallelism](https://img.shields.io/badge/Parallel-yes-green)

An implementation of the base algorithm using Kotlin. The first test runs concurrently using coroutines, the other one
runs on a single thread.

## Output

Tested on a machine with 4 cores (Intel i5 4590) and using slow DDR3 ram.

The output with coroutines (**15694** iterations in 5 seconds):
```
jakobk_kotlin_coroutines;15694;5;4;algorithm=base
```

The output without coroutines (**4381** iterations in 5 seconds):
```
jakobk_kotlin_singlethreaded;4381;5.0;1;algorithm=base
```