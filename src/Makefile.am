lib_LTLIBRARIES = libusbg.la
libusbg_la_SOURCES = usbg.c
if TEST_GADGET_SCHEMES
libusbg_la_SOURCES += usbg_schemes_libconfig.c
else
libusbg_la_SOURCES += usbg_schemes_none.c
endif
libusbg_la_LDFLAGS = $(LIBCONFIG_LIBS)
libusbg_la_LDFLAGS += -version-info 0:1:0
libusbg_la_CFLAGS = $(LIBCONFIG_CFLAGS)
AM_CPPFLAGS=-I$(top_srcdir)/include/
