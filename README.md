# Hello-World-em-Assembly
#### Para compilar em assembly tem que fazer o seguinte:

<p>Instale o nasm<br>

<p>Na linha de comando do terminal vá até o diretorio do seu arquivo e faça:<br>

    nasm -f elf32 nome.asm (para máquinas 32 bits)
    nasm -f elf64 nome.asm (para máquinas 64 bits) 
</li>

<p>Gere o executável .x:<br>

    ld nome.o -o nome.x
</li>

<p>Por fim para executar:<br>

    ./nome.x
</li>
