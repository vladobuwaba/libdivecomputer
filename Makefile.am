SUBDIRS = include src

if ENABLE_EXAMPLES
SUBDIRS += examples
endif

AM_MAKEFLAGS = -s
ACLOCAL_AMFLAGS = -I m4

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libdivecomputer.pc

EXTRA_DIST = \
	libdivecomputer.pc.in \
	msvc/libdivecomputer.vcproj
