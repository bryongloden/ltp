#
#    kernel/lib Makefile.
#
#    Copyright (C) 2012, Linux Test Project.
#
#    This program is free software; you can redistribute it and/or modify
#    it under the terms of the GNU General Public License as published by
#    the Free Software Foundation; either version 2 of the License, or
#    (at your option) any later version.
#
#    This program is distributed in the hope that it will be useful,
#    but WITHOUT ANY WARRANTY; without even the implied warranty of
#    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#    GNU General Public License for more details.
#
#    You should have received a copy of the GNU General Public License along
#    with this program; if not, write to the Free Software Foundation, Inc.,
#    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
#

top_srcdir		?= ../../..

include $(top_srcdir)/include/mk/env_pre.mk

CPPFLAGS		+= $(NUMA_CPPFLAGS) -I$(abs_srcdir)/../include \
			   -I$(abs_builddir)/../include
INTERNAL_LIB		:= libkerntest.a

include $(top_srcdir)/include/mk/lib.mk
