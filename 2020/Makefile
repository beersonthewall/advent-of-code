CC=gcc
CFLAGS=-Wall

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

clean:
	rm day1 day2
	rm *.o

day1: day1.o
	gcc -o day1 day1.o

day2: day2.o
	gcc -o day2 day2.o
