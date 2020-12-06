all: ss

ss:main.o sportsscoreboard.o
	gcc -Wall -o ss main.o sportsscoreboard.o

main.o:main.c
	gcc -c -Wall main.c
sportsscoreboard.o:sportsscoreboard.c
	gcc -c -Wall sportsscoreboard.c