# Exercicio8

#include <stdio.h>
#include <stdlib.h>
#include <math.h>

int main()
{
    system("color 0b");
    int i, n[15];

    for (i=0; i<=14; i++)
    {
        printf("Digite um numero: ");
        scanf("%d", &n[i]);
    }

    for (i=0; i<=14; i++)
    {

        printf("A raiz quadrada de %d e: %.2f\n",n[i],sqrt(n[i]));
    }

    return 0;
}
