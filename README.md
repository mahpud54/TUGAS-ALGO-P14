# TUGAS-ALGO-P14

## APLIKASI TOKO KECIL 

2. Dokumentasi Teknis

3. Komponen dan Spesifikasi
   
-Nama Aplikasi : Sistem Manajemen Inventori Toko Kecil

-Bahasa : Python 3.x

-Basis Data : SQLite

-Platform : Terminal (CLI - Command Line Interface)

-Fungsi Utama : Tambah barang, cari barang, lihat laporan stok

-Fitur Tambahan : Otomatis membuat database saat pertama dijalankan


# Inisialisasi dan setup database SQLite
def init_db():
    """
    Membuat database dan tabel items jika belum ada.
    Tabel menyimpan kode_barang, nama_barang, jumlah, dan satuan.
    """
    ...

# Menambahkan barang baru ke database
def tambah_barang():
    """
    Meminta input user (kode, nama, jumlah, satuan),
    lalu menyimpan data ke database SQLite.
    """
    ...

# Mencari barang berdasarkan nama atau kode
def cari_barang():
    """
    Meminta keyword pencarian dari user,
    lalu mencari barang dalam database yang mengandung kata tersebut.
    """
    ...

# Menampilkan semua data stok barang
def laporan_stok():
    """
    Menampilkan seluruh isi tabel items dalam format laporan.
    """
    ...

# Menu utama aplikasi
def main():
    """
    Menampilkan menu CLI: tambah, cari, lihat stok, keluar.
    Menjalankan fungsi sesuai pilihan user.
    """
    ...
