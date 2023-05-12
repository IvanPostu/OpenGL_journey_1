# OpenGL Journey - 1

## Build

```bash

# clean & build
$ cmake . && cmake --build . --clean-first

# run
$ ./bin/my_exe

```

## Generate eclipse project

```bash

# for linux
$ cmake -G "Eclipse CDT4 - Unix Makefiles" -DCMAKE_BUILD_TYPE=Debug ..

# for windows
$ cmake -G "Eclipse CDT4 - MinGW Makefiles" -DCMAKE_BUILD_TYPE=Debug ..

```

## IDEA - Eclipse

**Should be installed eclipse for C/C++ development**
- <img src="./_for_readme/eclipse1.png" alt="My Image" width="400" height="250" />
**Uncheck all except C/C++**
- <img src="./_for_readme/eclipse2.png" alt="My Image" width="200" height="250" />
**Import, existing projects into workspace**
**Debug configuration** `./bin/my_exe` path to binary
- <img src="./_for_readme/eclipse3.png" alt="My Image" width="550" height="350" />


## Eclipse - shortcuts
- Ctrl + Shift + R (on Windows and Linux) or Cmd + Shift + R (on Mac) to search for a file by name.
- Ctrl + Shift + T (on Windows and Linux) or Cmd + Shift + T (on Mac) to search for a type or class by name.
- F6 - Debug: step over
- F8 - Debug: resume