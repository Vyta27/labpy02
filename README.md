# labpy02
# Latihan 1 : Membuat proggram menentukan nilai akhir
![Screenshot 2024-10-31 101631](https://github.com/user-attachments/assets/8cc498bd-2c28-4fcd-96ff-90c707b19494)

- input data :
  - meminta pengguna untuk memasukan nilai UTS (Ujian Tengah Semester), nilai UAS (Ujian Akhir Semester), dan nilai tugas
- Perhitungan nilai akhir :
  - nilai akhir di hitung berdasarkan bobot nilai tugas sebesar 20%, UTS 40%, dan UAS 40%
  - Fungsi int() digunakan untuk mengkonversi input string menjadi integer
- Penentuan keterangan nilai lulus atau tidak
  - Keterangan lulus diberikan berdasarkan nilai akhir. Jika nilai akhir lebih dari 60, maka keterangan akan menjadi "LULUS", jika tidak akan menjadi "TIDAK LULUS".
- Penentuan nilai huruf
  - A jika lebih dari 80 B jika lebih dari 70 C jika lebih dari 50 D jika lebih dari 40 E jika di bawah atau sama dengan 40
- Output hasil
  
![Screenshot 2024-10-31 101800](https://github.com/user-attachments/assets/4fa11123-4440-4f91-84eb-7bb3b6976beb)

 - Kode ini menampilkan hasil, termasuk nilai UTS, UAS, tugas, nilai akhir, nilai huruf, dan keterangan lulus atau tidak lulus.

   Hasil Program: Pada contoh output di sisi kanan gambar, jika nilai tugas, UTS, dan UAS adalah 90, 85, dan 80, maka

   Nilai akhir adalah 85. Nilai huruf adalah "A". Keterangan: "LULUS".

# Latihan 2 : Membuat Proggram Menampilkan Status Gaji Karyawan
![Screenshot 2024-10-31 113016](https://github.com/user-attachments/assets/7726f830-ffa3-4b2a-8e36-da533b3aeb01)

- Input data :
  - Kode ini meminta pengguna untuk memasukkan gaji, status keluarga, dan kepemilikan rumah. Variabel gaji menyimpan nilai gaji sebagai integer.
  - Variabel berkeluarga akan bernilai True jika pengguna memasukkan "Y" (sudah berkeluarga) dan False jika "T". Variabel punya rumah akan bernilai True jika pengguna 
    memasukkan "Y" (punya rumah) dan False jika "T".
- Pengecekkan gaji : 
  - Jika gaji lebih dari 3.000.000, maka program akan mencetak "Gaji sudah di atas UMR". Jika tidak, program akan langsung mencetak "Gaji belum UMR" pada bagian else.
- Pengecekkan status keluarga :
  - Jika berkeluarga bernilai True,program akan menampilkan "Wajib ikutan asuransi dan menabung untuk pensiun". Jika berkeluarga bernilai False, program akan menampilkan 
   "Tidak perlu ikutan asuransi".
- Pengecekkan kepemilikan rumah :
  -  Jika punya_rumah bernilai True, program akan menampilkan "Wajib bayar pajak rumah". Jika punya_rumah bernilai False, program akan menampilkan "Tidak wajib bayar pajak 
     rumah".
  - Jika gaji tidak lebih dari 3.000.000, program akan langsung menampilkan "Gaji belum UMR" tanpa melakukan pengecekan tambahan
- Output hasil :
  
![Screenshot 2024-10-31 102008](https://github.com/user-attachments/assets/a49a908f-cd60-43ee-b92d-0c8e8c9fb104)

  - Pada contoh output pada gambar, jika gaji 8.000.000, status berkeluarga "T", dan punya rumah "Y":Program menampilkan bahwa gaji di atas UMR. Menampilkan bahwa pengguna 
    tidak perlu ikut asuransi dan Menampilkan bahwa pengguna wajib membayar pajak rumah.

# Latihan 3 : Penggunaan kondisi OR Program membandingkan 3 input bilangan lainnnya, maka cetak pernyataan "BENAR"
![Screenshot 2024-10-31 102356](https://github.com/user-attachments/assets/2b9c0990-bbcb-472a-a8e0-751ec4877c94)

- Input data :
  - Kode ini meminta pengguna untuk memasukkan tiga bilangan: a, b, dan c. Input dari pengguna dikonversi ke tipe int agar dapat digunakan dalam operasi aritmatika.
- Pengecekan kondisi :
  - Kode ini memeriksa apakah salah satu dari kondisi berikut terpenuhi: a + b == c b + c == a c + a == b Jika salah satu kondisi di atas benar, program akan mencetak 
    "BENAR". Jika tidak ada kondisi yang terpenuhi, program akan mencetak "SALAH".
  - Kode ini mengecek apakah salah satu dari tiga bilangan (a, b, atau c) dapat merupakan hasil penjumlahan dari dua bilangan lainnya. Pada contoh output pada
    gambar: Jika a = 5, b = 5, dan c = 10, maka kondisi terpenuhi, sehingga hasilnya adalah "BENAR".
- Output hasil :
  
![Screenshot 2024-10-31 102416](https://github.com/user-attachments/assets/62ab8930-50b8-4825-a0f1-ec0ae4558751)

# Kasus 1 : Program pemesanan tiket bioskop, Program ini meminta input dari user untuk tipe tiket (reguler atau VIP) dan status member (memiliki kartu member atau tidak).
![Screenshot 2024-10-31 103318](https://github.com/user-attachments/assets/dbd22638-6445-44f9-96d2-412b393faeca)

- Mendefinisikan harga tiket :
  - harga_tiket_reguler: Harga tiket reguler didefinisikan sebesar 50000 harga_tiket_vip: Harga tiket VIP didefinisikan sebesar 100000 diskon_member: Besar diskon untuk 
    member didefinisikan sebesar 0.20 (20%)
- Meminta input dari user :
  - Program meminta user untuk memasukkan tipe tiket (reguler/vip) dan menyimpannya ke dalam variabel tipe_tiket.
  - Program meminta user untuk memasukkan status member (ya/tidak) dan menyimpannya ke dalam variabel status_member.
  - Kedua input dari user diubah menjadi huruf kecil menggunakan fungsi lower().
- Menghitung harga tiket berdasarkan tipe :
  - Jika tipe_tiket adalah "reguler", maka harga_tiket diset menjadi harga_tiket_reguler.
  - Jika tipe_tiket adalah "vip", maka harga_tiket diset menjadi harga_tiket_vip.
  - Jika tipe_tiket bukan "reguler" atau "vip", maka program menampilkan pesan "Tipe tiket tidak valid" dan keluar dari program.
- Mengecek status untuk member diskon :
  - Program memeriksa nilai status_member: Jika status_member adalah "ya", maka total_harga dihitung dengan rumus harga_tiket * (1 - diskon_member), yang memberikan diskon 
    kepada member.
  - Jika status_member bukan "ya", maka total_harga diset sama dengan harga_tiket tanpa diskon.
- Output hasil :
  
![Screenshot 2024-10-31 103400](https://github.com/user-attachments/assets/4651fa6a-6061-45ad-aa75-c67ed23748cd)

# Kasus 2 : program kalkulator sederhana,Kode program ini dirancang untuk melakukan operasi aritmatika sederhana berdasarkan input pengguna. 
![Screenshot 2024-10-31 103854](https://github.com/user-attachments/assets/09fd2ed8-5e63-47ad-bf38-5c52a5da3300)

- Flowchart
  

- Input: Kode program meminta pengguna untuk memasukkan operator aritmatika (+, -, *, /) dan dua angka.
- Validasi Operator: Kode menggunakan struktur if-elif-else untuk memvalidasi operator yang dimasukkan.
- Operasi Aritmatika: Berdasarkan operator yang valid, kode melakukan operasi aritmatika yang sesuai dan menyimpan hasilnya dalam variabel hasil.
- Validasi Pembagian dengan Nol: Kode mengecek apakah angka kedua adalah nol untuk menghindari pembagian dengan nol. Jika angka kedua nol, program akan menampilkan pesan 
  error dan menghentikan eksekusi.
- Output hasil :
  
 - Jika operator valid dan operasi berhasil dilakukan, kode mencetak hasil perhitungan ke layar.
 - Jika operator tidak valid atau terjadi pembagian dengan nol, kode mencetak pesan error. Secara keseluruhan, kode ini mengilustrasikan penggunaan struktur kontrol if- 
   elif-else untuk membuat program sederhana yang dapat melakukan operasi aritmatika dasar.

   



