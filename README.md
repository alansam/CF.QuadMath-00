# Explore GNU 128-bit Numbers

Uses the `quadmath.h` header file.

The code would not compile using clang but the building with the current version of
gcc (gcc-15) was successful.

It does need the libquadlib in order to link correctly; add -lquadlib to the build.

## GNU Documentation

- [The GCC Quad-Precision Math Library](https://gcc.gnu.org/onlinedocs/libquadmath.pdf)
- [GCC libquadmath](https://gcc.gnu.org/onlinedocs/libquadmath/)
