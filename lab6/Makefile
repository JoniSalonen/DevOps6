# C++ compiler
CC=g++

prog: hello.o
	$(CC) -o prog hello.o

hello.o: hello.cpp hello.h
	$(CC) -c hello.cpp -o hello.o


.PHONY
clean:
	rm -rf *o hello