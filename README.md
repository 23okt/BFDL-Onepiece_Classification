# 🏴‍☠️ One Piece Image Classifier

Klasifikasi gambar karakter anime **One Piece** menggunakan Deep Learning dan Transfer Learning.  
Proyek ini dirancang untuk mengenali karakter-karakter ikonik seperti **Luffy**, **Zoro**, **Sanji**, **Ace**, dan lainnya, melalui model yang dapat dijalankan di **web** maupun **perangkat mobile**.

---

## 📌 Deskripsi Proyek

One Piece Image Classifier adalah proyek **image classification** yang menggunakan **model deep learning berbasis MobileNetV2** untuk mengklasifikasikan gambar ke dalam beberapa kategori karakter anime One Piece. Model ini dioptimalkan untuk digunakan di berbagai platform melalui konversi ke format **TensorFlow Lite (TFLite)** untuk aplikasi mobile dan **TensorFlow.js (TFJS)** untuk aplikasi web.

---

## 🚀 Fitur Utama

✅ **Klasifikasi Karakter Otomatis**  
🔁 **Transfer Learning dengan MobileNetV2**  
📱 **Model TFLite** – Dioptimalkan untuk Android/iOS  
🌐 **Model TFJS** – Bisa dijalankan langsung di browser  
📊 **Visualisasi Training dan Inference**

---

## 🧠 Teknologi yang Digunakan

| Teknologi           | Keterangan                                           |
| ------------------- | ---------------------------------------------------- |
| **Python**          | Bahasa pemrograman utama                             |
| **TensorFlow**      | Untuk pelatihan model deep learning                  |
| **TensorFlow Lite** | Untuk menjalankan model di mobile                    |
| **TensorFlow.js**   | Untuk integrasi model di web                         |
| **MobileNetV2**     | Model pretrained untuk transfer learning             |
| **pandas**          | Untuk manipulasi dan analisis data                   |
| **NumPy**           | Untuk operasi array dan numerik                      |
| **scikit-learn**    | Untuk train-test split                               |
| **Matplotlib**      | Untuk visualisasi distribusi data dan performa model |

---

## 📁 Struktur Proyek

📦 one-piece-image-classifier
├── 📂 dataset
│ └── [folder karakter One Piece]
├── 📜 model_training.ipynb
├── 📜 tflite_conversion.ipynb
├── 📜 tfjs_conversion.ipynb
├── 📁 saved_models/
│ ├── model.h5
│ ├── model.tflite
│ └── model_tfjs/
└── README.md
