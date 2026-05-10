# automatic-file-sorter-with-jupyter-notebook

# Automatic File Sorter

Project sederhana berbasis Python untuk merapikan file yang berantakan di dalam sebuah folder (seperti folder *Downloads*). Script ini secara otomatis akan mendeteksi ekstensi file dan memindahkannya ke dalam folder kategori yang sesuai.

## Fitur Utama

* **Pembuatan Folder Otomatis:** Program akan mengecek dan membuat folder kategori secara otomatis jika folder tersebut belum ada.
* **Penyortiran Berdasarkan Ekstensi:** Memindahkan file ke folder yang tepat berdasarkan tipe filenya.
* **Tanpa Pustaka Eksternal:** Hanya menggunakan pustaka bawaan Python (`os` dan `shutil`), sehingga tidak perlu melakukan instalasi dependensi tambahan.

## Kategori File yang Didukung

Program ini saat ini mendukung penyortiran untuk ekstensi file berikut:

| Kategori Folder | Ekstensi File yang Didukung |
| :--- | :--- |
| **csv files** | `.csv` |
| **pdf files** | `.pdf` |
| **exe files** | `.exe` |
| **excel files** | `.xlsx` |
| **images files** | `.png`, `.jpg`, `.jpeg` |
| **word files** | `.docx` |
| **txt files** | `.txt` |

## Note

### Secara default, program ini menggunakan path spesifik. Silahkan ubah path ini sebelum menjalankan program.
# Ubah bagian ini dengan lokasi folder yang ingin disortir
path = r"C:/Users/NamaKamu/Downloads/"

## Rencana Pengembangan (To-Do List)
  **Mengonversi script menjadi file .py standar.**
  **Implementasi watchdog untuk penyortiran real-time di background.**
  **Membangun Graphical User Interface (GUI) sederhana.**
