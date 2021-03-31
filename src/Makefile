# SPDX-License-Identifier: GPL-3.0-or-later
# Makefile for apoplexy 3.14.1 by The apoplexy Team (see credits.txt)
#
# cppcheck --language=c --std=c99 --verbose apoplexy.c
# Also try the line below with clang instead of gcc.
#
all:
	gcc -O2 -Wno-unused-result -std=c99 -g -pedantic -Wall -Wextra -Wshadow -Wpointer-arith -Wcast-qual -Wstrict-prototypes -Wmissing-prototypes apoplexy.c -o ../apoplexy `sdl2-config --cflags --libs` -I/usr/include/SDL2 -D_REENTRANT -lSDL2_ttf -lSDL2_image -lm -lcurl -lzip -Wno-format-truncation
