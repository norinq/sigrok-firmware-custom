##
## This file is part of the sigrok-firmware project.
##
## Copyright (C) 2026 Norinq <qq984487046@gmail.com>
##
## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 2 of the License, or
## (at your option) any later version.
##
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with this program; if not, see <http://www.gnu.org/licenses/>.
##

GNUMAKEFLAGS = --no-print-directory

pkgdatadir = $(datadir)/sigrok-firmware

dist_pkgdata_DATA = \
	dreamsourcelab/LICENSE.DreamSourceLab \
	dreamsourcelab/dreamsourcelab-dscope-fpga.fw \
	dreamsourcelab/dreamsourcelab-dscope-fx2.fw \
	dreamsourcelab/dreamsourcelab-dslogic-basic-fpga.fw \
	dreamsourcelab/dreamsourcelab-dslogic-basic-fx2.fw \
	dreamsourcelab/dreamsourcelab-dslogic-fpga-3v3.fw \
	dreamsourcelab/dreamsourcelab-dslogic-fpga-5v.fw \
	dreamsourcelab/dreamsourcelab-dslogic-fx2.fw \
	dreamsourcelab/dreamsourcelab-dslogic-plus-fpga.fw \
	dreamsourcelab/dreamsourcelab-dslogic-plus-fx2.fw \
	dreamsourcelab/dreamsourcelab-dslogic-pro-fpga.fw \
	dreamsourcelab/dreamsourcelab-dslogic-pro-fx2.fw \
	dreamsourcelab/dreamsourcelab-dslogic-u3pro32-fpga.fw

MAINTAINERCLEANFILES = ChangeLog

.PHONY: ChangeLog
ChangeLog:
	git --git-dir '$(top_srcdir)/.git' log >$@ || touch $@

dist-hook: ChangeLog

