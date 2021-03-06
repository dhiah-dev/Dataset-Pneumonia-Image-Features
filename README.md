# Dataset-Pneumonia-Image-Extracted-Features
Dataset of extracted features from normal and effected patients image for chest X-Ray. Features are extracted based on two different methods Principles Component Analysis (PCA) and Histogram of Gredients (HOG). Dataset recodes are labelled and ready to be applied by several approaches like machine learning.

The dataset features are extracted from two different image dimensions of the same X-Ray image samples, 700x800 and 1200x1300. 
HOG has been applied on three different block sizes, 8x8, 16x16, and 32x32. The final generated versions are X-Ray image 700x800 with PCA, HOG 8x8, HOG 16x16, and HOG 32x32 and the same for X-Ray image samples 1200x1300. The final 8 dataset versions are provided in both CSV and Mat files.
Dataset consists of 292 X-Ray images with 4 ARDS, 4 E.Coli, 11 SARS, 1 Chlamydia, 128 COVID-19, 125 Normal without infection, 2 General Pneumonia, and 17 Streptococcus
Each X-Ray Image has been reflected as one record of features (PCA or HOG). All records (X-Ray Images) are labelled in separate file
To use this dataset, cite the following paper:

Mohamed Ali, S., Alsaeedi, A., Al-Shammary, D., Alsaeedi, H. and Abid, H., 2021. Efficient intelligent system for diagnosis pneumonia (SARS-COVID19) in X-Ray images empowered with initial clustering. Indonesian Journal of Electrical Engineering and Computer Science, 22(1), p.241.
