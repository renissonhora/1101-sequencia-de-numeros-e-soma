# 1101-sequencia-de-numeros-e-soma
CÓDIGO FONTE
CÓDIGO FONTE






123456789101112131415161718192021222324 

#include <stdio.h>
#include <stdlib.h
>int main() {
//leitura de variaveis
int m,n,maior,menor,x,soma=0;
//  laço enquanto ler as variaveis e m for maior que 0 e n maior 0
while(scanf("%d %d", &m,&n)&& m>0 && n>0)
{ if(m>n){         maior=m;         menor=n;         } 
else{              maior=n;              menor=m;              }
for(x=menor; x<=maior; x++)
{                           printf("%d ",x);                           soma = soma+x;                           }  
printf("Sum=%d\n",soma);                           soma=0; } 
return 0;
} 
