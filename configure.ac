AC_INIT([retro-plugins], [0.4.0])
AM_INIT_AUTOMAKE([foreign subdir-objects])

AC_PROG_CC

LT_INIT

# Plugins

PKG_CHECK_MODULES(RETRO_PLUGINS, [
	retro-gobject-0.4
])

AC_CONFIG_FILES([
	Makefile
	plugins/Makefile
])

AC_OUTPUT
