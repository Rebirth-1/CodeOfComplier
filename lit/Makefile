EXE=lit
CC=g++
SRC=main.c elf_file.c linker.c
OBJ=main.o elf_file.o linker.o
CFLAGS=-g -Wno-deprecated
$(EXE):$(OBJ)
	$(CC) -Wno-deprecated -c $(SRC)
	$(CC) $(OBJ) -o $(EXE) $(CFLAGS)
	rm $(OBJ) *~ -f
clean:
	rm $(EXE) $(OBJ) *~ -f
