pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = librpitools.pc

lib_LTLIBRARIES = librpitools.la

librpitools_la_SOURCES = src/PCD8544.c

AM_CFLAGS = -I$(top_srcdir)/include

include_HEADERS = include/PCD8544.h

librpitools_la_LDFLAGS = -lwiringPi
