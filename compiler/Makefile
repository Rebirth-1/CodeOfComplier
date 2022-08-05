EXE=compiler
CC=g++
SRC=main.c compiler.c lexial.c parser.c error.c semantic.c generator.c
OBJ=main.o compiler.o lexial.o parser.o error.o semantic.o generator.o
CFLAGS=-g -Wno-deprecated
$(EXE):$(OBJ)
	$(CC) -Wno-deprecated -c $(SRC)
	$(CC) $(OBJ) -o $(EXE) $(CFLAGS)
	rm $(OBJ) *~ -f
clean:
	rm $(EXE) $(OBJ) *~ -f
