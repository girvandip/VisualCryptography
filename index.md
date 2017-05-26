Keamanan informasi telah menjadi suatu prioritas utama bagi pengguna teknologi digital pada era modern ini. Salah satu cara untuk mengamankan informasi tersebut adalah dengan menggunakan kriptografi. Kriptografi berasal dari bahasa Yunani yang terdiri atas dua suku kata yaitu kripto dan graphia. Kripto artinya memyembunyikan, sementara graphia artinya tulisan. Kriptografi adalah ilmu yang mempelajari tentang cara mengamankan informasi dengan teknik-teknik matematika tertentu. Inti dari teknik kriptografi adalah enkripsi dan dekripsi, dimana enkripsi adalah pengubahan informasi yang akan dikirimkan menjadi sesuatu yang tidak bermakna dan dekripsi adalah mengembalikan informasi yang telah dienkripsi menjadi suatu informasi yang bermakna. Informasi dapat diamankan dapat berupa pesan teks, suara, gambar, maupun video.

## Visual Cryptography

Kriptografi visual adalah suatu teknik yang digunakan untuk menyembunyikan informasi yang berupa gambar. Teknik kriptografi ini pertama kali ditemukan oleh Moni Naor dan Adi Shamir pada tahun 1994. Mereka mendemonstrasikan teknik enkripsi dengan cara membagi suatu gambar menjadi n share (bagian) sehingga hanya seseorang yang memiliki share sebanyak n yang dapat mendekripsikan gambar tersebut. Dalam teknik ini tidak dibutuhkan komputasi untuk melakukan dekripsi gambar, tetapi hanya dibutuhkan indera visual manusia. Setiap share akan dicetak dengan tingkat transparansi atau distribusi warna pixel yang berbeda-beda sehingga dekripsi dilakukan dengan cara menumpuk kumpulan share tersebut menjadi satu. Pesan yang disampaikan akan langsung terlihat jelas pada saat sekumpulan share tersebut disatukan. Untuk meningkatkan keamanan kriptografi visual, enkripsi biasanya dilakukan oleh pihak ketiga yang disebut dealer. 

Salah satu contoh sederhana kriptografi visual dapat dilihat dari gambar dibawah ini. Contoh ini adalah sebuah gambar biner yang hanya memiliki dua warna, yaitu hitam dan putih. Ada dua buah share yang dibentuk dari sebuah gambar yang dienkripsi. Masing-masing share tidak menunjukkan kemiripan apapun dengan gambar yang ingin  disampaikan. Hanya dengan menyatukan kedua share tersebut, pesan yang dienkripsi dapat dilihat dengan jelas.  

Dalam perkembangannya, kriptografi dapat pula mengolah gambar abu-abu (grayscale) dan juga gambar berwarna. Namun, perkembangan yang paling signifikan adalah digunakannya steganografi. Steganografi adalah sebuah teknik menyembunyikan suatu pesan rahasia dalam suatu pesan biasa yang dapat berupa teks, gambar, audio, video, dan berkas lainnya. Dalam lingkup kriptografi visual, steganografi digunakan untuk menyembunyikan pesan dalam suatu gambar atau dalam gabungan beberapa gambar.

Salah satu contoh aplikasi steganografi dapat dilihat pada gambar disamping. Ada 3 buah gambar, dimana gambar a dan b adalah gambar yang akan dienkripsi menjadi beberapa share dan gambar c adalah gambar yang merupakan pesan tersembunyi. Gambar d dan e adalah hasil gabungan dari share yang dibentuk pada saat enkripsi. Namun, tidak seperti kriptografi visual yang biasanya, ketika gambar d dan e digabungkan, maka akan menghasilkan gambar f yang merupakan pesan tersembunyi.

### Referensi

[1] https://en.wikipedia.org/wiki/Visual_cryptography
[2] http://www.datagenetics.com/blog/november32013/
[3] http://users.telenet.be/d.rijmenants/en/visualcrypto.htm
