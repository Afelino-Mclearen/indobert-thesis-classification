# Analisis Perbandingan Algoritma K-Nearest Neighbor (K-NN) dan Decision Tree Berdasarkan Hasil Semantic Similarity Judul Skripsi dan Bidang Konsentrasi

## Deskripsi

Repository ini berisi implementasi penelitian skripsi yang berjudul:

**"Analisis Perbandingan Algoritma K-Nearest Neighbor (K-NN) dan Decision Tree Berdasarkan Hasil Semantic Similarity Judul Skripsi dan Bidang Konsentrasi (Studi Kasus: Jurusan Pendidikan Teknologi Informasi dan Komunikasi)"**

Penelitian ini bertujuan untuk membandingkan performa algoritma K-Nearest Neighbor (K-NN) dan Decision Tree dalam mengklasifikasikan judul skripsi berdasarkan bidang konsentrasi menggunakan representasi semantik yang dihasilkan oleh model IndoBERT.

---

## Latar Belakang

Pertumbuhan jumlah dokumen skripsi yang terus meningkat setiap tahun menimbulkan tantangan dalam proses pengelolaan dan pengelompokan topik penelitian berdasarkan bidang konsentrasi.

Untuk mengatasi permasalahan tersebut, penelitian ini memanfaatkan IndoBERT sebagai metode representasi semantik sehingga informasi makna dalam judul skripsi dapat direpresentasikan dengan lebih baik sebelum dilakukan proses klasifikasi.

---

## Tujuan Penelitian

- Menganalisis perbandingan performa algoritma K-Nearest Neighbors dan Decision Tree berdasarkan representasi embedding semantik IndoBERT judul skripsi.
- Menentukan algoritma yang menghasilkan performa terbaik dari K-Nearest Neighbor (K-NN) dan Decision Tree.
- Membandingkan performa algoritma K-Nearest Neighbors (K-NN) dan Decision Tree terhadap model baseline TF-IDF + Logistic Regression
- Mengevaluasi hasil klasifikasi menggunakan metrik Accuracy, Precision, Recall, dan F1-Score.

---

## Bidang Konsentrasi

Klasifikasi dilakukan terhadap tiga bidang konsentrasi, yaitu:

- Rekayasa Perangkat Lunak (RPL)
- Teknik Komputer dan Jaringan (TKJ)
- Multimedia

---

## Metodologi Penelitian

### 1. Pengumpulan Data
Data penelitian berupa judul skripsi yang telah dikelompokkan berdasarkan bidang konsentrasi.

### 2. Pra-pemrosesan Teks
Tahapan preprocessing meliputi:

- Case Folding
- Text Cleaning
- Normalisasi Teks
- Stopword Removal
- Stemming

### 3. Representasi Semantik
Judul skripsi diubah menjadi vektor representasi menggunakan model IndoBERT.

### 4. Klasifikasi
Algoritma yang dibandingkan:

- K-Nearest Neighbor (K-NN)
- Decision Tree
- TF-IDF + Logistic Regression (Model Baseline)

### 5. Evaluasi Model
Evaluasi dilakukan menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Teknologi yang Digunakan

- Python
- Google Colab
- IndoBERT
- Transformers
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Sastrawi

---

## Struktur Repository

```text
indobert-thesis-classification
│
├── IndoBERT_Thesis_Classification.ipynb
├── README.md
├── requirements.txt
├── LICENSE
│
└── results/
    ├── confusion_matrix_knn.png
    ├── confusion_matrix_dt.png
    └── model_comparison.png
```

---

## Cara Menjalankan Program

1. Clone repository ini.

```bash
git clone https://github.com/Afelino-Mclearen/indobert-thesis-classification.git
```

2. Masuk ke folder repository.

```bash
cd indobert-thesis-classification
```

3. Install seluruh dependency.

```bash
pip install -r requirements.txt
```

4. Buka notebook menggunakan Google Colab atau Jupyter Notebook.

5. Upload dataset yang digunakan.

6. Jalankan seluruh sel secara berurutan.

---

## Hasil Penelitian

Penelitian ini membandingkan performa algoritma K-Nearest Neighbor (K-NN) dan Decision Tree berdasarkan representasi semantic similarity yang dihasilkan oleh IndoBERT.

Evaluasi dilakukan menggunakan metrik:

- Accuracy
- Precision
- Recall
- F1-Score

Visualisasi hasil evaluasi dapat dilihat pada folder `results/`.

---

## Catatan Dataset

Dataset yang digunakan dalam penelitian ini merupakan kumpulan judul skripsi yang telah diberi label berdasarkan bidang konsentrasi. Dataset tidak disertakan dalam repository ini untuk menjaga kepentingan akademik dan institusi.

---

## Penulis

**Afelino Mclearen**

Mahasiswa Program Studi Pendidikan Teknologi Informasi dan Komunikasi

Fakultas Teknik

Universitas Negeri Manado

---

## Lisensi

Proyek ini menggunakan lisensi MIT License.
