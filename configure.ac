# Autoconf requirements 
# Initialize. Note parameters, brackets, and whitespace
AC_INIT([hello], [0.01], 
[http://x.example.com/])

# autoconf version >= 2.68
AC_PREREQ([2.68])			

# Safety: File must exist
AC_CONFIG_SRCDIR([src/hello.c])		

# Make config header
AC_CONFIG_HEADERS([config.h])		

# Auxiliary files go here
AC_CONFIG_AUX_DIR([build-aux])		

# Use "m4" directory for internal "m4" files:q
AC_CONFIG_MACRO_DIR([m4])		

# Enable  automake to create makefile
AM_INIT_AUTOMAKE([1.11 subdir-objects -Wall -Werror])	
AC_CONFIG_FILES([Makefile])		

# Look for compilers
AC_PROG_CC 				

# Various checks go here

AC_OUTPUT
