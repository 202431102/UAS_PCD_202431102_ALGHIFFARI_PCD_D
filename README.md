# UAS_PCD_202431102_ALGHIFFARI_PCD_D
## Filtering Citra Menggunakan Median Filtering dan Mean Filtering

### Identitas Mahasiswa

- **Nama** : Alghiffari
- **NIM** : 202431102
- **Kelas** : PCD D
- **Mata Kuliah** : Pengolahan Citra Digital

---

## Deskripsi Project

Project ini merupakan tugas Ujian Akhir Semester (UAS) mata kuliah Pengolahan Citra Digital. Tujuan dari project ini adalah menerapkan teknik filtering citra menggunakan bahasa pemrograman Python pada Jupyter Notebook.

Metode filtering yang digunakan terdiri dari:

- Median Filtering menggunakan library OpenCV.
- Mean Filtering yang dibuat secara manual tanpa menggunakan fungsi bawaan OpenCV.

Citra yang digunakan merupakan foto pribadi yang diambil menggunakan kamera smartphone sesuai dengan ketentuan praktikum.

---

## Tujuan Project

- Memahami konsep dasar filtering citra.
- Menerapkan Median Filtering menggunakan OpenCV.
- Mengimplementasikan Mean Filtering secara manual.
- Membandingkan hasil filtering dengan citra asli.

---

## Software yang Digunakan

- Python 3
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib

---

## Struktur Folder

```
UAS_PCD_202431102_ALGHIFFARI_PCD_d
│
├── UAS_PRAKTIKUM_202431102_ALGHIFFARI_PCD_D.ipynb
├── README.md
├── image
│   ├── fotodiri.jpeg
│   ├── bukti_metadata.jpg
│   └── hasil_output.png
│
 └── Laporan_UAS_PRAKTIKUM_202431102_ALGHIFFARI_PCD_D.pdf
```

---

## Library yang Digunakan

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
```

---

## Cara Menjalankan Program

1. Clone atau download repository ini.

2. Install library yang dibutuhkan.

```bash
pip install opencv-python numpy matplotlib
```

3. Buka file

```
UAS_PRAKTIKUM_202431102_ALGHIFFARI_PCD_D.ipynb
```

menggunakan Jupyter Notebook.

4. Pastikan file gambar

```
fotodiri.jpeg
```

berada pada folder yang sama dengan notebook.

## Output Program

Program akan menampilkan:

- Original Image
- Median Filtering
- Mean Filtering (Manual)

Selain ditampilkan pada Jupyter Notebook, hasil filtering juga dapat disimpan sebagai file gambar.

---

## Hasil

Metode Median Filtering mampu mengurangi noise tanpa banyak menghilangkan detail objek, sedangkan Mean Filtering menghasilkan citra yang lebih halus namun sedikit mengurangi ketajaman gambar karena menggunakan nilai rata-rata piksel.

---

## Referensi

1. OpenCV. (2024). OpenCV Documentation. https://docs.opencv.org/

2. Python Software Foundation. (2025). Python Documentation. https://docs.python.org/

3. Matplotlib Development Team. (2024). Matplotlib Documentation. https://matplotlib.org/

4. NumPy Developers. (2024). NumPy Documentation. https://numpy.org/

**Alghiffari**

NIM : 202431102

Kelas : PCD D
