fails here:

```
checking for x86_64-linux-musl-pkg-config... no
checking for pkg-config... //bin/pkg-config
checking for GLIB - version >= 2.28.0... no
*** Could not run GLIB test program, checking why...
*** The test program failed to compile or link. See the file config.log for the
*** exact error that occurred. This usually means GLIB is incorrectly installed.
*** trying without -lgmodule
checking for x86_64-linux-musl-pkg-config... //bin/pkg-config
checking pkg-config is at least version 0.7... yes
checking for GLIB - version >= 2.28.0... no
*** Could not run GLIB test program, checking why...
*** The test program failed to compile or link. See the file config.log for the
*** exact error that occurred. This usually means GLIB is incorrectly installed.

*** If you don't have GLIB, you can get it from ftp://ftp.gtk.org/pub/glib/
*** We recommend you get the latest stable GLIB 2 version.
*** Compile and install it, and make sure pkg-config finds it,
*** by adding the path where the .pc file is located to PKG_CONFIG_PATH
*** Or alternatively install your distribution's package.
```
