Segundo Ejercicios de Paradigmas de programación 

1 Calculé la mitad de un número más su quinta parte 

#include <stdio.h>

int main() {
    float numero, mitad, quintaParte, resultado;

    printf("Introduce un número: ");
    scanf("%f", &numero);

    mitad = numero / 2;
    quintaParte = numero / 5;
    resultado = mitad + quintaParte;

    printf("La mitad del número más su quinta parte es: %.2f\n", resultado);

    return 0;
}


2 calcular el cuadrado de un número disminuido en 25


#include <stdio.h>
#include <math.h>

int main() {
    float numero, cuadrado;

    printf("Introduce un número: ");
    scanf("%f", &numero);

    cuadrado = pow(numero - 25, 2);

    printf("El cuadrado del número disminuido en 25 es: %.2f\n", cuadrado);

    return 0;
}

3 Calcular el cuadrado de x más el cuadrado de y más el cubo de z 

#include <stdio.h>
#include <math.h>

int main() {
    float x, y, z, resultado;

    printf("Introduce el valor de x: ");
    scanf("%f", &x);
    printf("Introduce el valor de y: ");
    scanf("%f", &y);
    printf("Introduce el valor de z: ");
    scanf("%f", &z);

    resultado = pow(x, 2) + pow(y, 2) + pow(z, 3);

    printf("El resultado es: %.2f\n", resultado);

    return 0;
}

4 Calcular el cuadrado de la suma de dos números 

#include <stdio.h>
#include <math.h>

int main() {
    float num1, num2, suma, resultado;

    printf("Introduce el primer número: ");
    scanf("%f", &num1);
    printf("Introduce el segundo número: ");
    scanf("%f", &num2);

    suma = num1 + num2;
    resultado = pow(suma, 2);

    printf("El cuadrado de la suma de los dos números es: %.2f\n", resultado);

    return 0;
}


5 Calcular el cuadrado de la diferencia de dos números 

#include <stdio.h>
#include <math.h>

int main() {
    float num1, num2, resta, resultado;

    printf("Introduce el primer número: ");
    scanf("%f", &num1);
    printf("Introduce el segundo número: ");
    scanf("%f", &num2);

    resta = num1 - num2;
    resultado = pow(resta, 2);

    printf("El cuadrado de la diferencia de los dos números es: %.2f\n", resultado);

    return 0;
}
