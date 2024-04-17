
**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Linguagens de Programação I *

# Ficha de Exercícios - 5: Vetores

Na resolução destes exercícios deve ser utilizada a Linguagem de Programação C. Para além da correta implementação dos requisitos, tenha em conta os seguintes aspetos:

- O código apresentado deve ser bem indentado. 
- O código deve compilar sem erros ou *warnings* utilizando o *gcc* com as seguintes flags:
- `-g -Wvla -Wall -Wpedantic -Wextra -Wdeclaration-after-statement`
- Tenha em atenção os nomes dados das variáveis, para que sejam indicadores daquilo que as mesmas vão conter.
- Evite o uso de constantes mágicas. 
- Evite duplicação de código. 
- Considere a implementação de funções para melhorar a legibilidade, evitar a duplicação e criar soluções mais genéricas.


1. [\*]	Preencher um vetor de 8 elementos inteiros inseridos pelo utilizador. Solicite um número do teclado. Pesquisar se esse número existe no vetor. Se existir, imprimir em qual posição do vetor. Se não existir, imprimir uma mensagem que não existe.

2.	[\*] Preencher um vetor x com 5 elementos inteiros pares entre número 2 a 20 inseridos pelo utilizador. Preencher um vetor y com 5 elementos inteiros ímpares de 10 a 19, inseridos pelo utilizador.  Somar os números que pertençam a mesma posição e imprimir cada resultado no ecrã, ou seja: x[0]+y[0],x[1]+y[1].

3. [\*] Preencher um vetor de 8 elementos inteiros inseridos pelo utilizador. Mostrar o vetor e informar quantos números são maiores que 30. Somar esses números maiores que 30.

4. [\*] Preencher um vetor de 8 elementos inteiros inseridos pelo utilizador. Mostrar o vetor na horizontal, espaçando os valores por tabs (\t). Calcular a média dos valores do vetor. Mostrar quantos números são múltiplos de 5. Quantos números são maiores que 10 e menores que 30. Qual o maior número do vetor.

5.	Preencher uma matriz com 3 nomes inseridos pelo utilizador, e mostrar quantas letras A (total de maiúsculas e minúsculas) e E (idem) têm nos 3 nomes.

6. Criar um algoritmo que lê um conjunto de 30 valores do teclado e os coloca em 2 vetores conforme estes valores forem pares ou ímpares. O tamanho do vetor é de 5 posições. Se algum vetor estiver cheio, escrevê-lo. Terminada a leitura escrever o conteúdo dos dois vetores. Cada vetor pode ser preenchido tantas vezes quantas for necessário.

7.	Armazenar nos vetores Nomes, PR1 e PR2 o nome e nota de duas provas de 6 alunos. Guardar no vetor Media a média de cada aluno e imprimir aprovado se a média for maior que 5 e reprovado se a média for menor ou igual a 5. OBS.: 2 vetores para as notas tipo float. 1 vetor para os nomes. 1 vetor para a média. 1 vetor para situação.

8.	Preencher um vetor com 5 números e guardar o cubo dos números em outro vetor. Mostrar os dois vetores.

9.	Preencher um vetor com os números 10 a 20, e depois mostrar os elementos pares do vetor de trás prá frente.

10.	Criar um algoritmo que leia os elementos de uma matriz inteira de 4 x 4 e imprima os elementos da diagonal principal.

11.	Criar um algoritmo que leia os elementos de uma matriz inteira de 3 x 3 e imprima todos os elementos, exceto os elementos da diagonal principal.

12.	Criar um algoritmo que leia os elementos de uma matriz inteira de 3 x 3 e adicione a outra matriz o resultado da multiplicação por 2 de cada elemento da primeira matriz.

13.	Criar um algoritmo que lê duas matrizes M(4,6) e N(4,6) e cria uma matriz que seja o produto de M por N.

14.	[\*] Elabore um programa que recebe um nome e imprime as 4 primeiras letras do nome.

15.	[\*] Elabore um programa que recebe um nome e imprime as letras na posição ímpar.

16.	[\*] Elabore um programa que recebe do teclado um nome e o imprime tantas vezes quantos forem seus caracteres.

17.	Elabore um programa que recebe um nome do teclado e imprime-o dez vezes.

18.	[\*] Elabore um programa que que solicite um nome e escreve-o de trás para a frente sem utilizar uma string auxiliar.

19.	Elabore um programa que que solicite um texto e retire todos os espaços em branco desse texto sem utilizar uma string auxiliar.



1. 	Crie uma função que compara duas strings (fazendo o mesmo que a função strcmp).

2. Crie uma função que transforma todos os caracteres de uma string em maiúsculas.

3.	Crie uma função que transforma todos os caracteres de uma string em minúsculas.

4. Crie uma função que recebe uma string e um caractere, e retorne o número de vezes que esse caractere aparece na string.

5.	Crie uma função que recebe uma string e um caractere, e apague todas as ocorrências desse caractere na string (cria uma nova string sem esse caractere).

6.	Crie uma função que recebe uma string e dois caracteres (C1 e C2) e troque todas as ocorrências na string do caractere C1 pelo caractere C2.

7.	Faça um programa que contenha um menu com as chamadas às funções dos exercícios anteriores.

