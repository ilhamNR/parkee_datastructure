# Implementasi Single Linked List di Java

Implementasi dari single linked list menggunakan Java tanpa menggunakan library List bawaan. Kode ini mencakup kelas `Node` dan `SingleLinkedList` untuk mengelola operasi dasar pada linked list.

Dibuat Menggunakan Apache Netbeans 22 (JDK-22) dan Gradle

## Struktur Proyek

- **Node.java**: Definisi kelas `Node` yang merepresentasikan setiap node dalam linked list.
- **SingleLinkedList.java**: Definisi kelas `SingleLinkedList` yang mengelola operasi-operasi pada linked list.
- **Main.java**: Contoh penggunaan dari linked list dengan interaksi pengguna melalui konsol.

## Operasi yang Tersedia

1. **Insert at End**: Menambahkan node baru dengan nilai data di akhir linked list.
2. **Insert at Beginning**: Menambahkan node baru dengan nilai data di awal linked list.
3. **Delete by Value**: Menghapus node pertama yang ditemukan dengan nilai data dari linked list.
4. **Display**: Menampilkan seluruh elemen dalam linked list dari kepala hingga akhir.

## Cara Menggunakan

1. Pastikan Anda memiliki Java Development Kit (JDK) terinstal.
2. Jalankan `Main.java` untuk menguji implementasi linked list.
3. Pilih opsi yang tersedia dari menu untuk melakukan operasi yang diinginkan pada linked list.

### Contoh Penggunaan

```bash
$ javac App.java       # Compile program
$ java Main             # Jalankan program

Menu:
1. Masukkan di akhir
2. Masukkan di awal
3. Hapus berdasarkan nilai
4. Tampilkan list
5. Keluar
Masukkan pilihan Anda: 1
Masukkan data untuk dimasukkan di akhir: 10

Linked List: 10

Menu:
1. Masukkan di akhir
2. Masukkan di awal
3. Hapus berdasarkan nilai
4. Tampilkan list
5. Keluar
Masukkan pilihan Anda: 2
Masukkan data untuk dimasukkan di awal: 5

Linked List: 5 10

Menu:
1. Masukkan di akhir
2. Masukkan di awal
3. Hapus berdasarkan nilai
4. Tampilkan list
5. Keluar
Masukkan pilihan Anda: 3
Masukkan data untuk dihapus: 5

Linked List: 10

Menu:
1. Masukkan di akhir
2. Masukkan di awal
3. Hapus berdasarkan nilai
4. Tampilkan list
5. Keluar
Masukkan pilihan Anda: 4

Linked List: 10

Menu:
1. Masukkan di akhir
2. Masukkan di awal
3. Hapus berdasarkan nilai
4. Tampilkan list
5. Keluar
Masukkan pilihan Anda: 5
Keluar...
