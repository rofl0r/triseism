#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

#AC_PREREQ(2.57)
AC_INIT(src/q3vm.c, [0.01], [phaethon@linux.ucla.edu])
AM_INIT_AUTOMAKE([triseism], [0.01])
AM_CONFIG_HEADER([config.h])
AC_CONFIG_SRCDIR([src/q3vm.h])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS([stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_CONST

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_VPRINTF
AC_CHECK_FUNCS([memset])

AC_CONFIG_FILES([Makefile
                 src/Makefile])
AC_OUTPUT
