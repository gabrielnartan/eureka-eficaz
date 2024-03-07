#include <stdio.h>

int main()
{
    int dia;
    printf("%s", "digite um dia da semana: ");
    scanf("%d",&dia);
    
    switch (dia)
    {
    case 1:
            printf("%s","\nsegunda-feira");
            break;
    case 2:
            printf("%s","\nterca-feira");
            break;
    case 3:
            printf("%s","\nquarta-feira");
            break;
    case 4:
            printf("%s","\nquinta-feira");
            break;
    case 5:
            printf("%s","sexta-feira");
            break;
    case 6:
            printf("%s","sabado");
            break;
    case 7:
            printf("%s","domingo");
            break;
    case 8:
            printf("%s","escolhe um numero de 1 a 7 Animal!!");
            break;
    case 0:
            printf("%s","escolhe um numero de 1 a 7 Animal!!");
            break;
    }
    
}
