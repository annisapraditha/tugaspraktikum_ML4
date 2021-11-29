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
- 
