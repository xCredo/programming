IntVector: main.c IntVector.c
	gcc -w -o IntVector main.c IntVector.c

main.o: main.c
	gcc -c main.c

IntVector.o: IntVector.c
	gcc -c IntVector.c

.PHONY: clean
clean:
	rm IntVector *.o