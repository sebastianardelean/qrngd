# QRNGD
[![CMake on a single platform](https://github.com/sebastianardelean/qrngd/actions/workflows/cmake-single-platform.yml/badge.svg)](https://github.com/sebastianardelean/qrngd/actions/workflows/cmake-single-platform.yml)

## Build

```
cmake -G Ninja -DCMAKE_BUILD_TYPE=Release ..

cmake --build .

cpack -V -G DEB
```
