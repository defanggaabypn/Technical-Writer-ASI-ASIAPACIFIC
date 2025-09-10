
# Dokumen Bisnis: Proses Perhitungan Deret Fibonacci

## Tujuan:  
Menghitung dan menampilkan deret Fibonacci berdasarkan jumlah elemen yang diminta oleh pengguna.

## Deskripsi Proses:  
1. **Input Pengguna**:  
   - Pengguna diminta untuk memasukkan jumlah elemen deret Fibonacci yang ingin dihitung.
   - Sistem menerima input ini sebagai nilai integer 'n', yang mewakili jumlah elemen dalam deret Fibonacci.

2. **Perhitungan Deret Fibonacci**:
   - Sistem akan menghitung elemen deret Fibonacci menggunakan rumus rekursif:
     - Jika 'n' kurang dari atau sama dengan 1, maka nilai deret Fibonacci adalah 'n'.
     - Jika lebih besar, maka nilai deret Fibonacci dihitung dengan menjumlahkan dua elemen sebelumnya (fibonacci(n-1) + fibonacci(n-2)).

3. **Output**:  
   - Sistem akan menampilkan deret Fibonacci sesuai dengan jumlah elemen yang diminta (hingga 'n').

## Langkah-langkah Pseudocode:

```
Program Fibonacci:
1. Mulai
2. Deklarasikan variabel 'n' sebagai integer.
3. Tampilkan pesan: "Masukkan jumlah deret Fibonacci:"
4. Terima input jumlah deret Fibonacci dari pengguna, simpan di 'n'.
5. Tampilkan pesan: "Deret Fibonacci hingga n adalah:"
6. Untuk setiap nilai 'i' dari 0 sampai n-1 lakukan langkah 7.
7. Tampilkan nilai Fibonacci untuk 'i'.
8. Selesai
```

## Flowchart:
1. Dimulai dengan menerima input jumlah deret Fibonacci.
2. Lakukan perhitungan berdasarkan rumus Fibonacci secara rekursif.
3. Tampilkan hasil deret Fibonacci yang dihitung.

## Tujuan Penggunaan:
- Menyediakan cara otomatis untuk menghitung deret Fibonacci dalam berbagai aplikasi pemrograman.
- Memudahkan pengguna dalam memperoleh informasi yang akurat mengenai deret Fibonacci.
