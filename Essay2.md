# Program C: Menghitung Luas Permukaan Tabung

## Deskripsi
Program ini digunakan untuk menghitung **luas permukaan tabung** yang terdiri dari:
- **Luas alas** (lingkaran bawah)
- **Luas atap** (lingkaran atas)
- **Luas selimut**
- **Luas total permukaan**

Rumus yang digunakan:
- Luas alas = π × r²  
- Luas atap = π × r²  
- Luas selimut = 2 × π × r × t  
- Luas total = luas alas + luas atap + luas selimut  

dengan:
- `r` = jari-jari tabung
- `t` = tinggi tabung

## Source Code
```c
#include <stdio.h>
#include <stdlib.h>

#define PHI 3.14

int main() {
    float r, t;
    float luasAlas, luasAtap, luasSelimut, luasTotal;

    // Input nilai jari-jari dan tinggi tabung
    printf("Masukkan jari-jari tabung (r): ");
    scanf("%f", &r);
    printf("Masukkan tinggi tabung (t): ");
    scanf("%f", &t);

    // Hitung luas alas (lingkaran bawah)
    luasAlas = PHI * r * r;

    // Hitung luas atap (lingkaran atas)
    luasAtap = PHI * r * r;

    // Hitung luas selimut tabung
    luasSelimut = 2 * PHI * r * t;

    // Hitung luas total permukaan tabung
    luasTotal = luasAlas + luasAtap + luasSelimut;

    // Tampilkan hasil
    printf("\nLuas alas tabung: %.2f\n", luasAlas);
    printf("Luas atap tabung: %.2f\n", luasAtap);
    printf("Luas selimut tabung: %.2f\n", luasSelimut);
    printf("Luas total kulit tabung: %.2f\n", luasTotal);

    return 0;
}
```

## Contoh Input & Output
```
Masukkan jari-jari tabung (r): 7
Masukkan tinggi tabung (t): 10

Luas alas tabung: 153.86
Luas atap tabung: 153.86
Luas selimut tabung: 439.60
Luas total kulit tabung: 747.32
```
