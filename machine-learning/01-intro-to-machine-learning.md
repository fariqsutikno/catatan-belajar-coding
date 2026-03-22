# Catatan Belajar Machine Learning

## Pengantar Machine Learning

### Apa Itu Machine Learning?

Menurut Google, ML is the **process of training** a piece of software, called a **model**, to make useful **predictions** or generate content (like text, images, audio, or video) from data.

Kata kuncinya terletak di: proses melatih, model, dan prediksi. Yang mana, berarti machine learning itu proses untuk melatih model itu. 

Mungkin kalau kita ibaratkan, model itu bagaikan otak manusia, yang mampu membuahkan sebuah pikiran berupa prediksi ataupun konten tertentu.

Adapun model itu simpelnya, hasil belajar yang sudah disimpan, dari semua pola yang dipelajari dari data, kemudian dikemas menjadi sesuatu yang bisa langsung dipakai untuk memprediksi hal baru nantinya.

Dalam supervised ML: Model akan mengambil contoh sebagai input, kemudian menyimpulkan prediksi sebagai output.

Adapun dalam unsupervised ML: model akan memetakan contoh input ke kelompok yang paling sesuai.


**Bagaimana cara kita memahami pengertian model menurut Google?**

Menurut Google, model secara umum adalah konstruksi matematika apa pun yang memproses data input dan menampilkan output. Dengan kata lain, model adalah kumpulan parameter dan struktur yang diperlukan agar sistem dapat membuat prediksi.

Oke, gini gambarannya, sebenarnya, model itu dasarnya hanya fungsi matematika:
f(x) = y
Dengan fungsi ini, input akan masuk, dan akan keluar menjadi output.

Kemudian, ia dapat berkembang lebih luas, yaitu kumpulan parameter.
Yang tadinya rumusnya adalah f(x) = y. Kemudian ia menjadi y = ax + b.
- y berperan sebagai output (hasil prediksi)
- x berperan sebagai input (data)
- a dan b ini yang dimaksud dari kumpulan parameter.

Nilai a dan b ini yang dipelajari dari training. Setelah training selesai, nilai a dan b itu kemudian dibekukan dan disimpan, dan inilah yang disebut sebagai model.

Contoh implementasinya:

Bayangkan kamu mau membuat rumus untuk menebak harga rumah:
> harga = (a x luas) + b

Sebelum training, kita ga tahu, berapa nilai a dan b.
Namun setelah training, machine akan belajar berapa nilai yang tepat untuk a dan b. Misalkan, a nilainya 5 juta, dan b nilainya 10 juta.

Sehingga jika kemudian di suatu hari, user meminta sistem untuk membuat prediksi dari harga rumah dengan luas 200m2, maka ia akan memasukkannya ke dalam rumus tersebut. 

Nah agar rumus tersebut tetap relevan dengan situasi yang ada, maka ia harus rajin ditraining. Proses training inilah yang disebut sebagai machine learning.

### To Do List
-[] Apa bedanya parameter dan hyperparameter?
-[] Kenapa model bisa "salah" meskipun sudah ditraining

### Referensi
- [Machine Learning Learning Course by Google](https://developers.google.com/machine-learning/intro-to-ml/what-is-ml?hl=id)
- [Guide to Machine Learning 2026 by IBM](https://www.ibm.com/id-id/think/machine-learning)
- [What Is Machine Learning - Amazon AWS](https://aws.amazon.com/what-is/machine-learning/)
- [What Is Machine Learning - Google Cloud](https://cloud.google.com/learn/what-is-machine-learning)
- [What Is Machine Learning - Datacamp](https://www.datacamp.com/blog/what-is-machine-learning)