- **Nama:** Femilia Padaunan
- **NIM:** H071241012
- **Kelas:** Deep Learning A

---

## 🧠 Model yang Diimplementasikan

### 1. Convolutional Neural Network (CNN)
- **Dataset:** Fashion-MNIST (60.000 data training, 10.000 data testing citra ukuran 28x28 piksel).
- **Arsitektur:** 3x Layer Konvolusi (`Conv2D` + `MaxPooling2D`), *Flatten*, *Dense Layer* dengan Dropout (0.5), dan *Softmax* output (10 kelas).
- **File Notebook:** `01_CNN_FashionMNIST/cnn_fashion_mnist.ipynb`

### 2. Recurrent Neural Network (RNN - LSTM)
- **Dataset:** IMDb Movie Reviews (Analisis sentimen ulasan teks positif/negatif).
- **Arsitektur:** *Embedding Layer* (max_features=10000), *LSTM Layer* (64 unit dengan dropout), dan *Sigmoid Output Layer*.
- **File Notebook:** `02_RNN_IMDb/rnn_imdb_sentiment.ipynb`
