# CMake binaries for Alpine

This repository produces the binaries of a specific version of CMake for
Alpine. It's needed by our internal images which is installing CMake, except
that no official binaries compiled for Alpine are available.

> The official distributed binaries of CMake will not work on Alpine because it's linked against a different C library (glibc != musl).

Instructions taken and adapted from: https://git.alpinelinux.org/aports/tree/main/cmake
