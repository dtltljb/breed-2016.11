#
# (C) Copyright 2000-2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# SPDX-License-Identifier:	GPL-2.0+

obj-y	= cpu.o reset.o

ifndef CONFIG_SPL_BUILD
obj-y	= cpu.o timer.o reset.o
obj-y	+= relocate.o
endif

