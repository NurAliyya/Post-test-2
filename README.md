# Sistem Pendaftaran Konser Post-test-2
Nama: Nur Aliyya

Kelas: C

Nim: 2409116094
# Deskripsi Program
Program ini adalah aplikasi berbasis Java Console dengan tema Sistem Pendaftaran Konser. Aplikasi ini memungkinkan pengguna untuk mengelola data peserta konser menggunakan operasi dasar CRUD (Create, Read, Update, Delete).
Selain CRUD, program juga dilengkapi dengan validasi input (nama tidak boleh kosong, email harus valid). Dan fitur pencarian peserta berdasarkan nama. Penerapan struktur MVC (Model, View, Controller) dengan pemisahan packages.

# Alur Program
1.Menampilkan menu utama:

 Sistem Pendaftaran Konser 
- Tambah Peserta
- Lihat Peserta
- Update Peserta
- Hapus Peserta
- Cari Peserta
- Keluar
- Pilih menu:
  
2. Tambah Peserta (Create)
- User memilih 1.
- Program meminta nama dan email.
- Sistem melakukan validasi input:
- Nama tidak boleh kosong.
- Email harus mengandung @.
- Jika valid maka data disimpan dan diberikan ID otomatis.
Masukkan Nama: Naya
Masukkan Email: Marzahanaya@mail.com
Peserta berhasil ditambahkan!

3. Tampilkan Peserta (Read)
- User memilih 2.
- Program menampilkan daftar semua peserta.
  
ID: 1 | Nama: Naya | Email: Marzahanaya@mail.com

ID: 2 | Nama: Dapi | Email: Abidzar@mail.com

4. Update Peserta (Update)
- User memilih 3.
- Cari peserta berdasarkan (1 = ID, 2 = Email): 2
- Masukkan Email Peserta: abidzar@gmail.com
Masukkan Nama baru: davi abidzar

Masukkan Email baru: abidzarghifarl@gmail.com

Data peserta berhasil diperbarui!

5. Hapus Peserta (Delete)
- User memilih 4.
- Masukkan ID peserta yang ingin dihapus.
Masukkan ID Peserta yang ingin dihapus: 2

Peserta berhasil dihapus!

6. Cari Peserta (Search)
- User memilih 5.
- Masukkan kata kunci nama.
- Program mencari peserta yang cocok.
Masukkan Nama yang dicari: Naya

ID: 1 | Nama: Marza Hanaya | Email: Marzahanaya@mail.com

7. Keluar Program
- User memilih 0
- Program menampilkan pesan:

<img width="1389" height="763" alt="image" src="https://github.com/user-attachments/assets/5d07eff6-f26a-4a2e-a61b-3a362c755ae7" />
<img width="1371" height="707" alt="image" src="https://github.com/user-attachments/assets/6bcfab9b-2ec0-43ce-9f1c-65265701d6b4" />
<img width="1398" height="749" alt="image" src="https://github.com/user-attachments/assets/c80a9498-43ef-46a2-b312-43bd456703d3" />



