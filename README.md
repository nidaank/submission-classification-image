# Rice Classification using CNN with TensorFlow

Proyek ini bertujuan untuk mengklasifikasikan gambar jenis beras ke dalam lima kelas berbeda menggunakan model Convolutional Neural Network (CNN) yang dibangun dengan TensorFlow dan Keras. Model kemudian disimpan dalam tiga format berbeda: `SavedModel`, `TFLite`, dan `TFJS` untuk kebutuhan deployment lintas platform.

---

## Dataset

Dataset yang digunakan merupakan kumpulan gambar dari lima jenis beras berikut:
- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

## Model Arsitektur

Model CNN dibangun menggunakan Keras Sequential API dengan layer:
- `Conv2D`, `MaxPooling2D`, `Dropout`, `BatchNormalization`
- `Flatten` dan `Dense`
- Optimizer: Adam
- Loss function: Categorical Crossentropy

### Inference Support:
- SavedModel (untuk deployment server/cloud)
- TFLite (untuk aplikasi mobile/embedded)
- TFJS (untuk aplikasi berbasis web/browser)

---