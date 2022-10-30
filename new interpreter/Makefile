# Project: new_interpreter
# Makefile created by Dev-C++ 4.9.9.2

CC   = gcc
RES  = 
OBJ  = instructions.o main.o VM_duongnn.o $(RES)
LINKOBJ  = instructions.o main.o VM_duongnn.o $(RES)
BIN  = new_interpreter.exe
RM = rm -f

.PHONY: all all-before all-after clean clean-custom

all: all-before new_interpreter.exe all-after


clean: clean-custom
	${RM} $(OBJ) $(BIN)

$(BIN): $(OBJ)
	$(CC) $(LINKOBJ) -o new_interpreter

instructions.o: instructions.c
	$(CC) -c instructions.c -o instructions.o $(CXXFLAGS)

main.o: main.c
	$(CC) -c main.c -o main.o $(CXXFLAGS)

VM_duongnn.o: VM_duongnn.c
	$(CC) -c VM_duongnn.c -o VM_duongnn.o $(CXXFLAGS)
