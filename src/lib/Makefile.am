## $NetBSD: Makefile.am,v 1.9 2010/11/06 03:42:59 agc Exp $

AM_CFLAGS		= $(WARNCFLAGS)

lib_LTLIBRARIES		= libnetpgp.la

libnetpgp_la_CPPFLAGS	= -I$(top_srcdir)/include

libnetpgp_la_SOURCES	= \
	bufgap.c \
	compress.c \
	create.c \
	crypto.c \
	fastctype.c \
	keyring.c \
	misc.c \
	netpgp.c \
	openssl_crypto.c \
	packet-parse.c \
	packet-print.c \
	packet-show.c \
	reader.c \
	signature.c \
	ssh2pgp.c \
	symmetric.c \
	validate.c \
	writer.c

dist_man_MANS		= libnetpgp.3
