ifndef CC
	CC=gcc
endif
CFLAGS=-std=c99 -Werror -Wall -pedantic -Wextra
SRCS=main.c
OBJS=$(subst .c,.o,$(SRCS))
RM=rm -f

all: main

clean:
	$(RM) $(OBJS) main

