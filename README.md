# asio_http_server

The simplest HTTP server using Boost.Asio

## Build

```shell
mkdir build && cd build
conan install .. -of .
cmake --preset conan-release ..
cmake --build .
```