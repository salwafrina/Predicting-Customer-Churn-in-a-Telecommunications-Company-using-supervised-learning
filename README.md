# Predicting Customer Churn in a Telecommunications Company using Supervised Learning

Proyek klasifikasi untuk memprediksi customer churn (pelanggan berhenti berlangganan) pada perusahaan telekomunikasi menggunakan algoritma **Naive Bayes**.

## 📌 Deskripsi

Customer churn adalah kondisi ketika pelanggan berhenti menggunakan layanan suatu perusahaan. Karena mempertahankan pelanggan lama lebih murah dibanding akuisisi pelanggan baru, mendeteksi potensi churn lebih awal menjadi prioritas strategis bagi perusahaan telekomunikasi.

Proyek ini membangun model klasifikasi untuk memprediksi apakah seorang pelanggan akan churn atau tidak, berdasarkan data demografi, jenis layanan, dan riwayat langganan.

## 🎯 Tujuan

- Memprediksi customer churn menggunakan metode klasifikasi Naive Bayes.
- Mengidentifikasi faktor-faktor utama yang memengaruhi churn.
- Memberikan rekomendasi yang dapat membantu perusahaan telekomunikasi meningkatkan strategi retensi pelanggan.

## 📊 Dataset

- **Sumber:** Telco Customer Churn Dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`)
- **Ukuran:** 7.043 baris, 21 kolom (7.032 baris setelah pembersihan data)
- **Target variable:** `Churn` (Yes/No)
- **Fitur:** demografi pelanggan (gender, SeniorCitizen, Partner, Dependents), informasi layanan (InternetService, OnlineSecurity, TechSupport, dll), serta data kontrak dan tagihan (Contract, PaymentMethod, MonthlyCharges, TotalCharges)

## 🛠️ Metodologi

1. **Data Cleaning** — menghapus data duplikat dan menangani missing values.
2. **Encoding** — mengubah fitur kategorikal menjadi numerik dengan Label Encoding.
3. **Data Splitting** — 80% data training, 20% data testing.
4. **Modeling** — melatih model Naive Bayes untuk mengenali pola pelanggan yang churn vs. bertahan.
5. **Evaluation** — mengevaluasi performa model menggunakan accuracy, precision, recall, F1-score, dan confusion matrix.

## 📈 Hasil

| Metric | No (Stay) | Yes (Churn) |
|---|---|---|
| Precision | 0.88 | 0.56 |
| Recall | 0.81 | 0.69 |
| F1-score | 0.84 | 0.62 |

**Akurasi keseluruhan: ~77,6%**

## ⚙️ Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib

## 🚀 Cara Menjalankan

```bash
# clone repository
git clone <url-repo-ini>
cd <nama-folder>

# install dependencies
pip install pandas numpy scikit-learn matplotlib

# jalankan notebook
jupyter notebook Predicting_Customer_Churn_in_a_Telecommunications_Company_using_supervised_learning.ipynb
```

> Pastikan file dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) berada di folder yang sama dengan notebook, atau sesuaikan path pembacaan data di dalam notebook.

## 👥 Tim

- Devlin Wen Sujatmiko
- George Steve
- Salwa Afrina Fadli

UNIJI, DKI Jakarta, Indonesia

## 📚 Referensi

1. A. K. Agasti, P. K. Sahu, R. Panda, "Predicting customer churn in telecommunication sector using Naive Bayes algorithm," *Indonesian Journal of Electrical Engineering and Computer Science*, vol. 32, no. 1, 2023.
2. A. Ebrah, M. Elnasir, "Churn prediction using machine learning and recommendations plans for telecoms," *Journal of Computer and Communications*, vol. 7, no. 11, 2019.
3. S. Ouf, M. A. Abdel-Hamid, H. A. Hefny, "A proposed hybrid framework to improve the accuracy of customer churn prediction in telecom industry," *Journal of Big Data*, vol. 12, no. 1, 2024.
4. Tridens Technology, "Telecom churn: definition, prediction, and prevention," 2024.
