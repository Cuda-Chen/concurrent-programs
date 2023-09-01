all:
	gcc -Wall -O2 -o test-cmap \
		cmap.c  random.c  rcu.c  test-cmap.c \
		-lpthread

debug:
	gcc -Wall -g -o test-cmap \
		cmap.c  random.c  rcu.c  test-cmap.c \
		-lpthread \
		-fsanitize=thread

clean:
	rm -f test-cmap
