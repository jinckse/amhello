AC_INIT([hello], [0.01], 
[http://x.example.com/])
AC_PREREQ([2.68])			# autoconf version >= 2.68
AC_CONFIG_SRCDIR([hello.c])		# Safety: File must exist
AC_CONFIG_HEADERS([config.h])		# Make config header
AC_CONFIG_AUX_DIR([build-aux])		# Auxiliary files go here
AM_INIT_AUTOMAKE([1.11 -Wall -Werror])	# Init automake
AC_CONFIG_FILES([Makefile])		# "configure" will create Makefile
AC_PROG_CC 				# Find and probe C compiler
AC_PROG_CXX 				# Find and probe C++ compiler
# Various checks go here
AC_OUTPUT
