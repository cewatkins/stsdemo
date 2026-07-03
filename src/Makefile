
CC := gcc
CFLAGS := -std=c11 -Wall -Wextra -Werror -O2
BIN := stsdemo

.PHONY: all clean run

all: $(BIN)

$(BIN): main.c
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -f $(BIN)

run: $(BIN)
	./$(BIN)
