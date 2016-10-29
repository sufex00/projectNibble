# projectNibble
O projeto consiste em implementar um processador de 8 bits com conjunto de instruções
reduzido, cujo núcleo foi projetado com arquitetura Harvard e 4 estágios de pipeline. O nome
do projeto é Nibble, figura abaixo, o qual possui apenas 6 instruções: ADD, ADDP, SUB, SUBP,
END e MDUMP. As instruções são gravadas na memória de programa (também chamada de
flash) e utiliza a memória RAM para armazenar os resultados das operações. O conteúdo do
processador são os seguintes módulos:
1.Memória de programa (ROM);
2.Decodificador de instrução;
3.Memória de dados (RAM);
4.Multiplexadores;
5.Módulo complemento a 2;
6.Somador completo (8 bits);
7.Registradores de carga paralela [1] (PC, ADDR, X, OP, Y e R) ;
8.Módulo de controle central.

Referências
[1] - ​ https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Seq/parload.htm ​ l
[2] - ​ https://www.altera.com/support/training/university/materials-tutorials.html








