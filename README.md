#include <stdio.h>

int main() {
    printf("Таблиця степенів двійки\n");
    
    int value = 1;
    
    for (int i=0; i<=10; i++) {
        printf("%d %d\n", i, value);
        value *= 2;
    }
    return 0;
}
