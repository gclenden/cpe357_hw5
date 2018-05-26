CC = gcc
CFLAGS =-Wall -g
MAIN = parseline
OBJS = parseline.o

all : $(MAIN)

$(MAIN) : $(OBJS)
	$(CC) $(CFLAGS) -o $(MAIN) $(OBJS)

parseline.o: parseline.c parseline.h
	$(CC) $(CFLAGS) -c parseline.c

clean :
	rm *.o $(MAIN)

handin:
	handin getaylor-grader 357hw5-11 handindir/*

test: 
	~getaylor-grader/tryAsgn5
