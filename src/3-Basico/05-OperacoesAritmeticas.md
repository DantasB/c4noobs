# Operadores Aritmeticos
Os operadores matemáticos são de importância fundamental para qualquer tipo de linguagem de programação. Eles são os operadores de adição, subtração, multiplicação, divisão, mod (resto da divisão), incremento e decremento.


## Operador de Adição
Como o nome já diz, é um operador que realiza uma soma, ele pode ser atribuido dentro de variáveis ou realizando soma de duas variáveis, no exemplo abaixo fará mais sentido.

```c
#include <stdio.h> 

int main(void) {

    int soma = 5 + 2; //variável inteira de nome "soma" recebe o valor da soma entre 5 e 2;

    printf("O valor da soma 5 + 2 = %d\n", soma);

    //Também pode ser declarado como:
    int num1 = 5; //variavel inteira de nome "num1" recebe o valor de 5.

    int num2 = 2; //variavel inteira de nome "num2" recebe o valor de 2.

    int soma2 = num1 + num2; //variavel de nome "soma2" recebe o valor da soma entre as variaveis de nome "num1" e "num2"

    printf("O valor da soma %d + %d = %d\n", num1, num2, soma2);

}
```


## Operador de subtração

Como o nome já diz, é um operador que realiza uma subtração, ele pode ser atribuido dentro de variáveis ou realizando subtrações de duas variáveis, no exemplo abaixo fará mais sentido.

```c
#include <stdio.h> 

int main(void) {

    int subtracao = 10 - 4; //variável inteira de nome "subtracao" recebe o valor da subtracao entre 10 e 4;

    printf("O valor da subtração 10 - 4 = %d\n", subtracao);

    //Também pode ser declarado como:
    int num1 = 10; //variavel inteira de nome "num1" recebe o valor de 10.

    int num2 = 4; //variavel inteira de nome "num2" recebe o valor de 4.

    int subtracao2 = num1 - num2; //variavel de nome "subtracao2" recebe o valor da subtração entre as variaveis de nome "num1" e "num2"

    printf("O valor da subtracao %d - %d = %d\n", num1, num2, subtracao2);

}
```

## Operador de multiplicação

Como o nome já diz, é um operador que realiza uma multiplicação, ele pode ser atribuido dentro de variáveis ou realizando subtrações de duas variáveis, no exemplo abaixo fará mais sentido.

```c
#include <stdio.h>

int main(void) {

    int multiplicacao = 10 * 5; //variável inteira de nome "multiplicacao" recebe o valor da multiplicação entre 10 e 5;

    printf("O valor da multiplicacao 10 * 5 = %d\n", multiplicacao);

    //Também pode ser declarado como:
    int num1 = 10; //variavel inteira de nome "num1" recebe o valor de 10.

    int num2 = 5; //variavel inteira de nome "num2" recebe o valor de 5.

    int multiplicacao2 = num1 * num2; //variavel de nome "multiplicacao2" recebe o valor da multiplicacao entre as variaveis de nome "num1" e "num2"

    printf("O valor da multiplicacao %d * %d = %d\n", num1, num2, multiplicacao2);
        
}
```

## Operador de divisão

Como o nome já diz, é um operador que realiza uma divisão, ele pode ser atribuido dentro de variáveis ou realizando subtrações de duas variáveis, no exemplo abaixo fará mais sentido.

```c
#include <stdio.h>

int main(void) {

    int divisao = 10 / 5; //variável inteira de nome "divisao" recebe o valor da divisão entre 10 e 5;

    printf("O valor da divisão 10 / 5 = %d\n", divisao);

    //Também pode ser declarado como:
    int num1 = 10; //variavel inteira de nome "num1" recebe o valor de 10.

    int num2 = 5; //variavel inteira de nome "num2" recebe o valor de 5.

    int divisao2 = num1 / num2; //variavel de nome "divisao2" recebe o valor da divisao entre as variaveis de nome "num1" e "num2"

    printf("O valor da divisao %d / %d = %d\n", num1, num2, divisao2);

}
```

## Operador de Mod

Esse operador retorna o resto de uma divisão. O exemplo abaixo fica mais simples de entender.

```c
#include <stdio.h>

int main(void) {

    int mod = 10 % 5; //variável inteira de nome "mod" recebe o valor do resto da divisão entre 10 e 5;

    printf("O resto da divisão 10 / 5 = %d\n", mod);

    //Também pode ser declarado como:
    int num1 = 10; //variavel inteira de nome "num1" recebe o valor de 10.

    int num2 = 5; //variavel inteira de nome "num2" recebe o valor de 5.

    int mod2 = num1 % num2; //variavel de nome "mod2" recebe o valor do resto da divisão entre as variaveis de nome "num1" e "num2"

    printf("O resto da divisão %d %% %d = %d\n", num1, num2, mod2);

}
```

**Obs**: Operações entre parênteses serão resolvidas primeiro, e depois de multiplicação, divisão e módulo.
[Mais detalhes sobre ordem de precedência](https://en.cppreference.com/w/c/language/operator_precedence)

## Operações resumidas 

Se uma variável for subtrair uma variável com 1, pode-se fazer das seguintes maneiras:

```c
int x = 10;
printf("%d\n", x);

x = x - 1; //funciona com qualquer valor, nao somente 1
printf("%d\n", x);

x -= 1; //funciona com qualquer valor nao somente 1
printf("%d\n", x);

x--; //subtrai somente 1 da variavel.
printf("%d\n", x);
```
<hr>
Se uma variável for somar uma variável com 1, pode-se fazer das seguintes maneiras:

```c
int x = 10;
printf("%d\n", x);

x = x + 1; //funciona com qualquer valor, nao somente 1
printf("%d\n", x);

x += 1; //funciona com qualquer valor nao somente 1
printf("%d\n", x);

x++; //soma somente 1 da variavel.
printf("%d\n", x);
```