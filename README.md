# w3schools

## HTML Home
Menampilkan Awal Pembukaan dengan judul dan isinya.

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1> 
<p>This is a paragraph.</p>

</body>
</html>

## HTML Introduction
Menampilkan sama dengan di atas.

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

## HTML Editor
Menampilkan cara kerja, step by step dalam pengerjaannya.

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

## HTML Basic
Menjelaskan dalam pengunaannya adalah :
H1 adalah menmampilkan bab setiap bagian.
H2 adalah Meenampilkan judul.
H3 adalah menampilkan pembahasan, hampir sama dengan judul.

## HTML Element
Elemen dalam HTML yang penting dalam membuat html :
<html> </html>
<body> </body>
<h1> </h1>
<p> <p>
dan paad setiap elemnts tersebut terdapat tag awal dan akhir.

## HTML Atributes
Atribut dalam html :
<a> Menampilkan hyperlink
<href> Menentukan URL halaman yang di tuju oleh tautan tersebut.
<img> digunakan untuk menyematkan gambar.
<img> juga berisi atribut width dan height, yang menentukan lebar dan tinggi gambar dalam sebuah pixel.
<img src="img_girl.jpg" alt="Girl with a jacket"> menampilkan gambar
<img src="img_typo.jpg" alt="Girl with a jacket"> tidak menampilkan gambar

## HTML Headings
Setiap Heading menampilkan ukuran font dan bagian bagian di bedakan dalam.
h1,h2,h3,h4,h5,h6.

## HTML Paragraphs
<p></p>
Menampilkan sebuah paragraf.

## HTML Styles
Style, menampilkan warna, ukuran pada html yang kita tuju.

<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>

## HTML Formating
HTML juga berisikan elemen yang mendefinisikan teks dengan makna.
<b>- Teks tebal
<strong>- Teks penting
<i>- Teks miring
<em>- Teks yang ditekankan
<mark>- Teks yang ditandai
<small>- Teks lebih kecil
<del>- Teks dihapus
<ins>- Teks yang disisipkan
<sub>- Teks subskrip
<sup>- Teks superskrip

<!DOCTYPE html>
<html>
<body>

<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

</body>
</html>

## HTML Quotations
elemen <blockquote>, untuk Kutipan.
<q>, untuk Kutipan Pendek.
<abbr>, untuk Singkatan. 
<address>, untuk Informasi Kontak.
<cite>, untuk Judul Karya.
<bdo>, untuk Penimpaan Dua Arah.

## HTML Comments

<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->

digunakan untuk mengomentari.

## HTML Colors
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>

</body>
</html>

memiliki style/warna di setiap formatnya.
Setiap parameter (red, green, dan blue) menentukan intensitas warna dengan nilai antara 0 dan 255.
Ini berarti ada 256 x 256 x 256 = 16777216 kemungkinan warna!

#### rrggbb​
Di mana rr (merah), gg (hijau), dan bb (biru) adalah nilai heksadesimal antara 00 dan ff (sama dengan desimal 0-255).

<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:#ff0000;">#ff0000</h1>
<h1 style="background-color:#0000ff;">#0000ff</h1>
<h1 style="background-color:#3cb371;">#3cb371</h1>
<h1 style="background-color:#ee82ee;">#ee82ee</h1>
<h1 style="background-color:#ffa500;">#ffa500</h1>
<h1 style="background-color:#6a5acd;">#6a5acd</h1>

</body>
</html>

#### hsl(rona,saturasi,kecerahan)
Rona adalah derajat pada roda warna dari 0 hingga 360. 0 adalah merah, 120 adalah hijau, dan 240 adalah biru.
Saturasi adalah nilai persentase. 0% berarti corak abu-abu, dan 100% merupakan warna penuh.
Kecerahan juga merupakan nilai persentase. 0% berwarna hitam, dan 100% berwarna putih.

<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%)</h1>
<h1 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</h1>
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
<h1 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</h1>
<h1 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</h1>

</body>
</html>

## HTML CSS
Cascading Style Sheets (CSS) digunakan untuk memformat tata letak halaman web.

Dengan CSS, Anda dapat mengontrol warna, font, ukuran teks, jarak antar elemen, bagaimana elemen diposisikan dan ditata, gambar latar belakang atau warna latar belakang apa yang akan digunakan, tampilan berbeda untuk perangkat dan ukuran layar berbeda, dan banyak lagi!

Inline - dengan menggunakan styleatribut di dalam elemen HTML
Internal - dengan menggunakan <style>elemen di <head>bagian
Eksternal - dengan menggunakan <link> elemen untuk menautkan ke file CSS eksternal

## HTML Link
#### Tautan HTML - Hyperlink
Tautan HTML adalah hyperlink, anda dapat mengeklik tautan dan melompat ke dokumen lain.

#### Tautan HTML - Sintaksis
Atribut yang paling penting dari <a> elemen adalah hrefatribut, yang menunjukkan tujuan tautan. Teks tautan adalah bagian yang akan terlihat oleh pembaca.
Mengklik teks tautan akan mengarahkan pembaca ke alamat URL yang ditentukan.

#### Tautan HTML - Atribut Target
Secara default, halaman yang ditautkan akan ditampilkan di jendela browser saat ini. Untuk mengubahnya, Anda harus menentukan target lain untuk tautan tersebut.
Atribut targetmenentukan tempat untuk membuka dokumen yang ditautkan.

Atribut targetdapat memiliki salah satu nilai berikut:
_self- Default. Membuka dokumen di jendela/tab yang sama saat diklik
_blank- Membuka dokumen di jendela atau tab baru
_parent- Membuka dokumen di bingkai induk
_top- Membuka dokumen di badan penuh jendela

#### URL Absolut vs. URL Relatif
Kedua contoh di atas menggunakan URL absolut (alamat web lengkap) dalam hrefatribut.

Tautan lokal (tautan ke halaman dalam situs web yang sama) ditentukan dengan URL relatif (tanpa bagian "https://www")

#### Tautan HTML - Gunakan Gambar sebagai Tautan
Untuk menggunakan gambar sebagai tautan, cukup masukkan <img> tag di dalam <a>tag.

#### Tautan ke Alamat Email
Gunakan mailto:di dalam hrefatribut untuk membuat tautan yang membuka program email pengguna (agar mereka dapat mengirim email baru).

#### Tombol sebagai Tautan
Untuk menggunakan tombol HTML sebagai tautan, Anda harus menambahkan beberapa kode JavaScript.

JavaScript memungkinkan Anda menentukan apa yang terjadi pada peristiwa tertentu, seperti mengklik tombol.

#### Judul Tautan
Atribut ini titlemenentukan informasi tambahan tentang suatu elemen. Informasi ini paling sering ditampilkan sebagai teks keterangan alat saat mouse bergerak di atas elemen tersebut.

#### Singkatnya :
Gunakan <a>elemen untuk menentukan tautan
Gunakan hrefatribut untuk menentukan alamat tautan
Gunakan targetatribut untuk menentukan tempat membuka dokumen tertaut
Gunakan <img>elemen (di dalam <a>) untuk menggunakan gambar sebagai tautan
Gunakan mailto:skema di dalam hrefatribut untuk membuat tautan yang membuka program email pengguna

#### Tautan warna 
Tautan yang belum dikunjungi diberi garis bawah dan berwarna biru
Tautan yang telah dikunjungi digarisbawahi dan berwarna ungu
Tautan aktif digaris bawahi dan berwarna merah.

<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>

## HTML Images
#### Sintaksis Gambar HTML
Tag HTML <img>digunakan untuk menanamkan gambar di halaman web.

Secara teknis, gambar tidak dimasukkan ke dalam halaman web; gambar ditautkan ke halaman web. <img>Tag tersebut menciptakan ruang penyimpanan untuk gambar yang dirujuk.

Tag tersebut <img>kosong, hanya berisi atribut dan tidak memiliki tag penutup.

Tag <img>memiliki dua atribut yang diperlukan:

src - Menentukan jalur ke gambar
alt - Menentukan teks alternatif untuk gambar

#### Peta Gambar
Tag HTML <map>mendefinisikan peta gambar. Peta gambar adalah gambar dengan area yang dapat diklik. Area tersebut didefinisikan dengan satu atau beberapa <area>tag.

<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>

#### Gambar Latar Belakang pada elemen HTML
Untuk menambahkan gambar latar belakang pada elemen HTML, gunakan style atribut HTML dan properti CSS background-image

Jika Anda ingin seluruh halaman memiliki gambar latar belakang, Anda harus menentukan gambar latar belakang pada <body>elemen

#### Elemen HTML <gambar>
Elemen HTML <picture>memberi pengembang web lebih banyak fleksibilitas dalam menentukan sumber daya gambar. Elemen tersebut <picture>berisi satu atau beberapa <source>elemen, yang masing-masing merujuk ke gambar yang berbeda melalui srcset atribut. Dengan cara ini, browser dapat memilih gambar yang paling sesuai dengan tampilan dan/atau perangkat saat ini.
Setiap <source>elemen memiliki media atribut yang menentukan kapan gambar paling cocok.

## HTML Favicon
Untuk menambahkan favicon ke situs web Anda, simpan gambar favicon Anda ke direktori akar server web Anda, atau buat folder di direktori akar yang disebut gambar, dan simpan gambar favicon Anda di folder ini. Nama umum untuk gambar favicon adalah "favicon.ico".

<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

## HTML Page Title 
Setiap halaman web harus memiliki judul halaman untuk menggambarkan arti halaman tersebut.
Elemen ini <title>menambahkan judul ke halaman Anda.

<!DOCTYPE html>
<html>
<head>
  <title>HTML Tutorial</title>
</head>
<body>

The content of the document......

</body>
</html>

Elemen <title>:

mendefinisikan judul di bilah alat browser
memberikan judul untuk halaman saat ditambahkan ke favorit
menampilkan judul halaman di hasil mesin pencari.

## HTML Tables


## HTML Lists


## HTML Block & Inline 


## HTML DIV


## HTML Classes


## HTML Id


## HTML Inframes


## HTML JavaScript


## HTML File Paths


## HTML Head


## HTML Layout 


## HTML Responsive 


## HTML Cmomputercode


## HTML Smantics


## HTML Style Guide 


## HTML Entitas


## HTML Symbols


## HTML Emojis


## HTML Charsets


## HTML URL Ebncode


## HTML vs. XHTML


