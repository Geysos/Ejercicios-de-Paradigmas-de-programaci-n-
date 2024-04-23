#include <stdio.h>

int main() {
    float velocidad_atun = 24.0; // Velocidad del atún en km/h
    float distancia;
    int horas;

    printf("Introduce el número de horas: ");
    scanf("%d", &horas);

    // Calculamos la distancia recorrida
    distancia = velocidad_atun * horas;

    printf("El atún nadará %.2f km en %d horas.\n", distancia, horas);

    return 0;
}
