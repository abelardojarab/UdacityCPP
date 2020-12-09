OBJS	= A_star_complete.o
SOURCE	= A_star_complete.cpp
HEADER	=
OUT	= A_Star_Search
CC	 = g++
FLAGS	 = -g -c -Wall
LFLAGS	 =

all: $(OBJS)
	$(CC) -g $(OBJS) -o $(OUT) $(LFLAGS)

A_star_complete.o: A_star_complete.cpp
	$(CC) $(FLAGS) A_star_complete.cpp

#test.o: test.cpp
#	$(CC) $(FLAGS) test.cpp

clean:
	rm -f $(OBJS) $(OUT)
