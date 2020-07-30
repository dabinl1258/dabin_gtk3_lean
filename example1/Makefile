.PHONY: run
run : out
	./out
out : example1.o
	gcc -o out example1.o `pkg-config --libs gtk+-3.0`  
example1.o : example1.c
	gcc -c example1.c `pkg-config --cflags gtk+-3.0` 