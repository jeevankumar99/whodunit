# Questions

## What's `stdint.h`?

It is used when an integer with a certain width is used, for lines 7 through 10 in bmp.h

## What's the point of using `uint8_t`, `uint32_t`, `int32_t`, and `uint16_t` in a program?

They are integers with an exact size, for example int32 is a 32 bit integer, int 8 is 8 bits and so on.

## How many bytes is a `BYTE`, a `DWORD`, a `LONG`, and a `WORD`, respectively?

a BYTE is 8 bits, DWORD is 32 bits, LONG is 32 bits and WORD is 16 bits.

## What (in ASCII, decimal, or hexadecimal) must the first two bytes of any BMP file be? Leading bytes used to identify file formats (with high probability) are generally called "magic numbers."

255 216 255

## What's the difference between `bfSize` and `biSize`?

TODO

## What does it mean if `biHeight` is negative?

It indicates that the bmp is coded in a top down way.

## What field in `BITMAPINFOHEADER` specifies the BMP's color depth (i.e., bits per pixel)?

biColourImportant

## Why might `fopen` return `NULL` in lines 24 and 32 of `copy.c`?

If the file it is trying to open does not exist, or if it cannot access it, the file cannot be opened.

## Why is the third argument to `fread` always `1` in our code?

That is because we are reading one nmem of data each time.

## What value does line 65 of `copy.c` assign to `padding` if `bi.biWidth` is `3`?

3

## What does `fseek` do?

it moves the cursor to a particular location in a file as per it's arguements

## What is `SEEK_CUR`?

It makes the offset to the current position indicator.

## Whodunit?

Professor Plum.
