# labpy02
# Latihan 1 : Membuat proggram menentukan nilai akhir
![Screenshot 2024-10-31 101631](https://github.com/user-attachments/assets/8cc498bd-2c28-4fcd-96ff-90c707b19494)

# input data :
 - meminta pengguna untuk memasukan nilai UTS (Ujian Tengah Semester), nilai UAS (Ujian Akhir Semester), dan nilai tugas  
# Perhitungan nilai akhir :
 - nilai akhir di hitung berdasarkan bobot nilai tugas sebesar 20%, UTS 40%, dan UAS 40%
 - Fungsi int() digunakan untuk mengkonversi input string menjadi integer
# Penentuan keterangan nilai lulus atau tidak
 - Keterangan lulus diberikan berdasarkan nilai akhir. Jika nilai akhir lebih dari 60, maka keterangan akan menjadi "LULUS", jika tidak akan menjadi "TIDAK LULUS".
# Penentuan nilai huruf
 - A jika lebih dari 80 B jika lebih dari 70 C jika lebih dari 50 D jika lebih dari 40 E jika di bawah atau sama dengan 40
# Output hasil
![Screenshot 2024-10-31 101800](https://github.com/user-attachments/assets/4fa11123-4440-4f91-84eb-7bb3b6976beb)

 - Kode ini menampilkan hasil, termasuk nilai UTS, UAS, tugas, nilai akhir, nilai huruf, dan keterangan lulus atau tidak lulus.

   Hasil Program: Pada contoh output di sisi kanan gambar, jika nilai tugas, UTS, dan UAS adalah 90, 85, dan 80, maka

   Nilai akhir adalah 85. Nilai huruf adalah "A". Keterangan: "LULUS".

# Latihan 2 : Membuat Proggram Menampilkan Status Gaji Karyawan
![Screenshot 2024-10-31 113016](https://github.com/user-attachments/assets/7726f830-ffa3-4b2a-8e36-da533b3aeb01)

# Input data :
  - Kode ini meminta pengguna untuk memasukkan gaji, status keluarga, dan kepemilikan rumah. Variabel gaji menyimpan nilai gaji sebagai integer.
  - Variabel berkeluarga akan bernilai True jika pengguna memasukkan "Y" (sudah berkeluarga) dan False jika "T". Variabel punya rumah akan bernilai True jika pengguna 
    memasukkan "Y" (punya rumah) dan False jika "T".
# Pengecekkan gaji : 
  - Jika gaji lebih dari 3.000.000, maka program akan mencetak "Gaji sudah di atas UMR". Jika tidak, program akan langsung mencetak "Gaji belum UMR" pada bagian else.
# Pengecekkan status keluarga :
  - Jika berkeluarga bernilai True,program akan menampilkan "Wajib ikutan asuransi dan menabung untuk pensiun". Jika berkeluarga bernilai False, program akan menampilkan 
   "Tidak perlu ikutan asuransi".
# Pengecekkan kepemilikan rumah :
  -  Jika punya_rumah bernilai True, program akan menampilkan "Wajib bayar pajak rumah". Jika punya_rumah bernilai False, program akan menampilkan "Tidak wajib bayar pajak 
     rumah".
  - Jika gaji tidak lebih dari 3.000.000, program akan langsung menampilkan "Gaji belum UMR" tanpa melakukan pengecekan tambahan
# Output hasil :
![Screenshot 2024-10-31 102008](https://github.com/user-attachments/assets/a49a908f-cd60-43ee-b92d-0c8e8c9fb104)

  - Pada contoh output pada gambar, jika gaji 8.000.000, status berkeluarga "T", dan punya rumah "Y":Program menampilkan bahwa gaji di atas UMR. Menampilkan bahwa pengguna 
    tidak perlu ikut asuransi dan Menampilkan bahwa pengguna wajib membayar pajak rumah.

# Latihan 3 : Penggunaan kondisi OR Program membandingkan 3 input bilangan lainnnya, maka cetak pernyataan "BENAR"
![Screenshot 2024-10-31 102356](https://github.com/user-attachments/assets/2b9c0990-bbcb-472a-a8e0-751ec4877c94)

# Input data :
  - Kode ini meminta pengguna untuk memasukkan tiga bilangan: a, b, dan c. Input dari pengguna dikonversi ke tipe int agar dapat digunakan dalam operasi aritmatika.
# Pengecekan kondisi :
  - Kode ini memeriksa apakah salah satu dari kondisi berikut terpenuhi: a + b == c b + c == a c + a == b Jika salah satu kondisi di atas benar, program akan mencetak 
    "BENAR". Jika tidak ada kondisi yang terpenuhi, program akan mencetak "SALAH".
  - Kode ini mengecek apakah salah satu dari tiga bilangan (a, b, atau c) dapat merupakan hasil penjumlahan dari dua bilangan lainnya. Pada contoh output di sebelah kanan 
    gambar: Jika a = 100, b = 50, dan c = 200, maka tidak ada kondisi yang terpenuhi, sehingga hasilnya adalah "SALAH".
# Output hasil :




   



