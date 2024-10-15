| Elemen HTML                              | Fungsi                                                      | Contoh Penggunaan                                                                                             | Hasil                                               |
|------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| `<h1>...<h1>`                            | Menandai judul utama yang besar pada halaman. Biasanya digunakan untuk judul utama dari halaman atau bagian penting. | ```html<br>&lt;h1&gt;Judul Utama&lt;/h1&gt;<br>```                                                           | <h1>Judul Utama</h1>                               |
| `<h2>...<h2>`                            | Menandai judul tingkat kedua, sedikit lebih kecil dari `<h1>`. Biasanya digunakan untuk sub-judul dari bagian utama. | ```html<br>&lt;h2&gt;Sub Judul&lt;/h2&gt;<br>```                                                             | <h2>Sub Judul</h2>                                 |
| `<h3>...<h3>`                            | Menandai judul tingkat ketiga, lebih kecil dari `<h2>`. Digunakan untuk sub-bagian dari sub-judul. | ```html<br>&lt;h3&gt;Sub-sub Judul&lt;/h3&gt;<br>```                                                         | <h3>Sub-sub Judul</h3>                             |
| `<h4>...<h4>`                            | Menandai judul tingkat keempat, lebih kecil dari `<h3>`. Digunakan untuk sub-sub-bagian dari judul. | ```html<br>&lt;h4&gt;Judul Kecil&lt;/h4&gt;<br>```                                                           | <h4>Judul Kecil</h4>                               |
| `<h5>...<h5>`                            | Menandai judul tingkat kelima, lebih kecil dari `<h4>`. Biasanya digunakan untuk pembagian yang lebih mendetail. | ```html<br>&lt;h5&gt;Judul Sangat Kecil&lt;/h5&gt;<br>```                                                    | <h5>Judul Sangat Kecil</h5>                        |
| `<h6>...<h6>`                            | Menandai judul tingkat keenam, paling kecil dari semua judul. Digunakan untuk pembagian yang paling detail. | ```html<br>&lt;h6&gt;Judul Terakhir&lt;/h6&gt;<br>```                                                        | <h6>Judul Terakhir</h6>                            |
| `<p>...<p>`                              | Menandai paragraf teks. Digunakan untuk mengelompokkan teks menjadi bagian yang terpisah. | ```html<br>&lt;p&gt;Ini adalah paragraf.&lt;/p&gt;<br>```                                                     | <p>Ini adalah paragraf.</p>                        |
| `<a href="...">...<a>`                   | Menandai tautan ke halaman lain atau sumber lain. Atribut `href` menentukan URL tujuan. | ```html<br>&lt;a href="https://example.com"&gt;Kunjungi Situs&lt;/a&gt;<br>```                             | <a href="https://example.com">Kunjungi Situs</a>   |
| `<img src="..." alt="...">`              | Menyisipkan gambar ke halaman. Atribut `src` menentukan URL gambar, dan `alt` memberikan teks alternatif jika gambar tidak bisa ditampilkan. | ```html<br>&lt;img src="https://via.placeholder.com/150" alt="Contoh Gambar"&gt;<br>```                     | <img src="https://via.placeholder.com/150" alt="Contoh Gambar"> |
| `<ul><li>...<li></ul>`                   | Membuat daftar tanpa nomor. Setiap item daftar diletakkan dalam elemen `<li>`. | ```html<br>&lt;ul&gt;<br>&nbsp;&nbsp;&lt;li&gt;Item 1&lt;/li&gt;<br>&nbsp;&nbsp;&lt;li&gt;Item 2&lt;/li&gt;<br>&lt;/ul&gt;<br>``` | <ul><li>Item 1</li><li>Item 2</li></ul>            |
| `<ol><li>...<li></ol>`                   | Membuat daftar dengan nomor. Setiap item daftar diletakkan dalam elemen `<li>`. | ```html<br>&lt;ol&gt;<br>&nbsp;&nbsp;&lt;li&gt;Item 1&lt;/li&gt;<br>&nbsp;&nbsp;&lt;li&gt;Item 2&lt;/li&gt;<br>&lt;/ol&gt;<br>``` | <ol><li>Item 1</li><li>Item 2</li></ol>            |
| `<strong>...<strong>`                   | Menandai teks yang harus ditampilkan dalam bentuk tebal. Biasanya digunakan untuk memberikan penekanan pada teks. | ```html<br>&lt;strong&gt;Teks Tebal&lt;/strong&gt;<br>```                                                     | <strong>Teks Tebal</strong>                        |
| `<em>...<em>`                            | Menandai teks yang harus ditampilkan dalam bentuk miring. Biasanya digunakan untuk memberikan penekanan atau menunjukkan istilah. | ```html<br>&lt;em&gt;Teks Miring&lt;/em&gt;<br>```                                                            | <em>Teks Miring</em>                              |
| `<blockquote>...<blockquote>`            | Menandai kutipan dari sumber lain. Biasanya digunakan untuk kutipan panjang dari teks. | ```html<br>&lt;blockquote&gt;Ini adalah kutipan.&lt;/blockquote&gt;<br>```                                | <blockquote>Ini adalah kutipan.</blockquote>        |
| `<code>...<code>`                        | Menandai teks sebagai kode dalam baris. Biasanya digunakan untuk menampilkan potongan kode program. | ```html<br>&lt;code&gt;kode contoh&lt;/code&gt;<br>```                                                        | <code>kode contoh</code>                           |
| `<pre><code>...<code></pre>`             | Menandai blok kode. Menampilkan kode dengan format yang telah ditentukan dan menjaga spasi. | ```html<br>&lt;pre&gt;&lt;code&gt;Kode multi-baris&lt;/code&gt;&lt;/pre&gt;<br>```                          | <pre><code>Kode multi-baris</code></pre>           |
| `<table><tr><th>...<th></tr></table>`    | Membuat tabel. Elemen `<tr>` menandai baris, `<th>` menandai sel header, dan `<td>` menandai sel data. | ```html<br>&lt;table&gt;<br>&nbsp;&nbsp;&lt;tr&gt;<br>&nbsp;&nbsp;&nbsp;&nbsp;&lt;th&gt;Header&lt;/th&gt;<br>&nbsp;&nbsp;&lt;/tr&gt;<br>&nbsp;&nbsp;&lt;tr&gt;<br>&nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt;Cell 1&lt;/td&gt;<br>&nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt;Cell 2&lt;/td&gt;<br>&nbsp;&nbsp;&lt;/tr&gt;<br>&lt;/table&gt;<br>``` | <table><tr><th>Header</th></tr><tr><td>Cell 1</td><td>Cell 2</td></tr></table> |
| `<hr>`                                  | Menyisipkan garis horizontal sebagai pemisah antar bagian. | ```html<br>&lt;hr&gt;<br>```                                                                                 | <hr>                                                |
| `<br>`                                  | Menyisipkan pemisah baris dalam teks. Digunakan untuk membuat jarak antar baris. | ```html<br>Line 1&lt;br&gt;Line 2<br>```                                                                    | Line 1<br>Line 2                                    |
| `<sup>...<sup>`                         | Menandai teks sebagai superscript, biasanya digunakan untuk menulis eksponen atau catatan kaki. | ```html<br>E=mc<sup>2</sup><br>```                                                                           | E=mc<sup>2</sup>                                   |
| `<sub>...<sub>`                         | Menandai teks sebagai subscript, biasanya digunakan untuk menulis indeks atau catatan bawah. | ```html<br>H<sub>2</sub>O<br>```                                                                             | H<sub>2</sub>O                                     |
| `<div>...<div>`                         | Membuat divisi atau bagian dalam halaman. Digunakan untuk mengelompokkan konten dan menerapkan gaya. | ```html<br>&lt;div&gt;Ini adalah div&lt;/div&gt;<br>```                                                     | <div>Ini adalah div</div>                           |
| `<span>...<span>`                       | Menandai bagian dari teks. Digunakan untuk menerapkan gaya pada teks tanpa mempengaruhi struktur. | ```html<br>&lt;span style="color: red;"&gt;Teks Merah&lt;/span&gt;<br>```                                  | <span style="color: red;">Teks Merah</span>        |
| `<iframe src="..." ...><iframe>`        | Menyisipkan konten dari sumber lain ke dalam halaman, seperti halaman web lain. | ```html<br>&lt;iframe src="https://example.com" width="300" height="200"&gt;&lt;/iframe&gt;<br>```         | <iframe src="https://example.com" width="300" height="200"></iframe> |
| `<input type="text">`                   | Membuat kotak input teks. Digunakan untuk menerima input dari pengguna. | ```html<br>&lt;input type="text" placeholder="Masukkan teks"&gt;<br>```                                    | <input type="text" placeholder="Masukkan teks">    |
| `<button>...<button>`                   | Membuat tombol yang dapat diklik untuk melakukan aksi atau mengirim data. | ```html<br>&lt;button&gt;Klik Saya&lt;/button&gt;<br>```                                                    | <button>Klik Saya</button>                        |
| `<form>...<form>`                       | Membuat formulir input data. Biasanya digunakan untuk mengumpulkan informasi dari pengguna. | ```html<br>&lt;form&gt;&lt;input type="text"&gt;&lt;button&gt;Kirim&lt;/button&gt;&lt;/form&gt;<br>```  | <form><input type="text"><button>Kirim</button></form> |
| `<select><option>...<option></select>`  | Membuat dropdown menu dengan pilihan yang dapat dipilih oleh pengguna. | ```html<br>&lt;select&gt;<br>&nbsp;&nbsp;&lt;option&gt;Pilihan 1&lt;/option&gt;<br>&nbsp;&nbsp;&lt;option&gt;Pilihan 2&lt;/option&gt;<br>&lt;/select&gt;<br>``` | <select><option>Pilihan 1</option><option>Pilihan 2</option></select> |
| `<textarea>...<textarea>`               | Membuat area input teks yang lebih besar dan dapat diisi dengan teks panjang. | ```html<br>&lt;textarea rows="4" cols="50"&gt;Teks panjang&lt;/textarea&gt;<br>```                        | <textarea rows="4" cols="50">Teks panjang</textarea>|
| `<label for="...">...<label>`           | Menyediakan label untuk elemen input. Atribut `for` menghubungkan label dengan elemen input tertentu. | ```html<br>&lt;label for="username"&gt;Nama Pengguna:&lt;/label&gt;&lt;input type="text" id="username"&gt;<br>``` | <label for="username">Nama Pengguna:</label><input type="text" id="username"> |
| `<fieldset>...<fieldset>`               | Mengelompokkan elemen-elemen dalam formulir. Biasanya digunakan bersama dengan `<legend>` untuk memberikan deskripsi grup. | ```html<br>&lt;fieldset&gt;&lt;legend&gt;Informasi Pribadi&lt;/legend&gt;&lt;input type="text"&gt;&lt;/fieldset&gt;<br>``` | <fieldset><legend>Informasi Pribadi</legend><input type="text"></fieldset> |
| `<script src="..."></script>`           | Menyisipkan atau merujuk file JavaScript untuk menjalankan kode di halaman. | ```html<br>&lt;script src="script.js"&gt;&lt;/script&gt;<br>```                                            | (Menjalankan kode JavaScript dari file `script.js`) |
| `<style>...<style>`                     | Menyisipkan CSS langsung ke dalam halaman HTML untuk mengatur gaya elemen. | ```html<br>&lt;style&gt;body { background-color: #f0f0f0; }&lt;/style&gt;<br>```                          | (Menerapkan CSS untuk latar belakang halaman)       |
| `<meta charset="...">`                  | Menentukan encoding karakter untuk halaman, memastikan karakter ditampilkan dengan benar. | ```html<br>&lt;meta charset="UTF-8"&gt;<br>```                                                              | (Mengatur encoding karakter halaman)               |
| `<link rel="stylesheet" href="...">`    | Menyisipkan file CSS eksternal untuk mengatur gaya halaman. | ```html<br>&lt;link rel="stylesheet" href="styles.css"&gt;<br>```                                          | (Menyambungkan file CSS `styles.css`)               |
| `<title>...<title>`                     | Menentukan judul halaman yang ditampilkan di tab browser atau jendela. | ```html<br>&lt;title&gt;Judul Halaman&lt;/title&gt;<br>```                                                  | (Menampilkan "Judul Halaman" di tab browser)       |
| `<meta name="description" content="...">` | Menyediakan deskripsi singkat tentang halaman yang digunakan oleh mesin pencari. | ```html<br>&lt;meta name="description" content="Deskripsi halaman"&gt;<br>```                             | (Menampilkan deskripsi untuk mesin pencari)        |
| `<meta name="viewport" content="...">`  | Mengatur bagaimana halaman ditampilkan di perangkat seluler dengan mengontrol lebar dan skala tampilan. | ```html<br>&lt;meta name="viewport" content="width=device-width, initial-scale=1"&gt;<br>```              | (Mengatur lebar tampilan untuk perangkat seluler)  |
| Elemen HTML                              | Fungsi                                                      | Contoh Penggunaan                                                                                             | Hasil                                               |
|------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| `<details>...<details>`                  | Menyediakan konten yang dapat diperluas atau diperkecil oleh pengguna. Biasanya digunakan untuk menampilkan informasi tambahan. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk melihat detail&lt;/summary&gt;&lt;p&gt;Ini adalah detail&lt;/p&gt;&lt;/details&gt;<br>``` | <details><summary>Klik untuk melihat detail</summary><p>Ini adalah detail</p></details> |
| `<summary>...<summary>`                  | Menyediakan ringkasan untuk elemen `<details>`. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk melihat detail&lt;/summary&gt;&lt;/details&gt;<br>``` | <details><summary>Klik untuk melihat detail</summary></details> |
| `<main>...<main>`                       | Menandai konten utama dari halaman, biasanya berisi konten utama dari dokumen. | ```html<br>&lt;main&gt;&lt;h1&gt;Konten Utama&lt;/h1&gt;&lt;p&gt;Ini adalah konten utama&lt;/p&gt;&lt;/main&gt;<br>``` | <main><h1>Konten Utama</h1><p>Ini adalah konten utama</p></main> |
| `<section>...<section>`                 | Menandai bagian-bagian terpisah dari konten halaman, sering kali digunakan untuk grup konten terkait. | ```html<br>&lt;section&gt;&lt;h2&gt;Bagian 1&lt;/h2&gt;&lt;p&gt;Ini adalah bagian 1&lt;/p&gt;&lt;/section&gt;<br>``` | <section><h2>Bagian 1</h2><p>Ini adalah bagian 1</p></section> |
| `<article>...<article>`                 | Menandai konten independen dan mandiri yang dapat didistribusikan atau dipublish secara terpisah. | ```html<br>&lt;article&gt;&lt;h2&gt;Artikel 1&lt;/h2&gt;&lt;p&gt;Ini adalah artikel 1&lt;/p&gt;&lt;/article&gt;<br>``` | <article><h2>Artikel 1</h2><p>Ini adalah artikel 1</p></article> |
| `<aside>...<aside>`                     | Menandai konten yang dapat dianggap sebagai informasi tambahan atau sampingan dari konten utama. | ```html<br>&lt;aside&gt;&lt;p&gt;Ini adalah informasi sampingan&lt;/p&gt;&lt;/aside&gt;<br>```             | <aside><p>Ini adalah informasi sampingan</p></aside> |
| `<footer>...<footer>`                   | Menandai bagian bawah dari halaman atau bagian halaman yang berisi informasi penutup atau kontak. | ```html<br>&lt;footer&gt;&lt;p&gt;Hak cipta &copy; 2024&lt;/p&gt;&lt;/footer&gt;<br>```                     | <footer><p>Hak cipta © 2024</p></footer>           |
| `<header>...<header>`                   | Menandai bagian atas dari halaman atau bagian halaman yang berisi informasi pengantar atau navigasi. | ```html<br>&lt;header&gt;&lt;h1&gt;Judul Halaman&lt;/h1&gt;&lt;nav&gt;&lt;a href="#home"&gt;Beranda&lt;/a&gt;&lt;/nav&gt;&lt;/header&gt;<br>``` | <header><h1>Judul Halaman</h1><nav><a href="#home">Beranda</a></nav></header> |
| `<nav>...<nav>`                         | Menandai bagian yang berisi link navigasi ke bagian lain dari halaman atau situs. | ```html<br>&lt;nav&gt;&lt;a href="#home"&gt;Beranda&lt;/a&gt;&lt;a href="#about"&gt;Tentang&lt;/a&gt;&lt;/nav&gt;<br>``` | <nav><a href="#home">Beranda</a><a href="#about">Tentang</a></nav> |
| `<figure>...<figure>`                   | Menandai konten yang diatur secara mandiri, seperti gambar, diagram, atau tabel, dengan caption opsional. | ```html<br>&lt;figure&gt;&lt;img src="image.jpg" alt="Gambar"&gt;&lt;figcaption&gt;Deskripsi gambar&lt;/figcaption&gt;&lt;/figure&gt;<br>``` | <figure><img src="image.jpg" alt="Gambar"><figcaption>Deskripsi gambar</figcaption></figure> |
| `<figcaption>...<figcaption>`           | Menyediakan caption atau deskripsi untuk elemen `<figure>`. | ```html<br>&lt;figure&gt;&lt;img src="image.jpg" alt="Gambar"&gt;&lt;figcaption&gt;Deskripsi gambar&lt;/figcaption&gt;&lt;/figure&gt;<br>``` | <figcaption>Deskripsi gambar</figcaption>          |
| `<mark>...<mark>`                       | Menandai teks yang relevan atau yang perlu disorot. | ```html<br>&lt;mark&gt;Teks yang disorot&lt;/mark&gt;<br>```                                                | <mark>Teks yang disorot</mark>                    |
| `<ruby>...<ruby>`                       | Menandai teks dengan anotasi, sering digunakan untuk menandai elemen bahasa atau pengucapan. | ```html<br>&lt;ruby&gt;漢字&lt;rp&gt;( &lt;/rp&gt;&lt;rt&gt;kanji&lt;/rt&gt;&lt;rp&gt;)&lt;/rp&gt;&lt;/ruby&gt;<br>``` | <ruby>漢字<rp>(<rt>kanji</rt>)</rp></ruby>         |
| `<rp>...<rp>`                           | Menyediakan tanda kurung untuk anotasi teks `<ruby>`. Biasanya digunakan sebagai pengganti jika anotasi tidak didukung. | ```html<br>&lt;ruby&gt;漢字&lt;rp&gt;( &lt;/rp&gt;&lt;rt&gt;kanji&lt;/rt&gt;&lt;rp&gt;)&lt;/rp&gt;&lt;/ruby&gt;<br>``` | <rp>(</rp>kanji<rp>)</rp>                          |
| `<rt>...<rt>`                           | Menyediakan teks anotasi untuk elemen `<ruby>`. Biasanya digunakan untuk menampilkan pengucapan atau transliterasi. | ```html<br>&lt;ruby&gt;漢字&lt;rp&gt;( &lt;/rp&gt;&lt;rt&gt;kanji&lt;/rt&gt;&lt;rp&gt;)&lt;/rp&gt;&lt;/ruby&gt;<br>``` | <rt>kanji</rt>                                    |
| `<bdo dir="...">...<bdo>`               | Menandai teks untuk dibaca dari arah yang berbeda, seperti RTL (Right-To-Left) atau LTR (Left-To-Right). | ```html<br>&lt;bdo dir="rtl"&gt;Tekst dari kanan ke kiri&lt;/bdo&gt;<br>```                              | <bdo dir="rtl">Tekst dari kanan ke kiri</bdo>    |
| `<bdi>...<bdi>`                         | Menandai bagian teks yang perlu dipertahankan arah bacanya secara independen dari teks di sekitarnya. | ```html<br>&lt;bdi&gt;Teks yang tidak mengikuti arah&lt;/bdi&gt;<br>```                                    | <bdi>Teks yang tidak mengikuti arah</bdi>        |
| `<data value="...">...<data>`           | Menyediakan data terstruktur untuk elemen tertentu, biasanya digunakan bersama dengan elemen lain seperti `<time>`. | ```html<br>&lt;data value="2024-08-10"&gt;10 Agustus 2024&lt;/data&gt;<br>```                              | <data value="2024-08-10">10 Agustus 2024</data>   |
| `<time datetime="...">...<time>`         | Menyediakan informasi tanggal dan waktu, biasanya dengan atribut `datetime` untuk format standar. | ```html<br>&lt;time datetime="2024-08-10"&gt;10 Agustus 2024&lt;/time&gt;<br>```                           | <time datetime="2024-08-10">10 Agustus 2024</time> |
| `<address>...<address>`                 | Menyediakan informasi kontak atau alamat untuk seseorang atau organisasi. | ```html<br>&lt;address&gt;123 Jalan Utama, Kota A&lt;/address&gt;<br>```                                   | <address>123 Jalan Utama, Kota A</address>       |
| `<colgroup><col>...<colgroup>`           | Menandai grup kolom dalam tabel untuk penerapan gaya atau pengaturan. | ```html<br>&lt;table&gt;&lt;colgroup&gt;&lt;col style="background-color: #f0f0f0"&gt;&lt;/col&gt;&lt;/colgroup&gt;&lt;/table&gt;<br>``` | (Mengatur gaya untuk grup kolom dalam tabel)      |
| `<caption>...<caption>`                 | Menyediakan judul atau keterangan untuk elemen tabel. | ```html<br>&lt;table&gt;&lt;caption&gt;Judul Tabel&lt;/caption&gt;&lt;/table&gt;<br>```                    | <caption>Judul Tabel</caption>                    |
| `<tbody>...<tbody>`                     | Menandai bagian tubuh dari tabel, berisi baris-baris data. | ```html<br>&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;Data&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt;<br>``` | <tbody><tr><td>Data</td></tr></tbody>              |
| `<thead>...<thead>`                     | Menandai bagian kepala tabel, berisi baris header. | ```html<br>&lt;table&gt;&lt;thead&gt;&lt;tr&gt;&lt;th&gt;Header&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;&lt;/table&gt;<br>``` | <thead><tr><th>Header</th></tr></thead>            |
| `<tfoot>...<tfoot>`                     | Menandai bagian kaki tabel, berisi informasi atau total. | ```html<br>&lt;table&gt;&lt;tfoot&gt;&lt;tr&gt;&lt;td&gt;Total&lt;/td&gt;&lt;/tr&gt;&lt;/tfoot&gt;&lt;/table&gt;<br>``` | <tfoot><tr><td>Total</td></tr></tfoot>            |
| `<template>...<template>`               | Menyediakan template yang tidak ditampilkan secara langsung, tetapi dapat digunakan dengan JavaScript untuk menyisipkan konten dinamis. | ```html<br>&lt;template id="my-template"&gt;&lt;p&gt;Ini adalah template&lt;/p&gt;&lt;/template&gt;<br>``` | (Template tidak terlihat, digunakan dengan JavaScript) |
| `<svg>...<svg>`                         | Menyediakan area untuk grafik vektor yang dapat diperbesar dan diperkecil tanpa kehilangan kualitas. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/></svg> |
| `<path d="...">...<path>`               | Menggambar bentuk-bentuk kompleks dalam SVG dengan mendefinisikan jalur atau garis. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;path d="M10 80 Q 95 10 180 80 T 350 80" stroke="black" fill="transparent"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><path d="M10 80 Q 95 10 180 80 T 350 80" stroke="black" fill="transparent"/></svg> |
| `<circle cx="...">...<circle>`         | Menggambar lingkaran dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/></svg> |
| `<rect width="...">...<rect>`           | Menggambar persegi panjang dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;rect width="90" height="90" stroke="black" stroke-width="3" fill="blue"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><rect width="90" height="90" stroke="black" stroke-width="3" fill="blue"/></svg> |
| `<line x1="...">...<line>`              | Menggambar garis dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;line x1="10" y1="10" x2="90" y2="90" stroke="black" stroke-width="2"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><line x1="10" y1="10" x2="90" y2="90" stroke="black" stroke-width="2"/></svg> |
| `<polygon points="...">...<polygon>`   | Menggambar bentuk poligon dengan beberapa sisi dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;polygon points="50,15 90,80 10,80" stroke="black" stroke-width="1" fill="green"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><polygon points="50,15 90,80 10,80" stroke="black" stroke-width="1" fill="green"/></svg> |
| `<polyline points="...">...<polyline>` | Menggambar serangkaian garis yang terhubung dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;polyline points="10,10 50,50 90,10" stroke="black" stroke-width="2" fill="none"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><polyline points="10,10 50,50 90,10" stroke="black" stroke-width="2" fill="none"/></svg> |
| `<stop offset="...">...<stop>`         | Menyediakan titik berhenti untuk gradien warna dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;defs&gt;&lt;linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%"&gt;&lt;stop offset="0%" style="stop-color:rgb(255,255,255);stop-opacity:1" /&gt;&lt;stop offset="100%" style="stop-color:rgb(0,0,0);stop-opacity:1" /&gt;&lt;/linearGradient&gt;&lt;/defs&gt;&lt;rect width="100" height="100" fill="url(#grad1)"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><defs><linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" style="stop-color:rgb(255,255,255);stop-opacity:1" /><stop offset="100%" style="stop-color:rgb(0,0,0);stop-opacity:1" /></linearGradient></defs><rect width="100" height="100" fill="url(#grad1)"/></svg> |
| Elemen HTML                              | Fungsi                                                      | Contoh Penggunaan                                                                                             | Hasil                                               |
|------------------------------------------|-------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| `<datalist>...<datalist>`                | Menyediakan daftar opsi untuk elemen input dengan tipe `text`. | ```html<br>&lt;input list="fruits"&gt;&lt;datalist id="fruits"&gt;&lt;option value="Apple"&gt;&lt;option value="Banana"&gt;&lt;/datalist&gt;<br>``` | <input list="fruits"><datalist id="fruits"><option value="Apple"><option value="Banana"></datalist> |
| `<output>...<output>`                   | Menyediakan tempat untuk menampilkan hasil kalkulasi atau hasil dari operasi JavaScript. | ```html<br>&lt;form oninput="result.value=parseInt(a.value)+parseInt(b.value)"&gt;&lt;input type="range" id="a" value="50"&gt;&lt;input type="range" id="b" value="50"&gt;&lt;output name="result"&gt;100&lt;/output&gt;&lt;/form&gt;<br>``` | <form oninput="result.value=parseInt(a.value)+parseInt(b.value)"><input type="range" id="a" value="50"><input type="range" id="b" value="50"><output name="result">100</output></form> |
| `<progress value="...">...<progress>`   | Menampilkan indikator kemajuan dari suatu proses, seperti progress bar. | ```html<br>&lt;progress value="70" max="100"&gt;&lt;/progress&gt;<br>```                                      | <progress value="70" max="100"></progress>        |
| `<meter value="...">...<meter>`         | Menyediakan indikator untuk nilai dalam rentang tertentu, seperti level atau kuota. | ```html<br>&lt;meter value="0.6" min="0" max="1"&gt;60%&lt;/meter&gt;<br>```                                 | <meter value="0.6" min="0" max="1">60%</meter>     |
| `<fieldset>...<fieldset>`               | Mengelompokkan elemen formulir dalam satu kelompok, sering digunakan bersama `<legend>`. | ```html<br>&lt;fieldset&gt;&lt;legend&gt;Informasi Kontak&lt;/legend&gt;&lt;input type="text"&gt;&lt;/fieldset&gt;<br>``` | <fieldset><legend>Informasi Kontak</legend><input type="text"></fieldset> |
| `<legend>...<legend>`                   | Menyediakan judul atau label untuk elemen `<fieldset>`. | ```html<br>&lt;fieldset&gt;&lt;legend&gt;Data Pribadi&lt;/legend&gt;&lt;input type="text"&gt;&lt;/fieldset&gt;<br>``` | <fieldset><legend>Data Pribadi</legend><input type="text"></fieldset> |
| `<output for="...">...<output>`         | Menyediakan tempat untuk menampilkan hasil perhitungan atau output dinamis, terkait dengan atribut `for`. | ```html<br>&lt;form oninput="result.value=parseInt(a.value)+parseInt(b.value)"&gt;&lt;input type="number" id="a" value="50"&gt;&lt;input type="number" id="b" value="50"&gt;&lt;output name="result"&gt;100&lt;/output&gt;&lt;/form&gt;<br>``` | <form oninput="result.value=parseInt(a.value)+parseInt(b.value)"><input type="number" id="a" value="50"><input type="number" id="b" value="50"><output name="result">100</output></form> |
| `<input type="radio">`                   | Menyediakan opsi tunggal dalam grup pilihan yang tidak dapat dipilih bersamaan. | ```html<br>&lt;input type="radio" id="option1" name="options" value="1"&gt;&lt;label for="option1"&gt;Opsi 1&lt;/label&gt;<br>&lt;input type="radio" id="option2" name="options" value="2"&gt;&lt;label for="option2"&gt;Opsi 2&lt;/label&gt;<br>``` | <input type="radio" id="option1" name="options" value="1"><label for="option1">Opsi 1</label><input type="radio" id="option2" name="options" value="2"><label for="option2">Opsi 2</label> |
| `<input type="checkbox">`                | Menyediakan opsi yang dapat dipilih secara independen, baik dipilih atau tidak dipilih. | ```html<br>&lt;input type="checkbox" id="check1"&gt;&lt;label for="check1"&gt;Centang ini&lt;/label&gt;<br>``` | <input type="checkbox" id="check1"><label for="check1">Centang ini</label> |
| `<input type="hidden">`                  | Menyimpan data yang tidak terlihat oleh pengguna, tetapi dikirim bersama formulir. | ```html<br>&lt;input type="hidden" name="userId" value="12345"&gt;<br>```                                      | (Tidak terlihat, menyimpan data `userId=12345`)   |
| `<input type="date">`                    | Menyediakan kontrol untuk memilih tanggal. | ```html<br>&lt;input type="date" id="date"&gt;<br>```                                                         | <input type="date" id="date">                      |
| `<input type="email">`                   | Menyediakan kontrol untuk memasukkan alamat email dengan validasi otomatis. | ```html<br>&lt;input type="email" id="email" placeholder="email@domain.com"&gt;<br>```                       | <input type="email" id="email" placeholder="email@domain.com"> |
| `<input type="number">`                  | Menyediakan kontrol untuk memasukkan angka dengan opsi pengaturan nilai minimal dan maksimal. | ```html<br>&lt;input type="number" id="quantity" min="1" max="10"&gt;<br>```                                 | <input type="number" id="quantity" min="1" max="10"> |
| `<input type="range">`                   | Menyediakan kontrol untuk memilih nilai dari rentang angka dengan slider. | ```html<br>&lt;input type="range" id="volume" min="0" max="100" value="50"&gt;<br>```                        | <input type="range" id="volume" min="0" max="100" value="50"> |
| `<input type="color">`                   | Menyediakan kontrol untuk memilih warna dengan palet warna. | ```html<br>&lt;input type="color" id="favcolor"&gt;<br>```                                                    | <input type="color" id="favcolor">                 |
| `<input type="file">`                    | Menyediakan kontrol untuk memilih file dari sistem file pengguna. | ```html<br>&lt;input type="file" id="file"&gt;<br>```                                                        | <input type="file" id="file">                      |
| `<input type="url">`                     | Menyediakan kontrol untuk memasukkan URL dengan validasi otomatis. | ```html<br>&lt;input type="url" id="website" placeholder="https://example.com"&gt;<br>```                    | <input type="url" id="website" placeholder="https://example.com"> |
| `<input type="tel">`                     | Menyediakan kontrol untuk memasukkan nomor telepon dengan validasi otomatis. | ```html<br>&lt;input type="tel" id="phone" placeholder="+123456789"&gt;<br>```                               | <input type="tel" id="phone" placeholder="+123456789"> |
| `<input type="password">`                | Menyediakan kontrol untuk memasukkan kata sandi yang disembunyikan dengan titik. | ```html<br>&lt;input type="password" id="password"&gt;<br>```                                                | <input type="password" id="password">              |
| `<input type="submit">`                  | Menyediakan tombol untuk mengirimkan formulir. | ```html<br>&lt;input type="submit" value="Kirim"&gt;<br>```                                                   | <input type="submit" value="Kirim">               |
| `<input type="reset">`                   | Menyediakan tombol untuk mengatur ulang formulir ke nilai default. | ```html<br>&lt;input type="reset" value="Reset"&gt;<br>```                                                    | <input type="reset" value="Reset">                |
| `<input type="search">`                  | Menyediakan kontrol untuk memasukkan teks pencarian dengan fitur pencarian khusus. | ```html<br>&lt;input type="search" id="search" placeholder="Cari... "&gt;<br>```                             | <input type="search" id="search" placeholder="Cari... "> |
| `<input type="week">`                    | Menyediakan kontrol untuk memilih minggu dan tahun. | ```html<br>&lt;input type="week" id="week"&gt;<br>```                                                         | <input type="week" id="week">                      |
| `<input type="datetime-local">`          | Menyediakan kontrol untuk memilih tanggal dan waktu lokal. | ```html<br>&lt;input type="datetime-local" id="datetime"&gt;<br>```                                            | <input type="datetime-local" id="datetime">        |
| `<input type="time">`                    | Menyediakan kontrol untuk memilih waktu. | ```html<br>&lt;input type="time" id="time"&gt;<br>```                                                         | <input type="time" id="time">                      |
| `<input type="month">`                   | Menyediakan kontrol untuk memilih bulan dan tahun. | ```html<br>&lt;input type="month" id="month"&gt;<br>```                                                       | <input type="month" id="month">                   |
| Elemen HTML                             | Fungsi                                                        | Contoh Penggunaan                                                                                      | Hasil                                            |
|-----------------------------------------|---------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| `<base>...<base>`                      | Menentukan URL dasar untuk semua link relatif dalam dokumen. | ```html<br>&lt;head&gt;&lt;base href="https://example.com/"&gt;&lt;/head&gt;<br>```                  | (Menetapkan URL dasar untuk semua tautan relatif) |
| `<blockquote>...<blockquote>`          | Menandai kutipan panjang dari sumber lain, biasanya dengan indentasi. | ```html<br>&lt;blockquote&gt;Kutipan panjang dari sumber lain&lt;/blockquote&gt;<br>```            | <blockquote>Kutipan panjang dari sumber lain</blockquote> |
| `<cite>...<cite>`                      | Menyediakan referensi atau kredit untuk sumber kutipan. | ```html<br>&lt;cite&gt;Penulis Buku&lt;/cite&gt;<br>```                                                | <cite>Penulis Buku</cite>                       |
| `<code>...<code>`                      | Menandai teks sebagai kode program. | ```html<br>&lt;code&gt;console.log("Hello World");&lt;/code&gt;<br>```                              | <code>console.log("Hello World");</code>       |
| `<del>...<del>`                        | Menyediakan teks yang telah dihapus atau tidak berlaku lagi. | ```html<br>&lt;del&gt;Teks yang dihapus&lt;/del&gt;<br>```                                             | <del>Teks yang dihapus</del>                    |
| `<ins>...<ins>`                        | Menyediakan teks yang telah ditambahkan atau diperbarui. | ```html<br>&lt;ins&gt;Teks yang ditambahkan&lt;/ins&gt;<br>```                                         | <ins>Teks yang ditambahkan</ins>                |
| `<kbd>...<kbd>`                        | Menandai input keyboard dari pengguna. | ```html<br>&lt;kbd&gt;Ctrl + C&lt;/kbd&gt;<br>```                                                        | <kbd>Ctrl + C</kbd>                            |
| `<mark>...<mark>`                      | Menyoroti teks untuk menandai informasi penting. | ```html<br>&lt;mark&gt;Teks yang disorot&lt;/mark&gt;<br>```                                            | <mark>Teks yang disorot</mark>                  |
| `<pre>...<pre>`                        | Menyediakan teks yang dipertahankan formatnya, biasanya untuk kode. | ```html<br>&lt;pre&gt;const a = 5;\nconst b = 10;&lt;/pre&gt;<br>```                                  | <pre>const a = 5;
const b = 10;</pre>                     |
| `<s>...<s>`                            | Menyediakan teks yang tidak berlaku atau tidak relevan. | ```html<br>&lt;s&gt;Teks yang dicoret&lt;/s&gt;<br>```                                                  | <s>Teks yang dicoret</s>                        |
| `<small>...<small>`                    | Menyediakan teks dengan ukuran font yang lebih kecil. | ```html<br>&lt;small&gt;Teks kecil&lt;/small&gt;<br>```                                                 | <small>Teks kecil</small>                       |
| `<strong>...<strong>`                  | Menyediakan teks yang diberi penekanan kuat (tebal). | ```html<br>&lt;strong&gt;Teks yang kuat&lt;/strong&gt;<br>```                                          | <strong>Teks yang kuat</strong>                |
| `<sub>...<sub>`                        | Menyediakan teks dengan subskrip (lebih kecil dan di bawah teks normal). | ```html<br>&lt;sub&gt;Teks subskrip&lt;/sub&gt;<br>```                                                | <sub>Teks subskrip</sub>                        |
| `<sup>...<sup>`                        | Menyediakan teks dengan superskrip (lebih kecil dan di atas teks normal). | ```html<br>&lt;sup&gt;Teks superskrip&lt;/sup&gt;<br>```                                                | <sup>Teks superskrip</sup>                      |
| `<table>...<table>`                    | Menyediakan elemen tabel untuk menampilkan data dalam format tabel. | ```html<br>&lt;table&gt;&lt;tr&gt;&lt;td&gt;Data&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;<br>```          | <table><tr><td>Data</td></tr></table>           |
| `<tbody>...<tbody>`                    | Menyediakan bagian tubuh tabel, biasanya berisi baris-baris data. | ```html<br>&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;Data&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt;<br>``` | <tbody><tr><td>Data</td></tr></tbody>          |
| `<thead>...<thead>`                    | Menyediakan bagian kepala tabel, biasanya berisi header kolom. | ```html<br>&lt;table&gt;&lt;thead&gt;&lt;tr&gt;&lt;th&gt;Header&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;&lt;/table&gt;<br>``` | <thead><tr><th>Header</th></tr></thead>        |
| `<tfoot>...<tfoot>`                    | Menyediakan bagian kaki tabel, biasanya berisi informasi total atau ringkasan. | ```html<br>&lt;table&gt;&lt;tfoot&gt;&lt;tr&gt;&lt;td&gt;Total&lt;/td&gt;&lt;/tr&gt;&lt;/tfoot&gt;&lt;/table&gt;<br>``` | <tfoot><tr><td>Total</td></tr></tfoot>        |
| `<caption>...<caption>`                | Menyediakan judul atau deskripsi untuk elemen tabel. | ```html<br>&lt;table&gt;&lt;caption&gt;Judul Tabel&lt;/caption&gt;&lt;/table&gt;<br>```                 | <caption>Judul Tabel</caption>                 |
| `<details>...<details>`                | Menyediakan elemen yang dapat diperluas untuk menampilkan informasi tambahan. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk info&lt;/summary&gt;&lt;p&gt;Informasi tambahan&lt;/p&gt;&lt;/details&gt;<br>``` | <details><summary>Klik untuk info</summary><p>Informasi tambahan</p></details> |
| `<summary>...<summary>`                | Menyediakan tajuk untuk elemen `<details>`. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk melihat&lt;/summary&gt;&lt;p&gt;Isi detail&lt;/p&gt;&lt;/details&gt;<br>``` | <details><summary>Klik untuk melihat</summary><p>Isi detail</p></details> |
| `<dialog>...<dialog>`                  | Menyediakan kotak dialog atau jendela popup yang dapat digunakan untuk interaksi pengguna. | ```html<br>&lt;dialog open&gt;Ini adalah dialog&lt;/dialog&gt;<br>```                                   | <dialog open>Ini adalah dialog</dialog>         |
| `<progress value="...">...<progress>`  | Menyediakan indikator kemajuan dari proses yang sedang berlangsung. | ```html<br>&lt;progress value="60" max="100"&gt;&lt;/progress&gt;<br>```                                | <progress value="60" max="100"></progress>     |
| `<meter value="...">...<meter>`        | Menyediakan indikator untuk nilai yang berada dalam rentang tertentu. | ```html<br>&lt;meter value="0.75" min="0" max="1"&gt;75%&lt;/meter&gt;<br>```                          | <meter value="0.75" min="0" max="1">75%</meter> |
| `<template>...<template>`              | Menyediakan template yang tidak dirender secara langsung tetapi dapat digunakan untuk menyisipkan konten dinamis dengan JavaScript. | ```html<br>&lt;template id="my-template"&gt;&lt;p&gt;Ini adalah template&lt;/p&gt;&lt;/template&gt;<br>``` | (Template tidak terlihat)                       |
| `<svg>...<svg>`                        | Menyediakan elemen grafis vektor yang dapat diperkecil atau diperbesar tanpa kehilangan kualitas. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/></svg> |
| `<path d="...">...<path>`              | Menggambar bentuk kompleks dengan mendefinisikan jalur atau garis dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;path d="M10 80 Q 95 10 180 80 T 350 80" stroke="black" fill="transparent"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><path d="M10 80 Q 95 10 180 80 T 350 80" stroke="black" fill="transparent"/></svg> |
| `<line x1="..." y1="..." x2="..." y2="...">...<line>` | Menggambar garis di dalam elemen SVG dari titik awal ke titik akhir. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;line x1="10" y1="10" x2="90" y2="90" stroke="black"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><line x1="10" y1="10" x2="90" y2="90" stroke="black"/></svg> |
| `<circle cx="..." cy="..." r="...">...<circle>` | Menggambar lingkaran di dalam elemen SVG dengan pusat dan radius yang ditentukan. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/></svg> |
| `<rect x="..." y="..." width="..." height="...">...<rect>` | Menggambar persegi panjang di dalam elemen SVG dengan posisi, lebar, dan tinggi yang ditentukan. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;rect x="10" y="10" width="80" height="50" stroke="black" fill="green"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><rect x="10" y="10" width="80" height="50" stroke="black" fill="green"/></svg> |
| `<polygon points="...">...<polygon>`  | Menggambar bentuk poligon dengan titik-titik yang ditentukan di dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;polygon points="50,15 100,100 0,100" stroke="black" fill="blue"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><polygon points="50,15 100,100 0,100" stroke="black" fill="blue"/></svg> |
| `<ellipse cx="..." cy="..." rx="..." ry="...">...<ellipse>` | Menggambar elips di dalam elemen SVG dengan pusat dan radius x dan y yang ditentukan. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;ellipse cx="50" cy="50" rx="30" ry="20" stroke="black" fill="purple"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><ellipse cx="50" cy="50" rx="30" ry="20" stroke="black" fill="purple"/></svg> |
| Elemen HTML                             | Fungsi                                                        | Contoh Penggunaan                                                                                      | Hasil                                            |
|-----------------------------------------|---------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| `<header>...<header>`                  | Menyediakan area untuk header atau bagian atas dokumen. | ```html<br>&lt;header&gt;&lt;h1&gt;Judul Utama&lt;/h1&gt;&lt;/header&gt;<br>```                      | <header><h1>Judul Utama</h1></header>          |
| `<footer>...<footer>`                  | Menyediakan area untuk footer atau bagian bawah dokumen. | ```html<br>&lt;footer&gt;&lt;p&gt;Hak Cipta 2024&lt;/p&gt;&lt;/footer&gt;<br>```                     | <footer><p>Hak Cipta 2024</p></footer>          |
| `<section>...<section>`                | Menyediakan bagian atau seksyen dalam dokumen. | ```html<br>&lt;section&gt;&lt;h2&gt;Bagian 1&lt;/h2&gt;&lt;p&gt;Konten bagian 1&lt;/p&gt;&lt;/section&gt;<br>``` | <section><h2>Bagian 1</h2><p>Konten bagian 1</p></section> |
| `<article>...<article>`                | Menyediakan konten independen atau artikel dalam dokumen. | ```html<br>&lt;article&gt;&lt;h2&gt;Artikel 1&lt;/h2&gt;&lt;p&gt;Isi artikel&lt;/p&gt;&lt;/article&gt;<br>``` | <article><h2>Artikel 1</h2><p>Isi artikel</p></article> |
| `<aside>...<aside>`                    | Menyediakan konten sampingan atau informasi tambahan. | ```html<br>&lt;aside&gt;&lt;p&gt;Informasi tambahan&lt;/p&gt;&lt;/aside&gt;<br>```                   | <aside><p>Informasi tambahan</p></aside>       |
| `<main>...<main>`                      | Menyediakan area utama dalam dokumen, berbeda dari header, footer, dan aside. | ```html<br>&lt;main&gt;&lt;h1&gt;Konten Utama&lt;/h1&gt;&lt;p&gt;Isi utama&lt;/p&gt;&lt;/main&gt;<br>``` | <main><h1>Konten Utama</h1><p>Isi utama</p></main> |
| `<nav>...<nav>`                        | Menyediakan area navigasi untuk tautan atau menu. | ```html<br>&lt;nav&gt;&lt;ul&gt;&lt;li&gt;&lt;a href="#home"&gt;Beranda&lt;/a&gt;&lt;/li&gt;&lt;/ul&gt;&lt;/nav&gt;<br>``` | <nav><ul><li><a href="#home">Beranda</a></li></ul></nav> |
| `<figure>...<figure>`                  | Menyediakan elemen untuk gambar atau diagram dengan keterangan. | ```html<br>&lt;figure&gt;&lt;img src="image.jpg" alt="Deskripsi"&gt;&lt;figcaption&gt;Keterangan&lt;/figcaption&gt;&lt;/figure&gt;<br>``` | <figure><img src="image.jpg" alt="Deskripsi"><figcaption>Keterangan</figcaption></figure> |
| `<figcaption>...<figcaption>`          | Menyediakan keterangan untuk elemen `<figure>`. | ```html<br>&lt;figure&gt;&lt;img src="image.jpg" alt="Deskripsi"&gt;&lt;figcaption&gt;Keterangan&lt;/figcaption&gt;&lt;/figure&gt;<br>``` | <figcaption>Keterangan</figcaption>            |
| `<div>...<div>`                        | Menyediakan kontainer umum untuk grup elemen, sering digunakan untuk pengaturan layout. | ```html<br>&lt;div&gt;&lt;p&gt;Teks dalam div&lt;/p&gt;&lt;/div&gt;<br>```                           | <div><p>Teks dalam div</p></div>               |
| `<span>...<span>`                      | Menyediakan kontainer inline untuk grup elemen atau teks kecil. | ```html<br>&lt;span&gt;Teks dalam span&lt;/span&gt;<br>```                                             | <span>Teks dalam span</span>                  |
| `<b>...<b>`                            | Menyediakan teks dengan gaya tebal (bold) tanpa memberikan arti semantik. | ```html<br>&lt;b&gt;Teks tebal&lt;/b&gt;<br>```                                                        | <b>Teks tebal</b>                              |
| `<i>...<i>`                            | Menyediakan teks dengan gaya miring (italic) tanpa memberikan arti semantik. | ```html<br>&lt;i&gt;Teks miring&lt;/i&gt;<br>```                                                        | <i>Teks miring</i>                            |
| `<u>...<u>`                            | Menyediakan teks dengan garis bawah. | ```html<br>&lt;u&gt;Teks bergaris bawah&lt;/u&gt;<br>```                                                | <u>Teks bergaris bawah</u>                     |
| `<s>...<s>`                            | Menyediakan teks yang dicoret, tidak relevan. | ```html<br>&lt;s&gt;Teks dicoret&lt;/s&gt;<br>```                                                       | <s>Teks dicoret</s>                            |
| `<del>...<del>`                        | Menyediakan teks yang dihapus atau diubah. | ```html<br>&lt;del&gt;Teks yang dihapus&lt;/del&gt;<br>```                                             | <del>Teks yang dihapus</del>                   |
| `<ins>...<ins>`                        | Menyediakan teks yang ditambahkan. | ```html<br>&lt;ins&gt;Teks yang ditambahkan&lt;/ins&gt;<br>```                                         | <ins>Teks yang ditambahkan</ins>               |
| `<datalist>...<datalist>`              | Menyediakan daftar pilihan untuk elemen `<input>` dengan tipe `list`. | ```html<br>&lt;input list="browsers"&gt;&lt;datalist id="browsers"&gt;&lt;option value="Chrome"&gt;&lt;option value="Firefox"&gt;&lt;/datalist&gt;<br>``` | <input list="browsers"><datalist id="browsers"><option value="Chrome"><option value="Firefox"></datalist> |
| `<output>...<output>`                  | Menyediakan area untuk menampilkan hasil kalkulasi atau output. | ```html<br>&lt;output name="result"&gt;0&lt;/output&gt;<br>```                                         | <output name="result">0</output>               |
| `<details>...<details>`                | Menyediakan kontrol untuk menampilkan atau menyembunyikan detail tambahan. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk detail&lt;/summary&gt;&lt;p&gt;Informasi detail&lt;/p&gt;&lt;/details&gt;<br>``` | <details><summary>Klik untuk detail</summary><p>Informasi detail</p></details> |
| `<summary>...<summary>`                | Menyediakan tajuk untuk elemen `<details>`. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk melihat&lt;/summary&gt;&lt;p&gt;Isi detail&lt;/p&gt;&lt;/details&gt;<br>``` | <summary>Klik untuk melihat</summary>         |
| `<dialog>...<dialog>`                  | Menyediakan dialog atau jendela popup yang dapat digunakan untuk interaksi pengguna. | ```html<br>&lt;dialog open&gt;Dialog aktif&lt;/dialog&gt;<br>```                                       | <dialog open>Dialog aktif</dialog>             |
| `<progress value="...">...<progress>`  | Menyediakan indikator kemajuan dari proses yang sedang berlangsung. | ```html<br>&lt;progress value="70" max="100"&gt;&lt;/progress&gt;<br>```                              | <progress value="70" max="100"></progress>     |
| `<meter value="...">...<meter>`        | Menyediakan indikator untuk nilai dalam rentang tertentu. | ```html<br>&lt;meter value="0.6" min="0" max="1"&gt;60%&lt;/meter&gt;<br>```                          | <meter value="0.6" min="0" max="1">60%</meter> |
| `<template>...<template>`              | Menyediakan template untuk konten yang tidak dirender langsung tetapi dapat digunakan dengan JavaScript. | ```html<br>&lt;template id="my-template"&gt;&lt;p&gt;Ini template&lt;/p&gt;&lt;/template&gt;<br>``` | (Template tidak terlihat)                       |
| `<svg>...<svg>`                        | Menyediakan elemen grafis vektor untuk gambar dan bentuk yang dapat diperbesar. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/></svg> |
| `<path d="...">...<path>`              | Menggambar jalur bentuk kompleks dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;path d="M10 80 Q 95 10 180 80 T 350 80" stroke="black" fill="transparent"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><path d="M10 80 Q 95 10 180 80 T 350 80" stroke="black" fill="transparent"/></svg> |
| `<line x1="..." y1="..." x2="..." y2="...">...<line>` | Menggambar garis dalam elemen SVG dari titik awal ke titik akhir. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;line x1="10" y1="10" x2="90" y2="90" stroke="black"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><line x1="10" y1="10" x2="90" y2="90" stroke="black"/></svg> |
| `<circle cx="..." cy="..." r="...">...<circle>` | Menggambar lingkaran di dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red"/></svg> |
| `<rect x="..." y="..." width="..." height="...">...<rect>` | Menggambar persegi panjang di dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;rect x="10" y="10" width="80" height="50" stroke="black" fill="green"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><rect x="10" y="10" width="80" height="50" stroke="black" fill="green"/></svg> |
| `<polygon points="...">...<polygon>`  | Menggambar bentuk poligon di dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;polygon points="50,15 100,100 0,100" stroke="black" fill="blue"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><polygon points="50,15 100,100 0,100" stroke="black" fill="blue"/></svg> |
| `<ellipse cx="..." cy="..." rx="..." ry="...">...<ellipse>` | Menggambar elips di dalam elemen SVG. | ```html<br>&lt;svg width="100" height="100"&gt;&lt;ellipse cx="50" cy="50" rx="30" ry="20" stroke="black" fill="purple"/&gt;&lt;/svg&gt;<br>``` | <svg width="100" height="100"><ellipse cx="50" cy="50" rx="30" ry="20" stroke="black" fill="purple"/></svg> |
| Elemen HTML                             | Fungsi                                                        | Contoh Penggunaan                                                                                      | Hasil                                            |
|-----------------------------------------|---------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| `<address>...<address>`                | Menyediakan informasi kontak atau alamat. | ```html<br>&lt;address&gt;&lt;p&gt;123 Jalan Utama, Jakarta&lt;/p&gt;&lt;/address&gt;<br>```         | <address><p>123 Jalan Utama, Jakarta</p></address> |
| `<bdi>...<bdi>`                        | Menyediakan isolasi bidirectional untuk teks. | ```html<br>&lt;bdi&gt;Teks yang tidak dipengaruhi&lt;/bdi&gt;<br>```                                 | <bdi>Teks yang tidak dipengaruhi</bdi>         |
| `<bdo dir="...">...<bdo>`              | Mengontrol arah teks di dalam elemen. | ```html<br>&lt;bdo dir="rtl"&gt;Teks dari kanan ke kiri&lt;/bdo&gt;<br>```                           | <bdo dir="rtl">Teks dari kanan ke kiri</bdo>  |
| `<details>...<details>`                | Menyediakan kontrol untuk menampilkan atau menyembunyikan detail tambahan. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk melihat&lt;/summary&gt;&lt;p&gt;Informasi detail&lt;/p&gt;&lt;/details&gt;<br>``` | <details><summary>Klik untuk melihat</summary><p>Informasi detail</p></details> |
| `<dialog>...<dialog>`                  | Menyediakan dialog atau jendela popup. | ```html<br>&lt;dialog open&gt;Dialog aktif&lt;/dialog&gt;<br>```                                       | <dialog open>Dialog aktif</dialog>             |
| `<summary>...<summary>`                | Menyediakan tajuk untuk elemen `<details>`. | ```html<br>&lt;details&gt;&lt;summary&gt;Klik untuk melihat&lt;/summary&gt;&lt;p&gt;Isi detail&lt;/p&gt;&lt;/details&gt;<br>``` | <summary>Klik untuk melihat</summary>         |
| `<time datetime="...">...<time>`        | Menyediakan informasi waktu atau tanggal yang terstruktur. | ```html<br>&lt;time datetime="2024-08-10"&gt;10 Agustus 2024&lt;/time&gt;<br>```                      | <time datetime="2024-08-10">10 Agustus 2024</time> |
| `<mark>...<mark>`                      | Menyediakan penanda untuk teks yang penting atau dicari. | ```html<br>&lt;mark&gt;Teks yang ditandai&lt;/mark&gt;<br>```                                          | <mark>Teks yang ditandai</mark>               |
| `<ruby>...<ruby>`                      | Menyediakan teks anotasi untuk karakter Jepang. | ```html<br>&lt;ruby&gt;漢字&lt;rt&gt;kanji&lt;/rt&gt;&lt;/ruby&gt;<br>```                            | <ruby>漢字<rt>kanji</rt></ruby>                |
| `<rt>...<rt>`                          | Menyediakan teks pinyin untuk elemen `<ruby>`. | ```html<br>&lt;ruby&gt;漢字&lt;rt&gt;kanji&lt;/rt&gt;&lt;/ruby&gt;<br>```                            | <ruby>漢字<rt>kanji</rt></ruby>                |
| `<rp>...<rp>`                          | Menyediakan tanda kurung untuk elemen `<ruby>`. | ```html<br>&lt;ruby&gt;漢字&lt;rp&gt;(kanji)&lt;/rp&gt;&lt;/ruby&gt;<br>```                          | <ruby>漢字<rp>(kanji)</rp></ruby>              |
| `<progress value="...">...<progress>`  | Menyediakan indikator kemajuan dari proses. | ```html<br>&lt;progress value="70" max="100"&gt;&lt;/progress&gt;<br>```                              | <progress value="70" max="100"></progress>     |
| `<meter value="...">...<meter>`        | Menyediakan indikator untuk nilai dalam rentang tertentu. | ```html<br>&lt;meter value="0.6" min="0" max="1"&gt;60%&lt;/meter&gt;<br>```                          | <meter value="0.6" min="0" max="1">60%</meter> |
| `<canvas>...<canvas>`                  | Menyediakan area untuk menggambar grafis menggunakan JavaScript. | ```html<br>&lt;canvas id="myCanvas" width="200" height="200"&gt;&lt;/canvas&gt;<br>```                | <canvas id="myCanvas" width="200" height="200"></canvas> |
| `<script src="...">...<script>`        | Menyediakan skrip atau kode JavaScript. | ```html<br>&lt;script src="script.js"&gt;&lt;/script&gt;<br>```                                        | (Kode JavaScript dieksekusi)                   |
| `<noscript>...<noscript>`              | Menyediakan konten alternatif jika JavaScript dinonaktifkan. | ```html<br>&lt;noscript&gt;JavaScript tidak didukung&lt;/noscript&gt;<br>```                         | <noscript>JavaScript tidak didukung</noscript> |
| `<iframe src="...">...<iframe>`        | Menyediakan area untuk menyematkan halaman web lain di dalam dokumen. | ```html<br>&lt;iframe src="https://www.example.com" width="600" height="400"&gt;&lt;/iframe&gt;<br>``` | <iframe src="https://www.example.com" width="600" height="400"></iframe> |
| `<object data="..." type="...">...<object>` | Menyediakan konten eksternal yang disematkan, seperti gambar atau video. | ```html<br>&lt;object data="video.mp4" type="video/mp4"&gt;&lt;/object&gt;<br>```                      | <object data="video.mp4" type="video/mp4"></object> |
| `<embed src="..." type="...">...<embed>` | Menyediakan konten eksternal yang disematkan dengan tipe tertentu. | ```html<br>&lt;embed src="file.pdf" type="application/pdf"&gt;<br>```                                | <embed src="file.pdf" type="application/pdf">  |
| `<param name="..." value="...">...<param>` | Menyediakan parameter untuk elemen `<object>`. | ```html<br>&lt;object data="movie.swf" type="application/x-shockwave-flash"&gt;&lt;param name="autoplay" value="true"&gt;&lt;/object&gt;<br>``` | (Parameter ditetapkan untuk objek Flash)      |
| `<source src="..." type="...">...<source>` | Menyediakan sumber media untuk elemen `<video>` atau `<audio>`. | ```html<br>&lt;video controls&gt;&lt;source src="movie.mp4" type="video/mp4"&gt;&lt;/video&gt;<br>``` | <video controls><source src="movie.mp4" type="video/mp4"></video> |
| `<track src="..." kind="...">...<track>` | Menyediakan teks track (subtitle) untuk elemen `<video>`. | ```html<br>&lt;video controls&gt;&lt;source src="movie.mp4" type="video/mp4"&gt;&lt;track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English"&gt;&lt;/video&gt;<br>``` | <video controls><source src="movie.mp4" type="video/mp4"><track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English"></video> |
| `<map>...<map>`                        | Menyediakan area peta untuk elemen `<img>`. | ```html<br>&lt;map name="example"&gt;&lt;area shape="rect" coords="34,44,270,350" href="link.html"&gt;&lt;/map&gt;&lt;img src="image.jpg" usemap="#example"&gt;<br>``` | <map name="example"><area shape="rect" coords="34,44,270,350" href="link.html"></map><img src="image.jpg" usemap="#example"> |
| `<area shape="..." coords="..." href="...">...<area>` | Menyediakan area klik pada elemen `<map>`. | ```html<br>&lt;map name="example"&gt;&lt;area shape="rect" coords="34,44,270,350" href="link.html"&gt;&lt;/map&gt;&lt;img src="image.jpg" usemap="#example"&gt;<br>``` | <map name="example"><area shape="rect" coords="34,44,270,350" href="link.html"></map><img src="image.jpg" usemap="#example"> |
| `<link rel="..." href="...">...<link>` | Menyediakan link ke sumber eksternal seperti CSS. | ```html<br>&lt;link rel="stylesheet" href="styles.css"&gt;<br>```                                       | (Link ke stylesheet)                           |
| `<meta name="..." content="...">...<meta>` | Menyediakan metadata untuk elemen dokumen, seperti deskripsi dan kata kunci. | ```html<br>&lt;meta name="description" content="Deskripsi halaman"&gt;<br>```                        | (Metadata disetel)                            |
| `<title>...<title>`                    | Menyediakan judul untuk dokumen yang ditampilkan di bilah judul browser. | ```html<br>&lt;title&gt;Judul Halaman&lt;/title&gt;<br>```                                             | <title>Judul Halaman</title>                  |





### **At-Rules yang Sering Digunakan**

1. **`@charset`**:
   - **Kegunaan**: Menentukan karakter encoding file CSS.
   - **Contoh Penggunaan**: Dalam file CSS untuk memastikan encoding yang benar.

2. **`@import`**:
   - **Kegunaan**: Mengimpor stylesheet eksternal ke dalam file CSS.
   - **Contoh Penggunaan**: Umum digunakan untuk mengimpor font atau stylesheet tambahan.

3. **`@media`**:
   - **Kegunaan**: Media queries untuk menerapkan gaya berdasarkan kondisi layar atau perangkat.
   - **Contoh Penggunaan**: Desain responsif yang menyesuaikan tampilan berdasarkan ukuran layar.

4. **`@supports`**:
   - **Kegunaan**: Mengecek dukungan browser terhadap fitur CSS tertentu sebelum menerapkan gaya.
   - **Contoh Penggunaan**: Menerapkan gaya modern hanya jika didukung oleh browser.

5. **`@font-face`**:
   - **Kegunaan**: Mendefinisikan font khusus yang dapat digunakan dalam dokumen.
   - **Contoh Penggunaan**: Menggunakan font yang di-host secara lokal atau dari web.

6. **`@keyframes`**:
   - **Kegunaan**: Mendefinisikan animasi CSS.
   - **Contoh Penggunaan**: Membuat animasi transisi atau pergerakan elemen.

7. **`@page`**:
   - **Kegunaan**: Menyusun gaya untuk halaman saat dicetak.
   - **Contoh Penggunaan**: Menyesuaikan margin atau ukuran halaman untuk pencetakan.

8. **`@namespace`**:
   - **Kegunaan**: Mendeklarasikan namespace XML dalam CSS.
   - **Contoh Penggunaan**: Umum digunakan dalam dokumen yang mengandung SVG atau XML.

9. **`@layer`** (baru tapi semakin populer):
   - **Kegunaan**: Mengelola lapisan prioritas dalam CSS.
   - **Contoh Penggunaan**: Untuk manajemen konflik gaya yang lebih baik dalam proyek besar.

### **At-Rules yang Jarang Digunakan**

1. **`@counter-style`**:
   - **Kegunaan**: Mendefinisikan gaya penomoran daftar kustom.
   - **Contoh Penggunaan**: Digunakan dalam pembuatan daftar yang unik, seperti numerik atau simbol kustom.

2. **`@document`** (deprecated):
   - **Kegunaan**: Menerapkan gaya untuk dokumen atau URL tertentu.
   - **Contoh Penggunaan**: Sekarang jarang digunakan karena telah deprecated.

3. **`@viewport`**:
   - **Kegunaan**: Mengontrol pengaturan viewport di berbagai perangkat.
   - **Contoh Penggunaan**: Mengelola aspek viewport seperti zooming, meskipun jarang digunakan secara langsung.

4. **`@region`** (experimental):
   - **Kegunaan**: Menghubungkan gaya ke bagian tertentu dari konten yang mengalir.
   - **Contoh Penggunaan**: Digunakan dalam layout kompleks.

5. **`@property`**:
   - **Kegunaan**: Mendefinisikan properti CSS kustom.
   - **Contoh Penggunaan**: Digunakan untuk memperluas kemampuan variabel CSS.

6. **`@custom-media`** (experimental):
   - **Kegunaan**: Mendefinisikan kondisi media kustom untuk media queries.
   - **Contoh Penggunaan**: Mengurangi redundansi dalam media queries.

7. **`@color-profile`**:
   - **Kegunaan**: Mendefinisikan profil warna.
   - **Contoh Penggunaan**: Penting dalam pekerjaan desain grafis dan pencetakan yang sangat khusus.

8. **`@container`** (baru dan masih experimental):
   - **Kegunaan**: Menggunakan container queries untuk membuat gaya yang bergantung pada ukuran kontainer.
   - **Contoh Penggunaan**: Masih dalam pengembangan dan eksperimental, tetapi potensial untuk desain modular.

9. **`@scope`** (experimental):
   - **Kegunaan**: Mengisolasi aturan CSS dalam scope tertentu.
   - **Contoh Penggunaan**: Membantu dalam komponen yang bergaya secara independen, masih jarang digunakan.

10. **`@font-feature-values`** dan variannya (`@swash`, `@ornaments`, `@annotation`, dll.):
    - **Kegunaan**: Mendefinisikan dan mengontrol fitur tertentu dalam font.
    - **Contoh Penggunaan**: Sangat khusus dan jarang ditemui di luar pekerjaan tipografi profesional.

11. **`@nest`** (experimental):
    - **Kegunaan**: Menyusun aturan CSS bersarang.
    - **Contoh Penggunaan**: Eksperimental dan belum diadopsi secara luas.

12. **`@custom-selector`** (experimental):
    - **Kegunaan**: Mendefinisikan selector CSS kustom.
    - **Contoh Penggunaan**: Eksperimental dan jarang digunakan.

13. **`@when`** dan **`@else`** (experimental):
    - **Kegunaan**: Conditional grouping rules.
    - **Contoh Penggunaan**: Masih jarang karena eksperimental.

Aturan yang sering digunakan adalah dasar untuk pengembangan CSS sehari-hari, sedangkan yang jarang digunakan biasanya lebih spesifik untuk kebutuhan tertentu atau eksperimental, dan belum didukung secara luas di berbagai browser.


Meskipun tidak ada sebanyak 50 at-rules dalam spesifikasi CSS saat ini, berikut adalah daftar yang mencakup hampir semua at-rule yang ada, termasuk yang umum digunakan, eksperimental, dan yang jarang ditemui. Daftar ini juga mencakup varian atau penggunaan spesifik dari at-rule yang mungkin dianggap berbeda dalam konteks tertentu:

1. **`@charset`** - Menentukan karakter encoding.
2. **`@import`** - Mengimpor file CSS.
3. **`@namespace`** - Mendefinisikan namespace.
4. **`@media`** - Media queries untuk kondisi spesifik.
5. **`@supports`** - Mendukung fitur CSS tertentu.
6. **`@font-face`** - Mengimpor dan mendefinisikan font custom.
7. **`@keyframes`** - Mendefinisikan animasi.
8. **`@page`** - Gaya untuk pencetakan halaman.
9. **`@counter-style`** - Gaya penomoran daftar kustom.
10. **`@document`** (deprecated) - Gaya untuk dokumen spesifik.
11. **`@viewport`** - Mengontrol aspek viewport.
12. **`@region`** (experimental) - Menghubungkan gaya ke bagian tertentu dari konten yang mengalir.
13. **`@property`** - Mendefinisikan properti CSS kustom.
14. **`@layer`** - Mengelola lapisan prioritas dalam CSS.
15. **`@color-profile`** - Mendefinisikan profil warna.
16. **`@container`** - Menggunakan container queries.
17. **`@custom-media`** (experimental) - Mendefinisikan media queries kustom.
18. **`@scope`** (experimental) - Mengisolasi aturan CSS dalam scope tertentu.
19. **`@media screen`** - Varian media queries untuk layar.
20. **`@media print`** - Varian media queries untuk pencetakan.
21. **`@media speech`** - Varian media queries untuk speech output.
22. **`@font-feature-values`** - Mendefinisikan nilai fitur font.
23. **`@swash`** - Bagian dari `@font-feature-values` untuk swash glyphs.
24. **`@ornaments`** - Bagian dari `@font-feature-values` untuk glyph ornament.
25. **`@annotation`** - Bagian dari `@font-feature-values` untuk annotation glyphs.
26. **`@stylistic`** - Bagian dari `@font-feature-values` untuk gaya stylistic.
27. **`@styleset`** - Bagian dari `@font-feature-values` untuk set gaya.
28. **`@character-variant`** - Bagian dari `@font-feature-values` untuk varian karakter.
29. **`@ligatures`** - Bagian dari `@font-feature-values` untuk ligatur.
30. **`@discretionary-ligatures`** - Bagian dari `@font-feature-values` untuk ligatur diskresioner.
31. **`@historical-ligatures`** - Bagian dari `@font-feature-values` untuk ligatur historis.
32. **`@stylistic-sets`** - Bagian dari `@font-feature-values` untuk set gaya stylistic.
33. **`@media handheld`** (deprecated) - Varian media queries untuk perangkat genggam.
34. **`@media all`** - Varian media queries untuk semua media.
35. **`@media projection`** (deprecated) - Varian media queries untuk proyektor.
36. **`@font-variation-settings`** - Mendefinisikan variasi font.
37. **`@swash`** - Mendefinisikan swash glyphs.
38. **`@ornaments`** - Mendefinisikan ornament glyphs.
39. **`@annotation`** - Mendefinisikan annotation glyphs.
40. **`@stylistic`** - Mendefinisikan fitur stylistic dalam font.
41. **`@styleset`** - Mendefinisikan set gaya dalam font.
42. **`@character-variant`** - Mendefinisikan varian karakter dalam font.
43. **`@feature`** (deprecated) - Fitur dalam font.
44. **`@viewport rule`** - Mengontrol viewport properties (varian).
45. **`@custom-selector`** (experimental) - Mendefinisikan selector CSS kustom.
46. **`@custom-media`** - Mendefinisikan media queries kustom (varian).
47. **`@nest`** (experimental) - Nested CSS rules.
48. **`@scope rule`** - Scope untuk gaya CSS (varian).
49. **`@when`** (experimental) - Conditional grouping rule.
50. **`@else`** (experimental) - Conditional grouping for `@when`.

Meskipun daftar di atas mencakup varian dan penggunaan spesifik, tidak ada lebih dari 50 at-rule unik dalam CSS saat ini. Beberapa dari aturan ini adalah eksperimental atau jarang digunakan dalam praktek sehari-hari dan mungkin tidak didukung secara luas di berbagai browser.

# --------------------------------------------------------------------------------------------------------

Tentu! Berikut adalah penjelasan awal tentang **CSS at-rules**, termasuk definisi umum, kegunaan, serta penjelasan mendalam dan contoh masing-masing at-rule dengan tingkat kesulitan yang berbeda.

---

## **Penjelasan Awal: CSS At-Rules**

**CSS at-rules** adalah instruksi khusus dalam CSS yang dimulai dengan tanda `@` diikuti oleh nama aturan dan seringkali diakhiri dengan blok deklarasi dalam kurung kurawal `{}`. Aturan ini digunakan untuk menambahkan fitur atau pengaturan khusus yang mempengaruhi bagaimana gaya diterapkan pada halaman web. At-rules dapat mengatur encoding, mengimpor file CSS, mengatur animasi, dan banyak lagi.

**Kegunaan**: 
1. **Definisi**: Mengatur gaya berdasarkan fitur spesifik atau kondisi.
2. **Pengaturan**: Menyediakan cara untuk mengatur bagaimana elemen ditampilkan atau diproses.
3. **Optimisasi**: Mengelola bagaimana gaya diterapkan dan dikompilasi untuk performa yang lebih baik.

---

### 1. **`@charset`**

- **Penjelasan**: Mendefinisikan encoding karakter yang digunakan dalam file CSS. Ini penting untuk memastikan bahwa karakter khusus seperti aksen atau simbol ditampilkan dengan benar.

- **Analogi**: `@charset` seperti memilih bahasa yang akan digunakan dalam buku. Jika buku ditulis dalam bahasa Inggris, maka semua pembaca harus mengerti bahasa Inggris agar bisa memahami isinya.

- **Contoh**:

  - **Biasa**:
    ```css
    @charset "UTF-8";
    ```
    - **Penjelasan**: Mendeklarasikan bahwa file CSS menggunakan encoding UTF-8, yang mendukung berbagai karakter internasional.
    - **Hasil**: File CSS bisa menggunakan karakter khusus dari berbagai bahasa.

  - **Sedang**:
    ```css
    @charset "ISO-8859-1";
    ```
    - **Penjelasan**: Mengatur encoding ke ISO-8859-1, yang mendukung karakter Latin Eropa Barat.
    - **Hasil**: File CSS dapat menggunakan karakter-karakter khusus dari bahasa Latin Eropa.

  - **Rumit**:
    ```css
    @charset "Windows-1252";
    ```
    - **Penjelasan**: Menggunakan encoding Windows-1252, yang sering digunakan dalam sistem Windows.
    - **Hasil**: Dukungan karakter tambahan seperti simbol mata uang Euro atau karakter khusus Eropa.

### 2. **`@import`**

- **Penjelasan**: Mengimpor file CSS lain ke dalam stylesheet yang aktif. Ini memungkinkan pemecahan gaya ke dalam beberapa file untuk organisasi yang lebih baik.

- **Analogi**: `@import` seperti mengundang seseorang ke acara. Anda memberi tahu siapa yang harus hadir, dan mereka membawa apa yang mereka butuhkan untuk berpartisipasi.

- **Contoh**:

  - **Biasa**:
    ```css
    @import url("styles.css");
    ```
    - **Penjelasan**: Mengimpor file CSS `styles.css` ke dalam stylesheet yang aktif.
    - **Hasil**: Gaya dari `styles.css` diterapkan ke halaman.

  - **Sedang**:
    ```css
    @import url("https://example.com/styles.css");
    ```
    - **Penjelasan**: Mengimpor file CSS dari URL eksternal.
    - **Hasil**: Gaya dari file yang di-host secara online diterapkan ke halaman.

  - **Rumit**:
    ```css
    @import url("https://example.com/styles.css") screen and (max-width: 600px);
    ```
    - **Penjelasan**: Mengimpor file CSS eksternal hanya jika layar memiliki lebar maksimal 600px.
    - **Hasil**: Gaya khusus diterapkan hanya pada perangkat mobile dengan layar kecil.

### 3. **`@namespace`**

- **Penjelasan**: Mendefinisikan namespace untuk elemen-elemen dalam CSS, berguna saat bekerja dengan XML atau SVG untuk menghindari konflik nama.

- **Analogi**: `@namespace` seperti menetapkan aturan permainan untuk tim yang berbeda dalam kompetisi. Setiap tim memiliki aturan sendiri yang diterapkan hanya untuk mereka.

- **Contoh**:

  - **Biasa**:
    ```css
    @namespace svg url("http://www.w3.org/2000/svg");
    ```
    - **Penjelasan**: Mendefinisikan namespace SVG untuk mengatur gaya pada elemen SVG.
    - **Hasil**: Gaya yang diterapkan hanya berlaku untuk elemen SVG.

  - **Sedang**:
    ```css
    @namespace math url("http://www.w3.org/1998/Math/MathML");
    ```
    - **Penjelasan**: Mendefinisikan namespace untuk MathML, memungkinkan penerapan gaya pada elemen matematika.
    - **Hasil**: Gaya diterapkan khusus untuk elemen matematika.

  - **Rumit**:
    ```css
    @namespace svg url("http://www.w3.org/2000/svg");
    @namespace xlink url("http://www.w3.org/1999/xlink");
    ```
    - **Penjelasan**: Mendefinisikan beberapa namespace, memungkinkan pengaturan gaya untuk elemen SVG dan XLink.
    - **Hasil**: Gaya diterapkan pada elemen yang menggunakan namespace berbeda.

### 4. **`@media`**

- **Penjelasan**: Mengatur gaya berdasarkan kondisi media, seperti ukuran layar atau orientasi. Ini berguna untuk membuat desain responsif.

- **Analogi**: `@media` seperti membuat peraturan khusus untuk berbagai jenis kendaraan di jalan raya. Anda memiliki peraturan berbeda untuk mobil, sepeda, dan pejalan kaki.

- **Contoh**:

  - **Biasa**:
    ```css
    @media screen and (max-width: 600px) {
      body {
        background-color: lightblue;
      }
    }
    ```
    - **Penjelasan**: Mengubah latar belakang halaman menjadi biru muda jika layar berukuran maksimal 600px.
    - **Hasil**: Gaya khusus diterapkan pada perangkat mobile.

  - **Sedang**:
    ```css
    @media (min-width: 768px) and (orientation: landscape) {
      .container {
        width: 80%;
      }
    }
    ```
    - **Penjelasan**: Mengatur lebar `.container` menjadi 80% jika layar minimal 768px dan orientasi landscape.
    - **Hasil**: Gaya diterapkan pada tablet atau desktop dengan orientasi landscape.

  - **Rumit**:
    ```css
    @media (prefers-color-scheme: dark) and (min-width: 1200px) {
      body {
        color: white;
        background-color: black;
      }
    }
    ```
    - **Penjelasan**: Mengatur warna teks dan latar belakang menjadi putih dan hitam jika pengguna lebih suka mode gelap dan lebar layar minimal 1200px.
    - **Hasil**: Gaya sesuai dengan preferensi pengguna dan ukuran layar besar.

### 5. **`@supports`**

- **Penjelasan**: Mengatur gaya hanya jika browser mendukung fitur tertentu, seperti Flexbox atau Grid. Ini berguna untuk fallback atau gaya alternatif.

- **Analogi**: `@supports` seperti mengadakan audit untuk memastikan fasilitas tertentu tersedia sebelum memutuskan untuk menggunakannya.

- **Contoh**:

  - **Biasa**:
    ```css
    @supports (display: grid) {
      .grid-container {
        display: grid;
      }
    }
    ```
    - **Penjelasan**: Menggunakan CSS Grid jika browser mendukung `display: grid`.
    - **Hasil**: Elemen menggunakan grid layout jika fitur tersedia.

  - **Sedang**:
    ```css
    @supports (display: flex) {
      .flex-container {
        display: flex;
        justify-content: center;
      }
    }
    ```
    - **Penjelasan**: Menggunakan Flexbox jika browser mendukung `display: flex`.
    - **Hasil**: Layout menggunakan Flexbox dengan elemen yang terpusat.

  - **Rumit**:
    ```css
    @supports (display: grid) and (not (grid-template-areas: "header header header")) {
      .grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-areas: "header header header" "main main sidebar" "footer footer footer";
      }
    }
    ```
    - **Penjelasan**: Menggunakan CSS Grid dengan konfigurasi khusus jika browser mendukung Grid dan aturan grid-template-areas tidak sama.
    - **Hasil**: Layout kompleks dengan area grid yang dinamis.

### 6. **`@font-face`**

- **Penjelasan**: Mendefinisikan font kustom untuk digunakan dalam halaman web. Ini memungkinkan penggunaan font yang tidak tersedia secara default di sistem.

- **Analogi**: `@font-face` seperti mendatangkan font kustom ke perpustakaan Anda, sehingga Anda bisa menggunakan font tersebut dalam dokumen Anda.

- **Contoh**:

  - **Biasa**:
    ```css
    @font-face {
      font-family: "Arial";
      src: url("arial.woff");
    }
    ```
    - **Penjelasan**: Mendefinisikan font Arial menggunakan file WOFF.
    - **Hasil**: Font Arial digunakan pada ele

men yang ditentukan.

  - **Sedang**:
    ```css
    @font-face {
      font-family: "CustomFont";
      src: url("customfont.woff2") format("woff2"),
           url("customfont.woff") format("woff");
    }
    ```
    - **Penjelasan**: Mendefinisikan font kustom dengan beberapa format untuk kompatibilitas.
    - **Hasil**: Font kustom diterapkan dengan berbagai format untuk dukungan browser yang lebih baik.

  - **Rumit**:
    ```css
    @font-face {
      font-family: "ComplexFont";
      src: url("complexfont.eot"); /* IE9 Compat Modes */
      src: url("complexfont.eot?#iefix") format("embedded-opentype"), /* IE6-IE8 */
           url("complexfont.woff2") format("woff2"), /* Super Modern Browsers */
           url("complexfont.woff") format("woff"), /* Pretty Modern Browsers */
           url("complexfont.ttf") format("truetype"), /* Safari, Android, iOS */
           url("complexfont.svg#ComplexFont") format("svg"); /* Legacy iOS */
      font-weight: normal;
      font-style: normal;
    }
    ```
    - **Penjelasan**: Mendefinisikan font kustom dengan banyak format untuk kompatibilitas penuh dengan berbagai browser dan perangkat.
    - **Hasil**: Font kustom ditampilkan di berbagai browser dan perangkat dengan format yang sesuai.

### 7. **`@keyframes`**

- **Penjelasan**: Mendefinisikan animasi dengan langkah-langkah perubahan gaya dari satu titik waktu ke titik waktu lainnya.

- **Analogi**: `@keyframes` seperti membuat storyboard untuk film animasi. Anda menentukan bagaimana karakter atau objek berubah sepanjang film.

- **Contoh**:

  - **Biasa**:
    ```css
    @keyframes slide {
      from {
        transform: translateX(-100%);
      }
      to {
        transform: translateX(0);
      }
    }
    ```
    - **Penjelasan**: Animasi slide dari kiri ke posisi normal.
    - **Hasil**: Elemen bergerak horizontal saat animasi dijalankan.

  - **Sedang**:
    ```css
    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-30px);
      }
      60% {
        transform: translateY(-15px);
      }
    }
    ```
    - **Penjelasan**: Animasi bouncing dengan beberapa langkah pergerakan vertikal.
    - **Hasil**: Elemen memantul seperti bola dengan animasi berulang.

  - **Rumit**:
    ```css
    @keyframes complexAnimation {
      0% {
        transform: rotate(0deg) scale(1);
        opacity: 1;
      }
      50% {
        transform: rotate(180deg) scale(1.5);
        opacity: 0.5;
      }
      100% {
        transform: rotate(360deg) scale(1);
        opacity: 1;
      }
    }
    ```
    - **Penjelasan**: Animasi kompleks dengan rotasi, skala, dan perubahan opacity.
    - **Hasil**: Elemen berotasi penuh, membesar, dan memudar dalam siklus animasi.

### 8. **`@page`**

- **Penjelasan**: Mengatur gaya untuk halaman cetak, seperti margin, ukuran halaman, dan konten header/footer.

- **Analogi**: `@page` seperti mengatur layout untuk dokumen cetak. Anda menentukan bagaimana halaman akan tampil saat dicetak.

- **Contoh**:

  - **Biasa**:
    ```css
    @page {
      margin: 1in;
    }
    ```
    - **Penjelasan**: Mengatur margin halaman cetak menjadi 1 inci.
    - **Hasil**: Margin sekitar halaman saat dicetak.

  - **Sedang**:
    ```css
    @page {
      margin: 1in;
      size: A4;
    }
    ```
    - **Penjelasan**: Mengatur margin dan ukuran halaman ke A4.
    - **Hasil**: Halaman cetak berukuran A4 dengan margin 1 inci.

  - **Rumit**:
    ```css
    @page {
      margin: 1in;
      size: A4 landscape;
      @top-center {
        content: "Page " counter(page);
      }
      @bottom-right {
        content: "Confidential";
      }
    }
    ```
    - **Penjelasan**: Mengatur ukuran dan margin halaman, serta menambahkan header dan footer khusus.
    - **Hasil**: Halaman A4 landscape dengan nomor halaman di tengah atas dan teks "Confidential" di kanan bawah.

### 9. **`@counter-style`**

- **Penjelasan**: Mendefinisikan gaya penomoran kustom untuk daftar. Anda menentukan bagaimana nomor atau simbol daftar akan ditampilkan.

- **Analogi**: `@counter-style` seperti membuat sistem penomoran khusus untuk daftar. Anda memutuskan bagaimana angka atau huruf akan ditampilkan.

- **Contoh**:

  - **Biasa**:
    ```css
    @counter-style decimal {
      system: numeric;
      symbols: "1" "2" "3" "4" "5" "6" "7" "8" "9" "10";
    }
    ```
    - **Penjelasan**: Menentukan gaya penomoran desimal standar.
    - **Hasil**: Menampilkan nomor daftar seperti 1, 2, 3, dst.

  - **Sedang**:
    ```css
    @counter-style roman {
      system: numeric;
      symbols: "I" "II" "III" "IV" "V" "VI" "VII" "VIII" "IX" "X";
      suffix: ".";
    }
    ```
    - **Penjelasan**: Menentukan gaya penomoran Romawi dengan akhiran titik.
    - **Hasil**: Menampilkan nomor daftar seperti I., II., III., dst.

  - **Rumit**:
    ```css
    @counter-style custom-counter {
      system: numeric;
      symbols: "a" "b" "c" "d" "e" "f" "g" "h" "i" "j";
      suffix: ".";
      prefix: "Item ";
    }
    ```
    - **Penjelasan**: Mendefinisikan gaya penomoran kustom dengan awalan "Item" dan akhiran titik.
    - **Hasil**: Menampilkan nomor daftar seperti Item a., Item b., Item c., dst.

### 10. **`@document`** (deprecated)

- **Penjelasan**: `@document` adalah aturan yang memungkinkan Anda mendefinisikan gaya CSS khusus untuk dokumen dengan URL tertentu. Ini berguna jika Anda ingin menerapkan gaya hanya pada halaman web yang memiliki URL spesifik. Namun, perlu dicatat bahwa `@document` sudah tidak digunakan lagi dalam spesifikasi CSS terbaru dan tidak didukung oleh browser modern.

- **Analogi**: `@document` seperti membuat aturan khusus untuk dokumen tertentu di perpustakaan. Anda memberikan aturan yang hanya berlaku untuk buku tersebut.

- **Contoh**:

  - **Biasa**:
    ```css
    @document url("https://example.com/") {
      body {
        background-color: lightgreen;
      }
    }
    ```
    - **Penjelasan**: Mengatur latar belakang halaman menjadi hijau muda hanya untuk URL tertentu.
    - **Hasil**: Gaya hanya diterapkan pada halaman dari URL yang ditentukan.

  - **Sedang**:
    ```css
    @document url("https://example.com/page.html") {
      h1 {
        color: blue;
      }
    }
    ```
    - **Penjelasan**: Mengubah warna teks `<h1>` menjadi biru untuk halaman yang ditentukan.
    - **Hasil**: Gaya diterapkan hanya pada halaman dengan URL tertentu.

  - **Rumit**:
    ```css
    @document url("https://example.com/") {
      .header {
        background-image: url("header-bg.jpg");
      }
      @page {
        margin: 2cm;
      }
    }
    ```
    - **Penjelasan**: Menambahkan gambar latar belakang untuk elemen dengan kelas `.header` dan mengatur margin halaman cetak.
    - **Hasil**: Halaman dengan gambar latar belakang khusus dan margin yang ditentukan untuk pencetakan.

### 11. **`@viewport`**

- **Penjelasan**: Mengatur ukuran dan pengaturan viewport pada perangkat, seperti zoom dan orientasi. Berguna untuk memastikan tampilan yang konsisten di berbagai perangkat.

- **Analogi**: `@viewport` seperti mengatur pengaturan layar pada monitor atau TV. Anda menentukan bagaimana tampilan layar akan ditampilkan.

- **Contoh**:

  - **Biasa**:
    ```css
    @viewport {
      width: device-width;
    }
    ```
    - **Penjelasan**: Mengatur lebar viewport sama dengan lebar perangkat.
    - **Hasil**: Konten akan menyesuaikan dengan lebar perangkat, seperti smartphone atau tablet.

  - **Sedang**:
    ```css
    @viewport {
      width: device-width;
      zoom: 1.5;
    }
    ```
    - **Penjelasan**: Mengatur zoom viewport ke 1.5x dari ukuran default.
    -

 **Hasil**: Konten diperbesar 1.5 kali dari ukuran normal.

  - **Rumit**:
    ```css
    @viewport {
      width: device-width;
      height: device-height;
      zoom: 1;
      orientation: landscape;
    }
    ```
    - **Penjelasan**: Mengatur lebar dan tinggi viewport sesuai perangkat, dengan zoom default dan orientasi landscape.
    - **Hasil**: Tampilan diatur dengan spesifikasi perangkat dan orientasi yang ditentukan.

### 12. **`@supports`**

- **Penjelasan**: Mengatur gaya hanya jika browser mendukung fitur tertentu, seperti Flexbox atau Grid. Ini berguna untuk fallback atau gaya alternatif.

- **Analogi**: `@supports` seperti mengadakan audit untuk memastikan fasilitas tertentu tersedia sebelum memutuskan untuk menggunakannya.

- **Contoh**:

  - **Biasa**:
    ```css
    @supports (display: grid) {
      .grid-container {
        display: grid;
      }
    }
    ```
    - **Penjelasan**: Menggunakan CSS Grid jika browser mendukung `display: grid`.
    - **Hasil**: Elemen menggunakan grid layout jika fitur tersedia.

  - **Sedang**:
    ```css
    @supports (display: flex) {
      .flex-container {
        display: flex;
        justify-content: center;
      }
    }
    ```
    - **Penjelasan**: Menggunakan Flexbox jika browser mendukung `display: flex`.
    - **Hasil**: Layout menggunakan Flexbox dengan elemen yang terpusat.

  - **Rumit**:
    ```css
    @supports (display: grid) and (not (grid-template-areas: "header header header")) {
      .grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-areas: "header header header" "main main sidebar" "footer footer footer";
      }
    }
    ```
    - **Penjelasan**: Menggunakan CSS Grid dengan konfigurasi khusus jika browser mendukung Grid dan aturan grid-template-areas tidak sama.
    - **Hasil**: Layout kompleks dengan area grid yang dinamis.

### 13. **`@container`** (Experimental)

- **Penjelasan**: `@container` adalah aturan eksperimental dalam CSS yang memungkinkan Anda mendefinisikan aturan gaya berdasarkan ukuran kontainer daripada ukuran viewport. Ini berguna untuk membuat desain responsif yang bergantung pada ukuran elemen kontainer.

- **Analogi**: `@container` seperti menentukan aturan dalam ruangan tertentu berdasarkan ukuran ruangan tersebut. Misalnya, Anda dapat membuat peraturan khusus jika ukuran ruangan berubah.

- **Contoh**:

  - **Biasa**:
    ```css
    @container (min-width: 500px) {
      .box {
        background-color: lightblue;
      }
    }
    ```
    - **Penjelasan**: Mengubah warna latar belakang elemen `.box` menjadi biru muda jika lebar kontainer minimal 500px.
    - **Hasil**: Warna latar belakang berubah jika kontainer memiliki lebar yang ditentukan.

  - **Sedang**:
    ```css
    @container (min-width: 600px) and (max-width: 800px) {
      .box {
        font-size: 1.2em;
      }
    }
    ```
    - **Penjelasan**: Mengatur ukuran font elemen `.box` jika lebar kontainer berada dalam rentang 600px hingga 800px.
    - **Hasil**: Ukuran font berubah sesuai dengan ukuran kontainer yang ditentukan.

  - **Rumit**:
    ```css
    @container (min-width: 500px) {
      .container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
      }
      .item {
        background-color: lightcoral;
        padding: 10px;
      }
      @container (min-width: 800px) {
        .item {
          background-color: lightgreen;
          grid-column: span 2;
        }
      }
    }
    ```
    - **Penjelasan**: Mengatur layout grid dan gaya elemen `.item` di dalam kontainer jika lebar kontainer minimal 500px, dan mengubah gaya elemen `.item` jika lebar kontainer minimal 800px.
    - **Hasil**: Layout grid dengan perubahan gaya berdasarkan ukuran kontainer yang berbeda.

    `@container` adalah fitur eksperimental dan mungkin tidak didukung secara universal di semua browser saat ini, jadi pastikan untuk memeriksa kompatibilitas sebelum menggunakannya dalam proyek produksi.
---

Dengan penjelasan, analogi, contoh, dan hasil di atas, Anda dapat memahami berbagai at-rules CSS dan cara penggunaannya dalam pengaturan gaya halaman web.