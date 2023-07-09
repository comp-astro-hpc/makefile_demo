CC      = gcc
CFLAGS  = -lm -Wno-implicit-function-declaration

hello: hello.c
	@echo "compiling..."
	$(CC) $< $(CFLAGS) -o $@

clean:
	rm -rf hello

