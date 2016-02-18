# Tugas-2

#include<stdio.h>

int main(){
    int input, in1, in2, x;
    float y, in3, in4;

    printf("\t\tCalculator Sederhana\n");
    printf("\t\t======================\n");
    printf("Selamat datang di Calculator Sederhana Ini... ^_^\n\n\n");
    printf("Silahkan Memilih Jenis perhitungan yang anda inginkan\n");
    printf("1. Perkalian\n");
    printf("2. Penjumlahan\n");
    printf("3. Pengurangan\n");
    printf("4. Pembagian\n");
    printf("Pilihan anda adalah[1-4] : ");
    scanf("%d", &input);
    if(input == 1){
        printf("\n\t\tPerkalian\n");
        printf("\t=======================\n");
        printf("Masukkan angka pertama : ");
        scanf("%d", &in1);
        printf("Masukkan angka kedua : ");
        scanf("%d", &in2);
        x = in1*in2;
        printf("Angka yang anda masukkan adalah %d dan %d\n", in1, in2);
        printf("Maka hasil Perkalian dari %d x %d adalah %d", in1, in2, x);
    }
    else if(input == 2){
        printf("\n\t\tPenjumlahan\n");
        printf("\t=======================\n");
        printf("Masukkan angka pertama : ");
        scanf("%d", &in1);
        printf("Masukkan angka kedua : ");
        scanf("%d", &in2);
        x = in1+in2;
        printf("Angka yang anda masukkan adalah %d dan %d\n", in1, in2);
        printf("Maka hasil Penjumlahan dari %d + %d adalah %d", in1, in2, x);
    }
    else if(input == 3){
        printf("\n\t\tPengurangan\n");
        printf("\t=======================\n");
        printf("Masukkan angka pertama : ");
        scanf("%d", &in1);
        printf("Masukkan angka kedua : ");
        scanf("%d", &in2);
        x = in1-in2;
        printf("Angka yang anda masukkan adalah %d dan %d\n", in1, in2);
        printf("Maka hasil Pengurangan dari %d - %d adalah %d", in1, in2, x);
    }
    else if(input == 4){
        printf("\n\t\tPembagian\n");
        printf("\t=======================\n");
        printf("Masukkan angka pertama : ");
        scanf("%f", &in3);
        printf("Masukkan angka kedua : ");
        scanf("%f", &in4);
        y = in3 / in4;
        printf("Angka yang anda masukkan adalah %.2f dan %.2f\n", in3, in4);
        printf("Maka hasil Pembagian dari %.2f / %.2f adalah %.3f", in3, in4, y);
    }
    else
        printf("\nInput yang anda masukkan telah melebihi pilihan yang tersedia");
    printf("\n\nTerima Kasih telah menggunakan Calculator Sederhana ini");
    printf("\nSampai Jumpa Lagi");
    getch();
    return 0;
}
