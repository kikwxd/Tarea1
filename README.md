#include <stdio.h>

int main() {
    float peso, altura, imc;

    //Hola como estan somos el team buena onda alfa dinamita
    printf("Ingrese su peso en kilogramos: ");
    scanf("%f", &peso);

    printf("Ingrese su altura en metros: ");
    scanf("%f", &altura);
    
    imc = peso / (altura * altura);
    if (imc > 30)
    {
         printf ("Momento de ir al gym");
    }
    printf("Su índice de masa corporal (IMC) es: %.2f\n", imc);

    return 0;
}
