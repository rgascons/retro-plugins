# When there are no modules to check, default to 'no', hence we need to
# force it to 'yes'.
#PKG_CHECK_MODULES(ATARI_2600_PLUGIN, [
#], [enable_atari_2600_plugin=yes], [enable_atari_2600_plugin=no])
enable_atari_2600_plugin=yes

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET


AM_CONDITIONAL(ENABLE_ATARI_2600_PLUGIN, test x$enable_atari_2600_plugin != xno)

AC_CONFIG_FILES([
	plugins/atari-2600/Makefile
])