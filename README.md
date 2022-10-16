https://peat-silicon-f53.notion.site/DSR-Embedded-Systems-Training-05eeb1cf6ee847348207cd58bffb9538

gcc -E (calling preprocessor) main.c -o main.i
gcc -S (calling compilator) main.i -o main.s
gcc -c (calling assembler) main.s -o main.o
gcc main.o -o main