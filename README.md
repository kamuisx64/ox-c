#include <stdio.h>
#include <stdlib.h>

void main(int argc, char *argv[])
{
    int n;

    if (argc == 1)
    {
        printf("Você precisa digitar um número inteiro.\n");
        printf("Made by Davi Sales");
        exit(0);
    }

    n = atoi(argv[1]);

    if (n % 2 == 0)
    {
        printf("Você digitou %d, que é par, então a letra é O\n", n);
    }
    else
    {
        printf("Você digitou %d, que é ímpar, então a letra é X\n", n);
    }

    printf("Made by Davi Sales");
    return;
}
