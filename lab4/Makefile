#
# Student makefile for Cache Lab
# 
CC = gcc
CFLAGS = -g -Wall -Werror -std=c99

all: csim

csim: csim.c cachelab.c cachelab.h
	$(CC) $(CFLAGS) -o csim csim.c cachelab.c -lm 

#
# Clean the src dirctory
#
clean:
	rm -rf *.o
	rm -f csim
	rm -f .csim_results .marker
