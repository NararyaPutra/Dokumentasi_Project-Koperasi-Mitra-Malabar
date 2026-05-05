# 📌 Dokumentasi Project  
## Koperasi Mitra Malabar

---

## 📖 Gambaran Umum
Dokumen ini berisi gambaran alur sistem pada Project Koperasi Mitra Malabar, yang mencakup proses utama dalam pengelolaan data serta interaksi antar entitas dalam sistem.

---

## 🔄 Data Flow Diagram (DFD Level 1)

DFD Level 1 menggambarkan proses utama yang terjadi dalam sistem, yaitu:

1. **Login Akun**  
   Proses autentikasi pengguna sebelum mengakses sistem.

2. **Proses Input Data Leads**  
   Pengguna melakukan input data calon customer (leads) ke dalam sistem.

3. **Proses Input Data Campaign**  
   Pengguna menginput data campaign yang berkaitan dengan aktivitas pengiklanan produk.

4. **Validasi Data**  
   Data yang telah diinput akan melalui proses validasi untuk memastikan keakuratan dan kelengkapan.

5. **Kustomisasi History**  
   Sistem menyimpan dan mengelola histori aktivitas sebagai bentuk pencatatan perubahan data.

---

## 🔁 Sequence Diagram

Sequence Diagram menggambarkan interaksi antar entitas dalam sistem, khususnya pada modul **Leads**.

### 1. Leads

#### A. Customer
Pengelolaan data customer meliputi:
- Tambah Customer  
- Edit Customer  
- Lihat Customer  
- Hapus Customer  

#### B. Kunjungan
Pengelolaan data kunjungan meliputi:
- Tambah Kunjungan  
- Edit Kunjungan  
- Lihat Kunjungan  
- Hapus Kunjungan  

---
