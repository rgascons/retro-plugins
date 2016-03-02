# When there are no modules to check, default to 'no', hence we need to
# force it to 'yes'.
#PKG_CHECK_MODULES(GAME_BOY_PLUGIN, [
#], [enable_game_boy_advance_plugin=yes], [enable_game_boy_advance_plugin=no])
enable_game_boy_advance_plugin=yes

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AC_PROG_CPP
AC_PROG_INSTALL
AC_PROG_LN_S
AC_PROG_MAKE_SET


AM_CONDITIONAL(ENABLE_GAME_BOY_ADVANCE_PLUGIN, test x$enable_game_boy_advance_plugin != xno)

AC_CONFIG_FILES([
	plugins/game-boy-advance/Makefile
])
