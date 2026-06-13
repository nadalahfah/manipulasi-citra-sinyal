# Eksperimen Manipulasi Citra Digital Menggunakan OpenCV

**Nama Mahasiswa :** Nada Lahfah Diha 
**NIM              :** 452024618093  
**Mata Kuliah      :** Pengolahan Sinyal Digital  
**Dosen Pengampu   :** Assoc. Prof. Dr. Ir. Oddy Virgantara Putra, S.Kom., M.T., IPP.  
**Universitas      :** Universitas Darussalam Gontor  

---

## 1. Deskripsi Singkat Project
Project ini merupakan implementasi berbagai teknik manipulasi citra digital menggunakan Python dan OpenCV. Eksperimen dilakukan untuk menganalisis secara mendalam pengaruh perubahan nilai piksel terhadap tampilan visual citra, tingkat kecerahan (*brightness*), kontras (*contrast*), serta detail objek.

Teknik yang diterapkan pada project ini meliputi:
* Membaca dan menampilkan citra
* Konversi format warna BGR ke RGB
* Penyesuaian ukuran citra (*Resize*)
* Penggabungan citra berbobot (*Image Blending*)
* Pembalikan nilai intensitas (*Image Negative*)
* Perbaikan kontras non-linier menggunakan Transformasi Logaritmik
* Koreksi pencahayaan fleksibel menggunakan Transformasi Gamma

---

## 2. Citra yang Digunakan
Project ini menggunakan dua citra digital sebagai aset uji coba yang disimpan di dalam folder `images/`:
* `image1.jpg`: Digunakan sebagai citra utama untuk seluruh uji coba transformasi visual tunggal.
* `image2.jpg`: Digunakan sebagai citra sekunder pasangan untuk proses penggabungan (*image blending*).

---

## 3. Library yang Digunakan
* **OpenCV (opencv-python):** Library utama untuk operasi pembacaan, manipulasi matriks spasial, dan transformasi fungsi citra.
* **NumPy:** Digunakan untuk komputasi array dan operasi aritmatika tingkat tinggi pada tingkat piksel.
* **Matplotlib:** Digunakan untuk menampilkan visualisasi citra keluaran serta grafik distribusi piksel (histogram).

---

## 4. Struktur Folder Project
Repositori disusun dengan struktur baku berikut untuk mempermudah pemeriksaan dan replikasi eksperimen:
```text
manipulasi-citra-digital/
│
├── notebook/
│   └── image_manipulation.ipynb         # File Jupyter Notebook / Google Colab utama
│
├── images/
│   ├── image1.jpg                       # Citra uji coba pertama
│   └── image2.jpg                       # Citra uji coba kedua
│
├── report/
│   └── laporan.pdf                      # Laporan dokumentasi PDF maksimal 8 halaman
│
├── README.md                            # Panduan utama project
└── requirements.txt                     # File daftar dependency library
