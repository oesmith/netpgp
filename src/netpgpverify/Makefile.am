## $NetBSD: Makefile.am,v 1.4 2010/11/06 00:03:34 agc Exp $

if BUILD_PROGRAMS

AM_CFLAGS		= $(WARNCFLAGS)

bin_PROGRAMS		= netpgpverify

netpgpverify_SOURCES	= verify.c

netpgpverify_CPPFLAGS	= -I$(top_srcdir)/include

netpgpverify_LDADD	= ../lib/libnetpgp.la

dist_man_MANS		= netpgpverify.1

endif
