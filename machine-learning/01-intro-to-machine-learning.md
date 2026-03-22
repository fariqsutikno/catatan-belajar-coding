# Intro to Machine Learning

## Apa Itu Machine Learning?

Menurut Google, ML is the **process of training** a piece of software, called a **model**, to make useful **predictions** or generate content (like text, images, audio, or video) from data. 

Atau jika kita terjemahkan, ML adalah **proses melatih** sebuah software, yang disebut **model**, untuk membuat **prediksi** yang berguna atau membuat konten (seperti teks, gambar, audio, atau video) dari data.

Kata kuncinya terletak di: proses melatih, model, dan prediksi. Yang mana, berarti machine learning itu proses untuk melatih model itu.

### Apa Itu Model?
Adapun model itu simpelnya, hasil belajar yang sudah disimpan, dari semua pola yang dipelajari dari data, kemudian dikemas menjadi sesuatu yang bisa langsung dipakai untuk memprediksi hal baru nantinya.

Dalam supervised ML: Model akan mengambil contoh sebagai input, kemudian menyimpulkan prediksi sebagai output.

Adapun dalam unsupervised ML: model akan memetakan contoh input ke kelompok yang paling sesuai.


#### Bagaimana cara kita memahami pengertian model menurut Google?

Menurut Google, model secara umum adalah konstruksi matematika apa pun yang memproses data input dan menampilkan output. Singkatnya, model adalah **struktur + kumpulan parameter** yang bekerja sama untuk membuat prediksi.

Konkretnya, model itu dasarnya kayak rumus matematika dengan variabel yang belum diisi:
> harga = (a × luas) + b

Strukturnya sudah ada. Tapi nilai a dan b (yang disebut parameter atau bobot) itu masih kosong alias random di awal.

Nah, proses **melatih model** maksudnya adalah mencari nilai a dan b yang paling pas, supaya prediksinya akurat.

Misalnya, setelah training, mesin menemukan bahwa **a = 5 juta** dan **b = 10 juta**. Maka, kalau ada user minta prediksi harga rumah 200m^2, mesin tinggal masukkan ke rumus aja:

> harga = (5.000.000 × 200) + 10.000.000 = Rp1.010.000.000

Nah di sini, model sebelum dan sesudah training bukan model yang berbeda. Strukturnya sama, tapi parameternya sudah terisi optimal.

> **Penting untuk dicatat!**
> 
> Parameter tidak berdiri sendiri. Nilai a = 5 juta tidak ada artinya tanpa tahu ia masuk ke rumus mana.
> Makanya, ``model = struktur + parameter``, keduanya adalah satu kesatuan yang tak terpisahkan.

Agar model tersebut dapat tetap relevan seiring waktu, ia perlu terus dilatih ulang dengan data baru. Proses inilah yang disebut sebagai machine learning.

So, melatih model itu maksudnya menyesuaikan parameter sampai hasil prediksinya seakurat mungkin. Dan itu semua dilakukan otomatis dengan matematika, bukan manual satu per satu. Inilah yang menyebabkan machine learning tampak ajaib.

---

## Lain - Lain
### To Do List
-[] Apa bedanya parameter dan hyperparameter?
-[] Kenapa model bisa "salah" meskipun sudah ditraining

### Referensi
- [Machine Learning Learning Course by Google](https://developers.google.com/machine-learning/intro-to-ml/what-is-ml?hl=id)
- [Guide to Machine Learning 2026 by IBM](https://www.ibm.com/id-id/think/machine-learning)
- [What Is Machine Learning - Amazon AWS](https://aws.amazon.com/what-is/machine-learning/)
- [What Is Machine Learning - Google Cloud](https://cloud.google.com/learn/what-is-machine-learning)
- [What Is Machine Learning - Datacamp](https://www.datacamp.com/blog/what-is-machine-learning)