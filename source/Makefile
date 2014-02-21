CC := gcc
CFLAGS := -O2 -pipe -march=native -fomit-frame-pointer -ggdb
LDFLAGS := -Wl,--as-needed
OUT := pngdefry

pngdefry: miniz.c pngdefry.c
	$(CC) -o $(OUT) $(CFLAGS) $(LDFLAGS) pngdefry.c

clean:
	rm -f $(OUT)
