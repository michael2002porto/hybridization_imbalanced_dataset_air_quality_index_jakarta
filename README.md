# Summary Dataset:
- **BAIK** = 1054
- **SEDANG** = 3065 → undersampling (ENN) = 1000
- **TIDAK SEHAT** = 154 → oversampling (SMOTE) = 5000 → undersampling (ENN) = 1000
- **TIDAK ADA DATA** = 110 → hapus

# preprocessed_ispu_dki1.csv
- BAIK = 928
- SEDANG = 2877 → ENN = 1000
- TIDAK SEHAT = 145 → SMOTE = 5000 → ENN = 1000

# resampled_ispu_dki1.csv
- BAIK = 928
- SEDANG = 1000
- TIDAK SEHAT = 924

Resampled dataset shape (ENN) [('BAIK', 928), ('SEDANG', 1000), ('TIDAK SEHAT', 145)]
Resampled dataset shape (SMOTE) [('BAIK', 928), ('SEDANG', 1000), ('TIDAK SEHAT', 2800)]
Resampled dataset shape (ENN) [('BAIK', 928), ('SEDANG', 1000), ('TIDAK SEHAT', 924)]