# Copyright (c) 2018 Deyuan Guo. All rights reserved.
# This file is subject to the terms and conditions defined
# in file 'LICENSE' in this source code package.

.PHONY: all clean

CC = g++
LIBS =
CFLAGS = -Wall -std=c++11

SRCS = $(wildcard *.cc)
OBJS = $(SRCS:.cc=.out)

%.out: %.cc
	$(CC) $(CFLAGS) $< -o $@ $(LIBS)

all: $(OBJS)

clean:
	rm -rf *.out

