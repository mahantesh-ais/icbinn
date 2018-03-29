#
#
# Makefile.am:
#
#
# $Id:$
#
# $Log:$
#
#
#

#
# Copyright (c) 2012 Citrix Systems, Inc.
# 
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation; either
# version 2.1 of the License, or (at your option) any later version.
# 
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Lesser General Public License for more details.
# 
# You should have received a copy of the GNU Lesser General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
#

LIBICBINN_LIBS_NO_DL=${LIBICBINN_LIBS:-ldl=}

libicbinn_resolved_la_SOURCES =

lib_LTLIBRARIES=libicbinn_resolved.la

libicbinn_resolved_la_LDFLAGS=-Wl,--no-as-needed
libicbinn_resolved_la_LDFLAGS+=-nostdlib
libicbinn_resolved_la_LDFLAGS+=-nodefaultlibs
libicbinn_resolved_la_LDFLAGS+=-Wl,-u
libicbinn_resolved_la_LDFLAGS+=-Wl,icbinn_canary
libicbinn_resolved_la_LDFLAGS+=-Wl,-Bstatic ${LIBICBINN_LIBS_NO_DL}
libicbinn_resolved_la_LDFLAGS+=-Wl,-Bdynamic
