#include <stdio.h>

int main() {
    float peso, altura, imc;

    //Hola como estan
    printf("Ingrese su peso en kilogramos: ");
    scanf("%f", &peso);

    printf("Ingrese su altura en metros: ");
    scanf("%f", &altura);
    
    imc = peso / (altura * altura);
    printf("Su índice de masa corporal (IMC) es: %.2f\n", imc);

    return 0;
}
