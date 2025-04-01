//while-em-C

#include <stdio.h>
#include <stdlib.h>
#include  <locale.h>

int main()
{

   setlocale(LC_ALL, "Portuguese");
   int n1,n2;

   printf("Escreva o primeiro numero :");
   scanf("%d",&n1);

   printf("Escreva o segundo numero :");
   scanf("%d",&n2);

   n1++;
   while(n1<n2)
    {

    printf("%d", n1);
    n1++;

    }

}
