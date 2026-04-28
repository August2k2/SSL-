CC = gcc
CFLAGS = -Wall -g

all: hello.exe

hello.exe: hello.c
	$(CC) $(CFLAGS) hello.c -o hello.exe

clean:
	del hello.exe

run: hello.exe
	./hello.exe