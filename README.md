# Tugas 2 – Preprocessing Teks Ulasan E-Commerce Berbahasa Indonesia

## Identitas Mahasiswa

- **Nama:** Mohd Hasyrul Makhribi
- **NIM:** 24146112
- **Program Studi:** Sistem Informasi
- **Mata Kuliah:** Natural Language Processing (NLP)
- **Dosen Pengampu:** Teuku Rizky Noviandy, S.Kom., M.Kom.

## Deskripsi

Proyek ini merupakan pengerjaan tugas Natural Language Processing (NLP) tentang preprocessing teks ulasan produk e-commerce berbahasa Indonesia.

Dataset yang digunakan berasal dari Hugging Face, yaitu E-Commerce Product Reviews Sentiment. Proses preprocessing dilakukan untuk membersihkan dan mempersiapkan teks sebelum digunakan dalam analisis sentimen.

## Dataset

Sumber dataset:

https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment

Jumlah data: 11.606 ulasan.

Kolom dataset:
- `review`
- `translate`
- `sentimen`

## Tahapan Preprocessing

Preprocessing dilakukan melalui lima tahapan:

1. **Case Folding:** Mengubah seluruh huruf menjadi huruf kecil.
2. **Cleaning:** Menghapus URL, angka, tanda baca, dan karakter khusus.
3. **Tokenization:** Memisahkan teks menjadi kata-kata.
4. **Stopword Removal:** Menghapus kata-kata yang dianggap kurang penting menggunakan stopword bahasa Indonesia dari NLTK.
5. **Stemming:** Mengubah kata berimbuhan menjadi kata dasar menggunakan Sastrawi.

## Library yang Digunakan

- Python
- Pandas
- Hugging Face Datasets
- NLTK
- Sastrawi
- Matplotlib
- Seaborn

## Menjalankan Program

1. Pastikan Python dan Jupyter Notebook sudah tersedia.
2. Instal library yang diperlukan.
3. Buka file `analisis_sentimen.ipynb` menggunakan Jupyter Notebook atau Visual Studio Code.
4. Jalankan setiap cell secara berurutan.
5. Tunggu hingga proses preprocessing selesai.

## Hasil

Hasil pengerjaan meliputi informasi dataset, distribusi label sentimen, proses preprocessing, dan 10 contoh teks sebelum serta sesudah preprocessing.
