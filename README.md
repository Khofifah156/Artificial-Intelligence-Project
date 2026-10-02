# Prediksi Penyakit Ginjal Kronis Menggunakan Machine Learning Berdasarkan Indikator Kesehatan

Project ini membahas penerapan Machine Learning untuk mengklasifikasikan kondisi Chronic Kidney Disease (CKD) dan Non-CKD berdasarkan berbagai indikator kesehatan. Dataset yang digunakan terdiri dari 11.934 data dengan 29 fitur dan target klasifikasi CKD/Non-CKD.

Data melalui tahap cleaning, preprocessing, encoding, scaling, serta pembagian data training dan testing. Beberapa algoritma dibandingkan, yaitu Logistic Regression, Random Forest, XGBoost, dan LightGBM. Model kemudian dievaluasi menggunakan cross-validation dan dilanjutkan dengan hyperparameter tuning untuk mendapatkan model akhir.
Hasil akhir menggunakan LightGBM sebagai model final dan dilengkapi analisis feature importance serta SHAP untuk melihat fitur yang berpengaruh terhadap prediksi. Model kemudian diimplementasikan ke dalam web CKD Predictor sebagai alat bantu prediksi awal.

## Tools

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* LightGBM
* Matplotlib
* Seaborn
* SHAP
* Google Colab
* Machine Learning
