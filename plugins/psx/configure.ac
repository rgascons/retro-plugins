# When there are no modules to check, default to 'no', hence we need to
# force it to 'yes'.
#PKG_CHECK_MODULES(PSX_PLUGIN, [
#], [enable_psx_plugin=yes], [enable_psx_plugin=no])
enable_psx_plugin=yes

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET


AM_CONDITIONAL(ENABLE_PSX_PLUGIN, test x$enable_psx_plugin != xno)

AC_CONFIG_FILES([
	plugins/psx/Makefile
])
