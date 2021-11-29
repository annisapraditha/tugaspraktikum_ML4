# tugaspraktikum_ML4

# OVERVIEW JURNAL
Skin Lesion Analysis Toward Melanoma Detection: A Challenge at the 2017 International Symposium on Biomedical Imaging (ISBI), Hosted by the International Skin Imaging Collaboration (ISIC), 
- dataset yang digunakan " http://challenge2017.isic-archive.com/ " didalamnya sudah terdapat testing, training, validation
- Lesion Segmentation, Dermoscopic Feature Classification, Disease Classification

# OVERVIEW DATASET
-https://www.kaggle.com/wanderdust/skin-lesion-analysis-toward-melanoma-detection
![image](https://user-images.githubusercontent.com/64590037/143798029-dd668b1a-2f0f-4258-9cf0-69d1aa9f00c1.png)
- terdapat 3 kelas
- tranin : melanoma (374 images), nevus (1372 images), seborrheic_keratosis (254 images)
- test : melanoma (117 images), nevus (393 images), seborrheic_keratosis (90 images)
- valid : melanoma (30 images), (78 images), seborrheic_keratosis (42 images)
- Data dibagi menjadi:

    data pelatihan (2000 gambar)
    dataset validasi (150 gambar)
    kumpulan data uji (600 gambar)

- spillting (80, 19, 1)
- keseluruhan data adalah 2570
- ![Screenshot (266)](https://user-images.githubusercontent.com/64590037/143911137-bfa6c031-7f7d-4472-8c0b-978f311f2646.png)


# PRE-PROCESSING
- size (250,250)
- horizontal flip (True)
- suffle (True)
- batch_size (32)
- class_mode (categorical)
- color_mode (rgb)

# MODEL YANG DIGUNAKAN
-MODEL 1
- Sequential (sequential_4)
- input_shape=(128, 128, 3))
- Dense, Dropout, Conv2D, Activation, Flatten, MaxPool2D, BatchNormalization
- ![Screenshot (265)](https://user-images.githubusercontent.com/64590037/143910733-5591b43f-37d3-4d7d-a2be-5fd00c5f0584.png)
- matrik evaluasi (-)
- grafik akurasi (-) karena ngerun epoch gagal terus
- ![Screenshot (263)](https://user-images.githubusercontent.com/64590037/143911262-acbeca11-af72-4e83-8c9e-a7b0f971d80d.png)
- grafik loss (-)
-MODEL2 (belum ada)
