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

#include <stdio.h>

int main() {
    float distancia_pingüino = 120.0; // Distancia recorrida por el pingüino en km
    int horas;
    float distancia_total;

    printf("Introduce el número de horas: ");
    scanf("%d", &horas);

    // Calculamos la distancia total
    distancia_total = distancia_pingüino * horas;

    printf("El pingüino nadará %.2f km en %d horas.\n", distancia_total, horas);

    return 0;
}

#include <stdio.h>

int main() {
    float distancia_antilope = 22.5; // Distancia recorrida por el antílope en km
    int horas;
    float distancia_total;

    printf("Introduce el número de horas: ");
    scanf("%d", &horas);

    // Calculamos la distancia total
    distancia_total = distancia_antilope * horas;

    printf("El antílope habrá recorrido %.2f km en %d horas.\n", distancia_total, horas);

    return 0;
}

#include <stdio.h>

int main() {
    int num_pasteles;
    float harina_por_pastel = 3.0; // Cantidad de harina por pastel en kg
    float cantidad_harina;

    printf("Introduce el número de pasteles a realizar: ");
    scanf("%d", &num_pasteles);

    // Calculamos la cantidad de harina necesaria
    cantidad_harina = (harina_por_pastel * num_pasteles) / 100.0;

    printf("La cantidad de harina a utilizar es: %.2f kg.\n", cantidad_harina);

    return 0;
}

#include <stdio.h>

int main() {
    int num_panes;
    float costo_por_pan = 8.0; // Costo de un pan en bs
    float costo_total;

    printf("Introduce el número de panes solicitados por el cliente: ");
    scanf("%d", &num_panes);

    // Calculamos el costo total de la venta
    costo_total = num_panes * costo_por_pan;

    printf("El costo total de la venta es: %.2f bs.\n", costo_total);

    return 0;
}
