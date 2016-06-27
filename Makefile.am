vmgldir = $(includedir)/X11/extensions
vmgl_HEADERS = \
	vmgl_ext.h \
	vmgl_extproto.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = vmglproto.pc

EXTRA_DIST = vmglproto.pc.in

MAINTAINERCLEANFILES = ChangeLog INSTALL

.PHONY: ChangeLog INSTALL

INSTALL:
	    $(INSTALL_CMD)

ChangeLog:
	    $(CHANGELOG_CMD)

dist-hook: ChangeLog INSTALL

