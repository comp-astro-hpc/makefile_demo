CC      = gcc
CFLAGS  = -Wno-implicit-function-declaration

hello: hello.o msg.o
	@echo "compiling..."
	@$(CC) $^ $(CFLAGS) -o $@

hello.o: hello.c
	@$(CC) $(CFLAGS) -c $<

msg.o: msg.c
	@$(CC) $(CFLAGS) -c $<

all: hello

clean:
	rm -rf *.o hello

