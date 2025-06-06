# Banana Ripeness Classification
## Project Overview
Klasifikasi tingkat kematangan buah pisang menggunakan Convolutional Neural Network (CNN).
Proyek ini membagi kematangan pisang menjadi empat kelas:
- Unripe → Mentah
- Ripe → Matang
- Overripe → Terlalu Matang
- Rotten → Busuk

Semua proses dilakukan dalam satu notebook, mulai dari:
- Persiapan dataset
- Preprocessing
- Training model CNN
- Evaluasi performa
- Inference terhadap gambar baru

Proyek dikembangkan menggunakan TensorFlow dan dijalankan di Google Colab.

## Dataset
Dataset yang digunakan dalam proyek ini merupakan kumpulan gambar buah pisang yang diklasifikasikan ke dalam empat kelas, dan diperoleh dari platform Kaggle. Dataset tersebut dapat diakses melalui tautan berikut: https://www.kaggle.com/datasets/atrithakar/banana-classification

##
Secara keseluruhan, diperoleh model terbaik dengan akurasi pada training set sekitar 96.89% dan pada testing set sekitar 93.92%. Model dilatih menggunakan arsitektur CNN dengan 32 neuron pada layer konvolusi, optimizer AdamW, learning rate = 0.00002, dan 20 epoch.
