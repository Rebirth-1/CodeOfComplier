EXE=ass
CC=g++
SRC=main.c lexial.c parser.c semantic.c generator.c elf_file.c
OBJ=main.o lexial.o parser.o semantic.o generator.o elf_file.o
CFLAGS=-g -Wno-deprecated
$(EXE):$(OBJ)
	$(CC) -Wno-deprecated -c $(SRC)
	$(CC) $(OBJ) -o $(EXE) $(CFLAGS)
	rm $(OBJ) *~ -f
clean:
	rm $(EXE) $(OBJ) *~ -f
