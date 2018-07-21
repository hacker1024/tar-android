# GNU tar binaries built with the Android NDK

## Information
Read more about tar on its [webpage](https://www.gnu.org/software/tar/).  
Sources are available [here](https://ftp.gnu.org/gnu/tar/).

## Building
To build, run `./configure` with the following environment variables set:

```
CFLAGS="-pie"
CPPFLAGS="-pie"
CC=/path/to/android/toolchain/clang
```
