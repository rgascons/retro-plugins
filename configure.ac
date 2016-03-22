AC_INIT([retro-plugins], [0.6.0])
AM_INIT_AUTOMAKE([foreign subdir-objects])

AC_PROG_CC

LT_INIT

# Plugins
m4_include([plugins/atari-2600/configure.ac])
m4_include([plugins/game-boy/configure.ac])
m4_include([plugins/mame/configure.ac])
m4_include([plugins/neo-geo-pocket/configure.ac])
m4_include([plugins/nes/configure.ac])
m4_include([plugins/pc-engine/configure.ac])
m4_include([plugins/snes/configure.ac])

PKG_CHECK_MODULES(RETRO_PLUGINS, [
	retro-gobject-0.6
])

AC_CONFIG_FILES([
	Makefile
	plugins/Makefile
	plugins/submodule-plugin.mk
])

AC_OUTPUT
