# Panduan Belajar IPython Notebook (.ipynb)

## 1. Pengenalan IPython Notebook
IPython Notebook (sekarang disebut Jupyter Notebook) adalah sebuah lingkungan interaktif yang memungkinkan pengguna untuk menulis dan menjalankan kode Python dalam bentuk sel-sel (cells). File dengan ekstensi `.ipynb` merupakan format yang digunakan oleh Jupyter Notebook untuk menyimpan kode, teks, dan output dalam satu dokumen.

## 2. Instalasi Jupyter Notebook
Sebelum menggunakan Jupyter Notebook, Anda perlu menginstalnya terlebih dahulu. Gunakan salah satu perintah berikut:

```bash
pip install notebook
```
atau jika menggunakan Anaconda:
```bash
conda install -c conda-forge notebook
```

## 3. Menjalankan Jupyter Notebook
Setelah instalasi selesai, jalankan Jupyter Notebook dengan perintah berikut:
```bash
jupyter notebook
```
Perintah ini akan membuka antarmuka Jupyter Notebook di browser.

## 4. Struktur Jupyter Notebook
Jupyter Notebook terdiri dari beberapa elemen:
- **Sel (Cell)**: Unit utama untuk menulis kode atau teks.
- **Kernel**: Proses yang menjalankan kode dalam notebook.
- **Toolbar**: Berisi berbagai opsi untuk menjalankan kode, menyimpan notebook, dan mengelola sel.

## 5. Jenis-Jenis Sel dalam Jupyter Notebook
1. **Code Cell**: Digunakan untuk menulis dan menjalankan kode Python.
2. **Markdown Cell**: Digunakan untuk menulis teks dengan format Markdown.
3. **Raw Cell**: Menyimpan teks mentah tanpa format tertentu.

## 6. Menjalankan Kode di Jupyter Notebook
Untuk menjalankan sel kode, tekan `Shift + Enter` atau klik tombol "Run" di toolbar.

Contoh:
```python
print("Hello, Jupyter Notebook!")
```

## 7. Penggunaan Markdown dalam Jupyter Notebook
Markdown digunakan untuk membuat teks terformat dalam notebook. Contoh:

```markdown
# Judul Utama
## Subjudul
**Teks Tebal**
*Italic*
```

## 8. Menyimpan dan Mengekspor Notebook
Untuk menyimpan notebook, klik **File > Save and Checkpoint**. Notebook juga bisa diekspor ke format lain seperti **HTML, PDF, dan script Python** melalui **File > Download as**.
