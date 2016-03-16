SUBDIRS = plugins

MAINTAINERCLEANFILES = \
	$(GITIGNORE_MAINTAINERCLEANFILES_TOPLEVEL) \
	$(GITIGNORE_MAINTAINERCLEANFILES_MAKEFILE_IN) \
	$(NULL)

# Some plugins have file names longer than what tar accepts, hence we
# need to use another archive format.
DIST_ARCHIVES = $(distdir).zip
DIST_TARGETS = dist-zip

-include $(top_srcdir)/git.mk
