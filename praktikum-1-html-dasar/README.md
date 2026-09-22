# Praktikum 1 - HTML Dasar

# Identitas

Nama: Elisia Putri Sarmelinda  
NIM: 312510456  
Program Studi: Teknik Informatika  
Universitas: Universitas Pelita Bangsa  


## Jawaban Pertanyaan

 1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?
`<!DOCTYPE html>` digunakan untuk menunjukkan kepada browser bahwa dokumen tersebut menggunakan standar HTML5. Dengan adanya deklarasi ini, browser dapat menampilkan halaman sesuai dengan aturan HTML5.

2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
Tag merupakan penanda yang digunakan dalam HTML, seperti `<p>` sebagai tag pembuka dan `</p>` sebagai tag penutup. Elemen merupakan satu kesatuan yang terdiri dari tag pembuka, isi, dan tag penutup, contohnya `<p>Isi</p>`. Sedangkan atribut adalah informasi tambahan yang ditambahkan pada tag pembuka, misalnya `src` pada `<img src="foto.jpg">`.

3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.
`<p>` digunakan untuk membuat sebuah paragraf baru, sedangkan `<br>` digunakan untuk berpindah ke baris berikutnya tanpa membuat paragraf baru. Jadi, `<p>` digunakan ketika ingin membuat bagian teks sebagai paragraf, sedangkan `<br>` hanya digunakan untuk membuat pergantian baris.

4. Apa fungsi atribut `href` pada tag `<a>`?
Atribut `href` berfungsi untuk menentukan tujuan dari sebuah link. Tujuannya dapat berupa alamat website atau file HTML lain yang akan dibuka ketika link tersebut diklik.

5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
Hyperlink internal digunakan untuk menghubungkan halaman yang masih berada di dalam satu proyek, misalnya dari `index.html` menuju `halaman2.html`. Sedangkan hyperlink eksternal digunakan untuk mengarahkan pengguna ke website lain yang berada di luar proyek, biasanya menggunakan alamat URL lengkap.

6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?
Atribut `src` digunakan untuk menentukan lokasi file gambar yang ingin ditampilkan pada halaman web. Sedangkan `alt` berisi teks alternatif yang dapat digunakan untuk menjelaskan gambar ketika gambar tidak berhasil ditampilkan, serta membantu pengguna yang menggunakan pembaca layar.

7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?
`<ul>` atau *unordered list* digunakan untuk membuat daftar yang tidak memiliki urutan tertentu dan biasanya ditampilkan dengan tanda bullet. Sementara itu, `<ol>` atau *ordered list* digunakan untuk membuat daftar yang memiliki urutan dan biasanya ditampilkan menggunakan angka.

8. Apa yang terjadi jika path gambar pada atribut `src` salah?
Jika lokasi atau path gambar yang ditulis pada atribut `src` tidak benar, browser tidak dapat menemukan gambar sehingga gambar tidak akan ditampilkan. Jika atribut `alt` tersedia, teks alternatif tersebut dapat ditampilkan sebagai pengganti keterangan gambar.

9. Mengapa struktur heading `<h1>` sampai `<h6>` perlu digunakan secara terstruktur?
Heading digunakan untuk menunjukkan tingkatan judul dalam sebuah halaman web. `<h1>` biasanya digunakan sebagai judul utama, kemudian `<h2>` hingga `<h6>` digunakan untuk subjudul dengan tingkatan yang lebih rendah. Penggunaan heading yang teratur membuat struktur halaman lebih mudah dipahami oleh pembaca dan juga membantu mesin pencari serta teknologi pembaca layar memahami isi halaman.

10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?
Komentar digunakan untuk memberikan keterangan atau catatan di dalam kode HTML tanpa menampilkannya pada halaman web. Komentar juga dapat digunakan untuk menonaktifkan sementara bagian kode tertentu tanpa harus menghapusnya.


## Deskripsi Praktikum

Praktikum ini membahas dasar-dasar HTML menggunakan Visual Studio Code. Pada praktikum ini dibuat halaman profil mahasiswa dan halaman kedua untuk mempelajari struktur HTML, gambar, hyperlink, paragraf, formatting teks, list, dan anchor.


# Langkah-Langkah Praktikum

# 1. Membuat Struktur Dasar HTML

Langkah pertama adalah membuat file `index.html` sebagai halaman utama. File HTML dibuat menggunakan struktur dasar HTML yang terdiri dari `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`.

# 2. Membuat Navigasi

Selanjutnya dibuat navigasi menggunakan tag `<nav>` dan `<a>`. Navigasi berisi link menuju halaman utama, halaman kedua, dan website eksternal.

# 3. Membuat Judul dan Menambahkan Foto

Kemudian dibuat judul utama menggunakan tag `<h1>` dan menambahkan foto profil menggunakan tag `<img>`. Foto yang digunakan adalah `elphoto.png`.

# 4. Membuat Data Diri

Pada halaman utama dibuat bagian Data Diri yang berisi nama, NIM, universitas, dan program studi.

# 5. Membuat Paragraf

Selanjutnya dibuat dua paragraf yang menjelaskan tentang pembelajaran HTML dasar dan fungsi HTML dalam membuat struktur sebuah halaman web.

# 6. Membuat Formatting Teks

Pada praktikum dibuat beberapa contoh formatting teks menggunakan HTML, seperti teks tebal, teks miring, highlight, teks berukuran kecil, teks yang dihapus, teks yang disisipkan, subscript, dan superscript.

## 7. Membuat Daftar Keahlian

Selanjutnya dibuat bagian Keahlian menggunakan unordered list atau `<ul>`. Keahlian yang ditampilkan yaitu HTML dasar, Microsoft Office, dan Design sederhana.

## 8. Membuat Target Belajar

Kemudian dibuat bagian Target Belajar menggunakan ordered list atau `<ol>`. Target belajar yang dibuat yaitu memahami struktur HTML, mempelajari CSS, dan mempelajari JavaScript.

# 9. Membuat Anchor

Pada bagian akhir halaman dibuat anchor menggunakan atribut `id`. Anchor digunakan untuk menuju bagian tertentu pada halaman HTML.

# 10. Membuat Halaman 2

Selanjutnya dibuat file `halaman2.html` sebagai halaman kedua. Halaman ini digunakan untuk mempelajari penggunaan hyperlink internal dan hyperlink eksternal.

# 11. Membuat Hyperlink Internal

Hyperlink internal digunakan untuk berpindah dari halaman kedua kembali ke halaman utama yang berada dalam folder proyek yang sama.

## 12. Membuat Hyperlink Eksternal

Hyperlink eksternal digunakan untuk membuka website yang berada di luar proyek. Pada praktikum ini hyperlink eksternal mengarah ke Website Universitas Pelita Bangsa.

# Kesimpulan

Pada praktikum ini telah dipelajari dasar-dasar HTML, mulai dari membuat struktur dokumen HTML, menambahkan gambar, membuat paragraf, melakukan formatting teks, membuat list, menggunakan anchor, serta membuat hyperlink internal dan eksternal.

Melalui praktikum ini dapat dipahami bahwa HTML digunakan untuk menyusun struktur dan konten dasar pada sebuah halaman web.