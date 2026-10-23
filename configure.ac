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

# We require at least autoconf 2.63 (AC_INIT format changed there).
AC_PREREQ([2.63])

AC_INIT([sigrok-firmware-custom], [0.1.0], [qq984487046@gmail.com],
	[sigrok-firmware-custom], [https://github.com/norinq/sigrok-firmware-custom])
AC_CONFIG_AUX_DIR([autostuff])

# We require at least automake 1.11 (needed for 'silent rules').
AM_INIT_AUTOMAKE([1.11 -Wall -Werror foreign no-define nostdinc])
AM_SILENT_RULES([yes])

AC_PROG_INSTALL

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
