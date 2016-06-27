AC_PREREQ([2.57])
AC_INIT([VMGLProto], [0.1.0], [http://www.cs.toronto.edu/~andreslc/vmgl])
AM_INIT_AUTOMAKE([foreign dist-bzip2])

# XORG_RELEASE_VERSION
# Require xorg-macros: XORG_DEFAULT_OPTIONS
m4_ifndef([XORG_MACROS_VERSION],
          [m4_fatal([must install xorg-macros 1.3 or later before running autoconf/autogen])])
XORG_MACROS_VERSION(1.3)
XORG_DEFAULT_OPTIONS

AC_CONFIG_FILES([Makefile
           vmglproto.pc])
AC_OUTPUT

