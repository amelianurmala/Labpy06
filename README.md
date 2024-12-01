# Labpy06

Nama   : Amelia Nurmala Dewi 

Kelas  : TI.24.A2 

NIM    : 312410199

# LATIHAN 1

## Berikut ini adalah gambar kodenya

![Screenshot (150)](https://github.com/user-attachments/assets/4564dffe-0c4d-406b-a7dd-370ba5d29d2a)

## Berikut ini adalah penjelasan pada kode di atas

1. **Lambda untuk `a(x)`**  
   Fungsi ini menerima satu parameter `x` dan mengembalikan nilai `x**2`. Dengan lambda: `lambda x: x**2`.

2. **Lambda untuk `b(x, y)`**  
   Fungsi ini menerima dua parameter `x` dan `y`, lalu mengembalikan akar kuadrat dari jumlah kuadrat keduanya menggunakan `math.sqrt`. Dengan lambda: `lambda x, y: math.sqrt(x**2 + y**2)`.

3. **Lambda untuk `c(*args)`**  
   Fungsi ini menerima banyak argumen `*args`, menjumlahkan semua elemen, dan membagi hasilnya dengan jumlah elemen. Dengan lambda: `lambda *args: sum(args) / len(args)`.

4. **Lambda untuk `d(s)`**  
   Fungsi ini menerima string `s`, lalu menggabungkan karakter unik dari string tersebut (menggunakan `set` untuk membuat unik). Dengan lambda: `lambda s: "".join(set(s))`.


# Berikut ini adalah gambar hasil kodenya (Output)

![Screenshot (151)](https://github.com/user-attachments/assets/1ef463c4-f94d-4c5f-ad30-ef5034efc9de)


# Berikut adalah penjelasannya pada hasil kode di atas

1. **Fungsi `a(5)`** menghitung kuadrat dari `5`, hasilnya adalah `25`.
2. **Fungsi `b(3, 4)`** menghitung akar kuadrat dari (3² + 4²), hasilnya adalah `5.0`.
3. **Fungsi `c(1, 2, 3, 4, 5)`** menghitung rata-rata dari angka-angka tersebut, hasilnya adalah `3.0`.
4. **Fungsi `d("hello")`** mengembalikan string dengan karakter unik dari input `hello` (urutan hasil dapat berbeda).


# TUGAS PRATIKUM 

## Berikut ini adalah gambar kodenya 

![Screenshot (154)](https://github.com/user-attachments/assets/e41fc8c4-1222-4c22-bef9-e0e2d226a9fa)
![Screenshot (155)](https://github.com/user-attachments/assets/b5e66387-b5b7-4572-9a76-7835e828eed5)

## Berikut ini adalah penjelasan pada kode diatas

1. **Dictionary `data_mahasiswa`**
   - Digunakan untuk menyimpan data mahasiswa dalam format `{nama: nilai}`.

2. **Fungsi `tambah(nama, nilai)`**
   - Menambahkan data mahasiswa baru ke dictionary.
   - Jika nama mahasiswa sudah ada, menampilkan pesan bahwa data sudah ada.

3. **Fungsi `tampilkan()`**
   - Menampilkan semua data mahasiswa dalam format daftar.
   - Jika tidak ada data, menampilkan pesan bahwa data kosong.

4. **Fungsi `hapus(nama)`**
   - Menghapus data mahasiswa berdasarkan nama.
   - Jika nama tidak ditemukan, menampilkan pesan error.

5. **Fungsi `ubah(nama, nilai_baru)`**
   - Mengubah nilai mahasiswa berdasarkan nama.
   - Jika nama tidak ditemukan, menampilkan pesan error.

6. **Menu Utama (Loop)**
   - Menyediakan menu interaktif:
     - Pilihan **1**: Menambah data mahasiswa.
     - Pilihan **2**: Menampilkan data mahasiswa.
     - Pilihan **3**: Menghapus data mahasiswa.
     - Pilihan **4**: Mengubah nilai mahasiswa.
     - Pilihan **5**: Keluar dari program.
   - Input pengguna divalidasi, dan jika input tidak valid, menampilkan pesan error.


## Berikut ini adalah hasilnya (Output)

### 1. Tambahakan Data
   ![Screenshot (152) - Copy](https://github.com/user-attachments/assets/4e841416-85fb-4f26-9bdf-3dc5b6269470)

   Penjelasan:
   
- Pengguna memilih menu **1** (tambah data).
- Memasukkan nama **Amelia Nurmala Dewi** dan nilai **90**.
- Data dan nilai Mahasiswa Amelia Nurmala Dewi Berhasil ditambahkan

---

### 2. Tampilkan Data
   ![Screenshot (153) - Copy](https://github.com/user-attachments/assets/ccc98900-34c0-40f5-9d1c-7004dc975eb6)

   Penjelasan:
   
- Pengguna memilih menu **2** (tampilkan data).
- Program memeriksa bahwa ada data dalam dictionary `data_mahasiswa`.
- Menampilkan daftar mahasiswa beserta nilai mereka, dalam hal ini **Amelia Nurmala Dewi** dengan nilai **90.0**.

---

### 3. Menghapus Data
   ![Screenshot (153)](https://github.com/user-attachments/assets/315dc6a5-537e-48ce-bbc4-fa8dea72c8ec)

   Penjelasan:

- Pengguna memilih menu **3** (hapus data) dan memasukkan nama **Amelia Nurmala Dewi**.
- Program memeriksa bahwa nama **Amelia Nurmala Dewi** ada dalam `data_mahasiswa`.
- Data **Amelia Nurmala Dewi** dihapus dari dictionary, dan pesan konfirmasi ditampilkan.

---

### 4. Mengubah Data
   ![Screenshot (152)](https://github.com/user-attachments/assets/15f66711-a892-46bd-8ef8-b346b291fdac)
   
   Penjelasan:
   
- Pengguna memilih menu **4** (ubah data) untuk mengubah nilai mahasiswa bernama **Alice**.
- Karena sebelumnya data **Alice** sudah dihapus (pada langkah 4), program tidak menemukan nama tersebut dalam dictionary `data_mahasiswa`.
- Pesan error ditampilkan untuk memberitahu bahwa data **Alice** tidak ditemukan.

---

### 5. Keluar dari Program
   ![Screenshot (154) - Copy](https://github.com/user-attachments/assets/0d02be0e-dce9-4042-8ab6-9581f3a416ec)

   Penjelasan:
   
- Pengguna memilih menu **5** (keluar).
- Program menghentikan eksekusi dan menampilkan pesan konfirmasi **"Keluar dari program"** sebelum keluar.

  ## Berikut adalah gambar flowchart nya

  ![6224181741560643372](https://github.com/user-attachments/assets/b713d080-a1e2-4b52-aead-0dad8ed0fbb8)


