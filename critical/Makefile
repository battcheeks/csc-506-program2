OBJ = trap-omp
CC = g++
CFLAGS = -o $(OBJ)
LFLAGS = -lm -fopenmp

$(OBJ):
	$(CC) $(CFLAGS) $(OBJ).c $(LFLAGS)

.PHONY: run clean

run: $(OBJ)
	@./$(OBJ)

clean:
	@rm -f $(OBJ)
