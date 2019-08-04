# Hello-World-em-Assembly
Para compilar em assembly tem que fazer o seguinte:

-Instale o nasm
-Na linha de comando do terminal vá até o diretorio do seu arquivo e faça:

$ nasm -f elf32 nome.asm (para máquinas 32 bits)
$ nasm -f elf64 nome.asm (para máquinas 64 bits)

-Gere o executável .x:

$ ld nome.o -o nome.x

- Por fim para executar:

$ ./nome.x

