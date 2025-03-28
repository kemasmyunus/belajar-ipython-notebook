# Belajar IPython Notebook (.ipynb)

## 1. Menjalankan Jupyter Notebook
Setelah instalasi selesai, jalankan Jupyter Notebook dengan perintah berikut:
```bash
jupyter notebook
```
Perintah ini akan membuka antarmuka Jupyter Notebook di browser, tempat Anda dapat membuat dan mengelola notebook.

## 2. Struktur Jupyter Notebook
Jupyter Notebook terdiri dari beberapa elemen:
- **Sel (Cell)**: Unit utama untuk menulis kode atau teks.
- **Kernel**: Proses yang menjalankan kode dalam notebook.
- **Toolbar**: Berisi berbagai opsi untuk menjalankan kode, menyimpan notebook, dan mengelola sel.

## 3. Jenis-Jenis Sel dalam Jupyter Notebook
1. **Code Cell**: Digunakan untuk menulis dan menjalankan kode Python.
2. **Markdown Cell**: Digunakan untuk menulis teks dengan format Markdown.
3. **Raw Cell**: Menyimpan teks mentah tanpa format tertentu.

## 4. Menjalankan Kode di Jupyter Notebook
Untuk menjalankan sel kode, tekan `Shift + Enter` atau klik tombol "Run" di toolbar.

Contoh:
```python
print("Hello, Jupyter Notebook!")
```

## 5. Penggunaan Markdown dalam Jupyter Notebook
Markdown digunakan untuk membuat teks terformat dalam notebook. Contoh:

```markdown
# Judul Utama
## Subjudul
**Teks Tebal**
*Italic*
```

## 6. Menyimpan dan Mengekspor Notebook
Untuk menyimpan notebook, klik **File > Save and Checkpoint**. Notebook juga bisa diekspor ke format lain seperti **HTML, PDF, dan script Python** melalui **File > Download as**.

## 7. Menjalankan Perintah Terminal di Jupyter Notebook
Anda bisa menjalankan perintah terminal langsung dari dalam notebook dengan menggunakan awalan `!`.

Contoh:
```python
!ls  # Menampilkan daftar file di direktori (Linux/macOS)
!dir  # Menampilkan daftar file di direktori (Windows)
```

## 8. Menggunakan Magic Commands
Magic commands adalah fitur khusus dalam Jupyter Notebook yang memudahkan berbagai tugas.

Contoh:
- `%timeit`: Mengukur waktu eksekusi suatu perintah.
- `%run nama_script.py`: Menjalankan script Python.
- `%matplotlib inline`: Menampilkan plot secara langsung di dalam notebook.

Contoh penggunaan:
```python
%timeit sum(range(1000))
```
