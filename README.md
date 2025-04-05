# cximage-unix

Computer vision library for CPP.

# Building

To build as a shared library use scons:

```shell
scons
```

To install the shared library to /usr/local/lib and include headers to /usr/local/include (you may need to be root):

```shell
scons install
```

To install just the shared library:

```shell
scons install-lib
```

To install just the include headers:

```shell
scons install-lib
```

To clean up an action:

```shell
scons -c [install|install-lib|install-inc]
```

## ⚠️ Disclaimer ⚠️

I'm not the original creator of this library, all credits go to Davide Pizzolato and his original [codeproject article](https://www.codeproject.com/Articles/1300/CxImage).

I just modified some files to make it compatible with linux/unix/macos systems.
