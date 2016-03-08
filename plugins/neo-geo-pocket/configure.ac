# When there are no modules to check, default to 'no', hence we need to
# force it to 'yes'.
#PKG_CHECK_MODULES(NEO_GEO_POCKET_PLUGIN, [
#], [enable_neo_geo_pocket_plugin=yes], [enable_neo_geo_pocket_plugin=no])
enable_neo_geo_pocket_plugin=yes

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET


AM_CONDITIONAL(ENABLE_NEO_GEO_POCKET_PLUGIN, test x$enable_neo_geo_pocket_plugin != xno)

AC_CONFIG_FILES([
	plugins/neo-geo-pocket/Makefile
])
