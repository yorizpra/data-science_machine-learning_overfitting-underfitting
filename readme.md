# Data Science Machine Learning: Overfitting and Underfitting

Repository ini berisi notebook yang menjelaskan tentang overfitting dan underfitting dalam machine learning, serta berbagai teknik untuk mengatasi kedua masalah tersebut.

## Struktur Direktori

- `overfitting_underfitting.ipynb`: Notebook utama yang berisi penjelasan dan kode untuk mendeteksi serta mengatasi overfitting dan underfitting.

## Cara Menggunakan

1. Clone repository ini ke lokal Anda:
    ```sh
    git clone https://github.com/yorizpra/data-science_machine-learning_overfitting-underfitting.git
    cd data-science_machine-learning_overfitting-underfitting
    ```

2. Buka file `overfitting_underfitting.ipynb` menggunakan Jupyter Notebook atau JupyterLab.

## Isi Notebook

Notebook ini mencakup:

1. **Import Library**: Mengimpor pustaka yang diperlukan untuk analisis data dan pemodelan machine learning.
2. **Memuat Dataset untuk Kasus Overfitting**: Menggunakan dataset California Housing untuk mendemonstrasikan overfitting.
3. **Mendeteksi Overfitting**: Menggunakan Mean Squared Error (MSE) dan learning curve untuk mendeteksi overfitting.
4. **Mengatasi Overfitting**: Berbagai teknik untuk mengatasi overfitting, termasuk cross-validation, regularization, pruning, data augmentation, Random Forest, dan early stopping.
5. **Memuat Dataset untuk Kasus Underfitting**: Menggunakan dataset Breast Cancer untuk mendemonstrasikan underfitting.
6. **Mendeteksi Underfitting**: Menggunakan akurasi dan learning curve untuk mendeteksi underfitting.
7. **Mengatasi Underfitting**: Berbagai teknik untuk mengatasi underfitting, termasuk menggunakan model yang lebih kompleks, feature engineering dengan PCA, hyperparameter tuning, preprocessing data, dan menambah data latih.

## Persyaratan

- Python 3.9
- Jupyter Notebook atau JupyterLab
- Pustaka Python yang diperlukan (dapat diinstal menggunakan `pip` atau `conda`)

## Instalasi Pustaka

Untuk menginstal pustaka yang diperlukan, jalankan perintah berikut:
```sh
pip install numpy pandas scikit-learn matplotlib