OBJ = trap-omp
CC = g++
CFLAGS = -o $(OBJ)
LFLAGS = -lm -fopenmp

$(OBJ):
	$(CC) $(CFLAGS) $(OBJ).c $(LFLAGS)

clean:
	@rm -f $(OBJ)
