# OpenGL Journey - 1

## Build

```bash

# create build folder
$ mkdir build && cd build

# clean & build
$ rm -rf ./* && cmake .. && cmake --build . --clean-first

# run
$ ./main/my_exe

```

## Generate eclipse project

```bash

# for linux
$ mkdir build && cd build && cmake -G "Eclipse CDT4 - Unix Makefiles" ..

# for windows
$ mkdir build && cd build && cmake -G "Eclipse CDT4 - MinGW Makefiles" ..

```
