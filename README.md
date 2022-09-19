# CrackMe

#include <conio.h>
#include <stdio.h>
#include <stdlib.h>

int main() {
    int pin=0;
    printf("Vvedite PIN: ");
    scanf("%d", &pin);
    if (pin == 8754) {
        printf("PIN VEREN");
    } else {
        printf("PIN NE VEREN");
    };
    _getch();
    return 0;
}
