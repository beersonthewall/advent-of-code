CC=gcc
CFLAGS=-Wall

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

clean:
	rm *.o
	rm day1 day2 day3 -f

day1: day1.o
	$(CC) -o day1 day1.o

day2: day2.o
	$(CC) -o day2 day2.o

day3: day3.o
	$(CC) -o day3 day3.o
