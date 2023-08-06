# fire-up-the-oven-cmake
Example Hello World for inclussion in a BitBake meta data layer. 

## Build and run
```bash
$ mkdir build; cd build
$ cmake -G Ninja -DCMAKE_CXX_COMPILER=clang++ -DCMAKE_BUILD_TYPE=Debug ..
$ cmake -build .
$ ./HelloWorld
...
```