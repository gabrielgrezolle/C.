# C.
Algoritimo basic

#include <stdlib.h>
#include <stdio.h>
    int main () {
    float nota1 , nota2 , nota3 , media;
    
   
    printf ("digite a sua primeira nota : ");
    scanf ("%f", &nota1); 
    printf ("agora digite a sua segunda nota : ");
    scanf ("%f", &nota2);
    printf ("por fim, digite a sua última nota : ");
    scanf ("%f", &nota3); 
    media = (nota1+nota2+nota3)/3; 
 
       printf ("a sua média é %f .",media);
    
       return 0;
    }
