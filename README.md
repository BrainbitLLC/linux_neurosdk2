# Overview

Library compiled for AstraLinux v2.12.46, kernel v5.15.0. Arch: x86_64

```
user@astra:~$ ldd --version
ldd (Debian GLIBC 2.28-10+deb10u1) 2.28
Copyright (C) 2018 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
Written by Roland McGrath and Ulrich Drepper.
```

And dependencies:
```
linux-vdso.so.1
libblkid.so.1
libc++.so.1
libc++abi.so.1 
libc.so.6
libdl.so.2
libffi.so.6
libgcc_s.so.1
libgio-2.0.so.0
libglib-2.0.so.0
libgmodule-2.0.so.0
libgobject-2.0.so.0
libm.so.6
libmount.so.1
libpcre.so.3
libpthread.so.0
libresolv.so.2 
librt.so.1
libselinux.so.1
libstdc++.so.6
libudev.so.1
libuuid.so.1
libz.so.1
/lib64/ld-linux-x86-64.so.2
```

We put the library dependencies next to the library itself, if you are using a system different from ours I suggest you link them to your project too.

# Install

First way:
Download library, dependencies and headers from folder `raw_lib` and add .so to your project by your preferred way.

Sesond way:
Download .deb package from folder `package` and install with `apt`:

```
sudo apt install libneurosdk2.deb
```

Latest version: `1.0.6.29`

[Samples for BrainBit](https://gitlab.com/neurosdk2/neurosamples/-/tree/main/cpp/brainbit?ref_type=heads)
[Samples for Callibri](https://gitlab.com/neurosdk2/neurosamples/-/tree/main/cpp/callibri?ref_type=heads)