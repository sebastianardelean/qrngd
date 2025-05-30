# QRNGD
[![Debian Build](https://github.com/sebastianardelean/qrngd/actions/workflows/build_deb.yml/badge.svg)](https://github.com/sebastianardelean/qrngd/actions/workflows/build_deb.yml)

## Build

```
cmake -G Ninja -DCMAKE_BUILD_TYPE=Release ..

cmake --build .

cpack -V -G DEB
```
