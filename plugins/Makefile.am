# temp. solution while mailcheck & xdcc arn't in SUBDIRS
EXTRA_DIST = plugin20.html Make.plugin plugin-conf.in \
				xdcc/xdcc.c \
				xdcc/Makefile.am

noinst_HEADERS = xchat-plugin.h

if DO_PYTHON
pythondir = python
endif

if DO_PERL
perldir = perl
endif

if DO_TCL
tcldir = tcl
endif

if DO_SASL
sasldir = sasl
endif

if DO_DOAT
doatdir = doat
endif

if DO_FISHLIM
fishlimdir = fishlim
endif

if DO_CHECKSUM
checksumdir = checksum
endif

if DO_SYSINFO
sysinfodir = sysinfo
endif

#SUBDIRS = . $(pythondir) $(perldir) mailcheck xdcc
SUBDIRS = . $(pythondir) $(perldir) $(tcldir) $(sasldir) $(doatdir) $(fishlimdir) $(checksumdir) $(sysinfodir)
