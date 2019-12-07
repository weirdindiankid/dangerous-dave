CC = gcc
INCS = -I /usr/local/Cellar/sdl2/2.0.10/include/SDL2
LIBS = -L /usr/local/Cellar/sdl2/2.0.10/lib

CFLAGS = -std=gnu89 -Wall
LFLAGS = -lSDL2main -lSDL2

SRC = lmdave.c
OBJ = lmdave

all: $(SRC)
	$(CC) $(SRC) $(INCS) $(LIBS) $(CFLAGS) $(LFLAGS) -o $(OBJ)
