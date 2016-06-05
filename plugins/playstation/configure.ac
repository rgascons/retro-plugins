# When there are no modules to check, default to 'no', hence we need to
# force it to 'yes'.
#PKG_CHECK_MODULES(ENABLE_PLAYSTATION_PLUGIN, [
#], [enable_playstation_plugin=yes], [enable_playstation_plugin=no])
enable_playstation_plugin=yes

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET


AM_CONDITIONAL(ENABLE_PLAYSTATION_PLUGIN, test x$enable_playstation_plugin != xno)

AC_CONFIG_FILES([
	plugins/playstation/Makefile
])
