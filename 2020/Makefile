CC=gcc
CFLAGS=-Wall

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

clean:
	rm day1
	rm *.o

day1: day1.o
	gcc -o day1 day1.o
