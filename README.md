# PYTN_Assgn_03_04_Krisna-WInar-Setiawan
## Data Overview

Project Overview
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

There are four datasets:

bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014] <br>
bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.<br>
bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs).<br>
bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs).
The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM).<br>

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).
## Analisis Keseluruhan
Untuk Hasil akhiir Classification algoritma Logistic Regression memiliki performa yang lebih baik dari yang algoritma yang lain seperti SVM, KNN, dan DT. Hasil classification diatas dapat dilihat bahwa proses klasifikasi dengan dataset imbalanced menghasilkan accuracy sebesar 0.91. Serta hasil klasifikasi setelah dilakukan balancing dataset menggunakan metode oversampling SMOTE menghasilkan accuracy sebesar 0.84.
