Judul Program : Sistem Pelayanan Antrean Restoran

Deskripsi : Program ini bertujuan untuk nenbantu pelayanan restoran dalam sistem antrean. Program ini merupakan implementasi dari QueueArray yang dimana Queue mengikuti prinsip FIFO (First In, First Out). Hal ini berarti data yang pertama kali masuk ke dalam Queue akan menjadi data yang pertama kali diproses, mendahului elemen-elemen lain yang datang setelahnya.

Source Code :
<img width="2186" height="4168" alt="Tugas Akhir PSD 4 (1)" src="https://github.com/user-attachments/assets/b33567ef-7d69-4ac3-b5bf-e8768ba39391" />

Penjelasan : 

Baris 1 : Membuat kelas bernama QueueArray

Baris 2 : ukuran maksimum queue adalah 100 jika tidak diisi nilai lain

Baris 3 : Menyimpan ukuran maksimum queue ke variabel MAXN

Baris 4 : membuat array dengan ukuran MAXN dengan semua isi awal bernilai None

Baris 5 : Menyimpan indeks depan queue, -1 menandakan queue masih kosong

Baris 6 : Menyimpan indeks belakang queue, -1 berarti belum ada data

Baris 8 : Method untuk mengecek apakah queue kosong

Baris 9 : Mengembalikan nilai True jika queue kosong dan front_idx bernilai -1

Baris 11 : Method untuk mengecek apakah queue penuh

Baris 12 : Mengecek apakah posisi belakang berikutnya sama dengan posisi depan

Baris 14 : Method untuk menghitung jumlah elemen dalam queue

Baris 15 : Mengecek apakah queue kosong

Baris 16 : jika kosong, jumlah elemen = 0

Baris 17 : Mengecek apakah indeks belakang berada setelah indeks depan

Baris 18 : Menghitung jumlah elemen secara normal

Baris 19 : Digunakan jika queue melingkar dan menghitung jumlah elemen pada circular queue

Baris 21 : Method untuk menambahkan data ke queue

Baris 22 : Mengecek apakah queue penuh

Baris 23 : menampilkan pesan "Queue penuh"

Baris 24 : Menghentikan proses enqueue

Baris 25 : Menyimpan jumlah orang sebelum pelanggan baru masuk

Baris 26 : Mengecek apakah queue kosong

Baris 27 : Jika kosong, indeks depan menjadi 0

Baris 28 : Indeks belakang juga menjadi 0

Baris 29 : Jika queue tidak kosong

Baris 30 : Menggeser indeks belakang ke posisi berikutnya

Baris 31 : Menyimpan data x ke posisi belakang queue

Baris 32 : estimasi waktu tunggu setiap orang diasumsikan membutuhkan 2 menit

Baris 33 : Menampilkan pesan "Pelanggan ke- memasuki antrean. "

Baris 34 : menampilkan pesan "Estimasi anda menunggu menit. karena masih terdapat orang di depan Anda."

Baris 36 : Method untuk menghapus data paling depan dari queue

Baris 37 : Mengecek apakah queue kosong

Baris 38 : menampilkan pesan "Queue kosong"

Baris 39 : Menghentikan proses dequeue

Baris 40 : Menyimpan nilai paling depan queue

Baris 41 : Mengecek apakah queue hanya memiliki satu elemen

Baris 42 : Mengosongkan queue dengan mengubah front menjadi -1

Baris 43 : Mengubah rear menjadi -1

Baris 44 : Jika queue masih memiliki lebih dari satu elemen

Baris 45 : Memindahkan indeks depan ke elemen berikutnya

Baris 46 : menampilkan pesan "Nomor antrean silakan menuju kasir pembayaran."

Baris 48 : Method untuk melihat elemen paling depan tanpa menghapusnya

Baris 49 : Mengecek apakah queue kosong

Baris 50 : menampilkan pesan "Queue kosong"

Baris 51 : Menghentikan proses

Baris 52 : Menampilkan pesan "Elemen depan: "

Baris 54 : Method untuk menampilkan seluruh isi queue

Baris 55 : Mengecek apakah queue kosong

Baris 56 : Menampilkan pesan "Queue kosong"

Baris 57 : Menghentikan proses

Baris 58 : Menampilkan pesan "Isi queue (depan ke belakang): "

Baris 59 : Variabel i dari depan

Baris 60 : Perulangan tanpa batas

Baris 61 : Menampilkan elemen queue

Baris 62 : Mengecek apakah sudah mencapai belakang queue

Baris 63 : Menghentikan perulangan

Baris 64 : Pindah ke indeks berikutnya

Baris 65 : Pindah ke baris baru

Baris 68 : Fungsi utama program

Baris 69 : Membuat queue dari kelas QueueArray

Baris 70 : Variabel untuk menyimpan pilihan menu

Baris 71 : Perulangan berjalan sampai user memilih 5

Baris 72 : Menampilkan judul program

Baris 73 : Menampilkan menu menambah nomor antrean

Baris 74 : Menampilkan menu menghapus nomor antrean

Baris 75 : Menampilkan menu melihat antrean bagian depan

Baris 76 : Menampilkan menu melihat seluruh queue

Baris 77 : Menampilkan menu keluar

Baris 78 : digunakan untuk menangani error input

Baris 79 : memilih salah satu input pilihan menu

Baris 80 : Menangkap error jika input bukan angka

Baris 81 : menampilkan pesan "Input tidak valid!"

Baris 82 : Kembali ke awal perulangan

Baris 83 : Jika memilih menu enqueue

Baris 84 : Menangani error input nomor antrean

Baris 85 : menginput nomor antrean

Baris 86 : Menambahkan nomor antrean ke queue

Baris 87 : Jika input bukan angka

Baris 88 : menampilkan pesan "Input tidak valid!"

Baris 89 : Jika memilih dequeue

Baris 90 : Memanggil method dequeue

Baris 91 : Jika memilih peek

Baris 92 : Memanggil method peek

Baris 93 : Jika memilih display

Baris 94 : Menampilkan seluruh queue

Baris 95 : Jika memilih keluar

Baris 96 : menampilkan pesan "Program selesai. Terima kasih."

Baris 97 : Jika pilihan menu tidak tersedia

Baris 98 : Menampilkan pesan "Pilihan tidak valid!"

Baris 101 : Mengecek apakah file dijalankan langsung

Baris 102 : Memanggil fungsi utama program

Output :
<img width="349" height="470" alt="TA PSD (1)" src="https://github.com/user-attachments/assets/7d7d5140-54ca-4a35-940f-623f146f6de1" />

Penjelasan : User memilih salah satu 5 menu. Menu 1 umtuk memasuki nomor antrean, Menu 2 untuk melayani nomor terdepan, Menu 3 untuk melihat nomor antrean paling depan, Menu 4 untuk melihat semua nomor antrean, Menu 5 untuk Keluar.

Link Dokumentasi : https://youtu.be/Mzei76DWb2M

