CC = gcc
FILES = main.c
OUT_EXE = main

build: $(FILES)
	$(CC) -o $(OUT_EXE) $(FILES)

run: build
	./$(OUT_EXE)
clean:
	rm -f *.o $(OUT_EXE)