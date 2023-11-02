# Tugas Besar Aljabar Linear dan Geometri (IF2123-01)
> Tugas membuat kalkulator matriks yang bisa bekerja sesuai dengan spesifikasi yang diberikan

Repository tugas besar Aljabar Linear dan Geometri kelompok "Aldy DPP" yang terdiri dari anggota:
- Renaldy Arief Susanto 13522022
- Abdul Rafi Radityo Hutomo 13522089

## Tentang AldyDPP Matrix Calculator
Program ini dibuat dalam rangka memenuhi ketentuan tugas besar 1 mata kuliah Aljabar Linear dan Geometri IF2123-01 ITB 2023/2024. Program berupa kalkulator matriks yang dapat digunakan untuk menyelesaikan beberapa persoalan seperti sistem persamaan linier dan interpolasi polinom. Untuk selengkapnya, Anda dapat membaca laporan yang terdapat pada folder "doc". Program berbasis GUI menggunakan Java Swing dan dicompile dalam bentuk executable JAR.

## Cara Menjalankan Program
Berikut langkah-langkah menjalankan program di komputer Anda:
1. Buka folder "src" pada repository ini. Kemudian buka folder "Runnable Program".
2. Unduh file "AldyDPP Matrix Calculator.jar". Ini adalah aplikasi utamanya.
3. SANGAT PENTING: unduh "images.zip" dan ***extract di folder yang sama dengan aplikasi***. Berikut contoh gambar setup yang sudah benar.

![Alt text](image.png)

Atau jika Anda meletakkan file di desktop:

![Alt text](image-1.png)

4. Jalankan aplikasi AldyDPP Matrix Calculator.
5. Langkah 1-3 di atas adalah first time setup. Untuk kedepannya, Anda hanya perlu membuka aplikasi dengan mengklik executable file "AldyDPP Matrix Calculator.jar".
6. Pada program, Anda dapat memasukkan input file .txt. Anda harus memasukkan file .txt dengan cara meng-input directory penuh dari file. Contoh: "C:\Users\Aldy\Desktop\example.txt".
7. Pada program, Anda juga dapat menulis output program ke dalam sebuah file .txt. Beda dengan input, Anda **Hanya Perlu Memasukkan Nama File Saja.** Contoh : "example.txt". File .txt ini akan otomatis masuk ke dalam folder "res" yang seharusnya akan dibuat secara otomatis pada folder yang sama.


## Beberapa Hal Penting Tentang Program
1. Fungsi main dari program terdapat pada src/tubes/gui/GUI.java
2. Program terdiri dari tombol-tombol menu yang berupa segi-empat putih. Silakan navigasi program menggunakan tombol-tombol ini.
3. Anda dapat melakukan kalkulasi berkali-kali. Dalam kata lain, Anda **tidak** harus menutup dan membuka kembali program jika ingin melakukan sebuah kalkulasi lagi.
4. Tampilan program mungkin akan bertabrakan/berantakan apabila Anda memasukkan angka yang sangat besar atau menggunakan jumlah variabel yang **absurd**, tetapi pada umumnya tampilan program seharusnya masih memadai untuk jumlah variabel kurang dari 15.
5. Secara umum, Anda akan terlempar ke halaman error jika input Anda salah, yaitu diantaranya menginput karakter nonangka, menginput file path yang tidak ada, atau pun file txt tidak berukuran yang sesuai. Pastikan input Anda benar.
6. Angka 0 tidak akan muncul pada output fungsi sistem persamaan linier, interpolasi polinomial, mau pun regresi linier. Jika terdapat angka "0.000", artinya nilai sebenarnya lebih kecil dari 0.01, tetapi lebih besar dari 0.