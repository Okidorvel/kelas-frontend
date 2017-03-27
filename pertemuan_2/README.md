# CATATAN PERTEMUAN 2
Berlangsung pada 27 Maret 2017, 13.00-15.00 WIB @ [QODR HQ](https://goo.gl/maps/MBNM8tfTmd82)

## INTRO
- Browser yang digunakan. (rekomendasi menggunakan chrome)
- Cross Platform Browser (Mengetes web kita agar sama dengan semua browser)
  - Firefox: 
    - Ada garis outline dibeberapa element.
    - Inspect element untuk merubah ukuran lebih sedikit.
    - Memakan RAM disemua-`tab`, baik yang aktif atau tidak.
  - Chrome: 
    - Inspect element untuk merubah ukuran lebih lengkap dan mendekati aslinya.
    - Memakan RAM di-`tab` yang aktif saja.
- Inspect Element:
   - Tab Elements: untuk merubah script html/css.
   - Tab Console: untuk menginputkan script `javascript`.
   - Tab Source: untuk melihat sumber dari apa web itu dibuat.
   - Tab Network: untuk melihat kecepatan load web.

## HTML
- Struktur dasar HTML:
  ```html
  <!DOCTYPE html>
  <html>
      <head>
          <meta charset="UTF-8">
          <title>Page Title</title>
      </head>
      <body>
      
      </body>
  </html>  
- Struktur yang wajib ada `<!DOCTYPE html>` untuk mengenali browser dengan tipe file `html`.
- Tag `<meta charset="UTF-8">` untuk standar pengkodean karakter dengan `utf-8`. 
- Heading: untuk membuat teks besar, dengan tag `<h1>` sampai `<h6>`.
- Paragraf: untuk membuat teks paragraf, dengan tag `<p>`.
- HTML Elements: 
  - diapit dengan tag `<namatag>` kemudian ditutup dengan `</namatag>`.
  - menggunakan lowercase (huruf kecil)
- HTML Attributes: informasi tambahan dari html element.
  - menggunakan lowercase dan diapit `double quote` (`""`) atau petik dua.
  - berguna juga untuk SEO
- HTML Headings:
  - berguna untuk SEO mengenali website.
  - harus ada disetiap page `h1`, `h2` dan `h3`.
  - hanya untuk heading, jangan untuk membuat teks besar / tebal.
  - `<hr>` untuk membuat garis horizontal.
- HTML Paragraphs:
  - menggunakan tag `<p>`.
  - tidak beda jika dibuat line baru atau tidak, tetap akan merata dan tidak berpengaruh.
  - tag `<br>` untuk membuat baris baru dari paragraph.
  - TAG `<pre>` untuk mengetik kode dengan terformat dan style font `Courier`.
- HTML Styles:
  - Disebut pula dengan `inline-css` dengan attribut `style`.
- HTML Formatting:
  - Untuk membuat tekks dengan format yang special.
  - diantaranya `<b>`, `<strong>`, `<i>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`.
  - tag `<strong>` menyatakan font yg penting dan `<b>` hanya teks tebal biasa.
  - tag `<em>` menyatakan font yg penting dan `<i>` hanya teks miring biasa.

## TIPS
- Gunakan inspect element untuk me-remake sementara.
- Ada plugin yang otomatis menyimpan editan dari css yang diubah di inspect elemeny.
- Dokumentasi tag-tag HTML di [HTML5 Doctor](http://html5doctor.com)
- Tutorial tentang fitur terbaru di [HTML5 Rocks](https://www.html5rocks.com)
- Materi pembelajaran kelas di [W3School](https://www.w3schools.com/)
- Untuk mengganti favicon `<link rel="icon" href="/favicon.ico" type="image/x-icon">`
- Praktekan semua materi bahasan pada HTML5 Tutorial di w3schools sebagai bahan latihan.

## TUGAS
- Semua yang telah dipelajarin dibuat dalam satu file lagi semisal `tugas_1.html` lalu diberi `style` yang bagus untuk melatih kemampuan.