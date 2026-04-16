# Praktikum 5 – Pemrograman Dasar Nested Loop

## 📌 Deskripsi

Repository ini berisi implementasi program Java berdasarkan praktikum **Nested Loop**.
Program dibuat untuk memahami konsep **perulangan bersarang (nested loop)** dalam menampilkan pola berbasis karakter (`*`).

---

## 🎯 Tujuan

* Memahami konsep dasar nested loop
* Menerapkan logika perulangan dalam pembuatan pola
* Melatih pemecahan masalah berbasis output visual

---

## 🧩 Daftar Program

Repository ini terdiri dari **4 program utama**, yaitu:

### 1. Pola Persegi (Full Bintang)

Menampilkan pola persegi dengan jumlah baris dan kolom sesuai input.

#### Contoh:

```
*****
*****
*****
*****
*****
```

#### Konsep:

* Loop luar → baris
* Loop dalam → kolom

---

### 2. Pola Segitiga Meningkat

Menampilkan pola bintang dari kecil ke besar.

#### Contoh:

```
*
**
***
****
*****
```

#### Konsep:

* Jumlah bintang bertambah setiap baris

---

### 3. Pola Segitiga Menurun

Menampilkan pola bintang dari besar ke kecil.

#### Contoh:

```
*****
****
***
**
*
```

#### Konsep:

* Jumlah bintang berkurang setiap baris

---

### 4. Pola Segitiga Rata Kanan

Menampilkan pola segitiga dengan posisi rata kanan.

#### Contoh:

```
    *
   **
  ***
 ****
*****
```

#### Konsep:

* Kombinasi spasi dan bintang
* Nested loop untuk mengatur posisi

---

## 💻 Contoh Implementasi (Program 1)

Berikut salah satu implementasi kode:

```java
import java.util.Scanner;

public class nestedLoop1 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("Masukkan jumlah bintang yang ingin ditampilkan: ");
        int inputan = sc.nextInt();

        for (int i = 1; i <= inputan; i++) {
            for (int j = 1; j <= inputan; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

---

## ⚙️ Cara Menjalankan Program

1. Compile file Java:

```
javac namaFile.java
```

2. Jalankan program:

```
java namaFile
```

3. Masukkan angka sesuai kebutuhan (misal: 5)

---

## 📚 Konsep yang Digunakan

* Perulangan `for`
* Nested Loop
* Input menggunakan `Scanner`
* Output formatting (`print` dan `println`)

---

## 🧠 Kesimpulan

Nested loop merupakan konsep penting dalam pemrograman untuk menghasilkan pola tertentu.
Dengan memahami struktur perulangan bersarang, programmer dapat membuat berbagai bentuk output yang kompleks secara efisien.

---

## 🛠️ Teknologi

* Bahasa: Java
* Tools: Terminal / Command Prompt / IDE

---
