Running main() from src/gtest_main.cc
[==========] Running 5 tests from 1 test suite.
[----------] Global test environment set-up.
[----------] 5 tests from Benchmark
[ RUN      ] Benchmark.Raw
raw:             0.0622 ms
[       OK ] Benchmark.Raw (0 ms)
[ RUN      ] Benchmark.StdUnique
std::unique_ptr: 0.0664 ms
[       OK ] Benchmark.StdUnique (0 ms)
[ RUN      ] Benchmark.MyUnique
my UniquePtr:    0.0848 ms
[       OK ] Benchmark.MyUnique (0 ms)
[ RUN      ] Benchmark.StdShared
std::shared_ptr: 0.1186 ms
[       OK ] Benchmark.StdShared (0 ms)
[ RUN      ] Benchmark.MyShared
