# HackingSTL
Hacking STL (ex: C++11 thread for stacksize)

## thread
Implement std::stacking_thread(size_t size, ...)

<code>
  std::thread thread = std::stacking_thread(65536, []{ printf("Hello, world!\n"); });
</code>

## semaphore
Implement semaphore before C++20
