<div style="text-align: center;">

# Perbedaan Kedua Data

</div>

<div style="text-align: justify;">

## Data Import :

- Pada **Guided_4**, data yang diimport adalah `train_features` dan `train_labels`, lalu digabungkan menjadi dataframe `train`.
- Pada **Unguided_4**, data yang diimport adalah `test_features` dan `test_labels`, lalu digabungkan menjadi dataframe `test`.

## Informasi Data :

- **Guided_4 (train data)** memiliki 3817 baris dan 17 kolom. Kolom yang ada mencakup fitur seperti **tahun kelahiran, pendidikan, status pernikahan, pendapatan**, dan berbagai kategori belanja serta jumlah promosi.
- **Unguided_4 (test data)** memiliki 3818 baris dan 18 kolom. Terdapat kolom tambahan **ID** yang tidak ada pada data train, namun sebagian besar kolom lainnya mirip dengan data train, seperti **pendidikan, status pernikahan, pendapatan, keluhan**, dan lain-lain.

## Kolom Yang Hilang :

- Beberapa kolom pada kedua dataset mengandung nilai yang hilang (missing values), seperti **pendidikan, status pernikahan, pendapatan**, dan kategori belanja lainnya. Namun, jumlah missing values dan distribusi antara train dan test sedikit berbeda.
- Di data test, terdapat kolom **tanggal_menjadi_anggota** dengan lebih banyak nilai kosong dibandingkan data train.

Berdasarkan perbandingan tersebut, dapat disimpulkan bahwa meskipun kedua data memiliki struktur yang serupa, terdapat beberapa perbedaan, terutama terkait jumlah kolom dan missing values. Kolom **ID** juga hanya ada di data test.

</div>