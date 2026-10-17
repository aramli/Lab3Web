### Lab3Web
Praktikum 2 belajar dasar CSS <br>

NAMA    : Andi Ramli Hidayat <br>
NIM     : 312510385 <br>
KELAS   : I253B
<hr>
=========Jawaban Soal Praktikum==========
<p>1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.</p>
Jawaban : Saya mencoba menambahkan properti baru seperti `background-color`, `margin`, dan `padding` pada elemen. 
<br>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/6.png" width="300"/>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/7.png" width="300"/>
<br>
<p>2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!</p>
Jawaban :`h1 { ... }` → berlaku untuk semua elemen `h1` di halaman. `#intro` `h1 { ... }` → hanya berlaku untuk `h1` yang berada di dalam elemen dengan `id="intro"`.
<br>
<p>3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline
CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!</p>
Jawaban: Yang ditampilkan adalah Inline CSS, karena memiliki prioritas tertinggi.Urutan prioritas: Inline > Internal > Eksternal.
<br>
<p>4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector
tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada
browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-
paragraf"> )</p>.
Jawaban : Jika sebuah elemen punya ID dan Class, maka ID Selector lebih kuat dibanding Class.Hasilnya teks akan berwarna biru, karena aturan ID lebih spesifik dan menimpa aturan Class.
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/10.png" width="300"/>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/9.png" width="300"/>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/8.png" width="300"/>
<hr>

### Praktikum 
1. Buatlah repository baru dengan nama Lab3Web.<br>
2. Kerjakan semua latihan yang diberikan sesuai urutannya.<br>
3. Screenshot setiap perubahannya.<br>
4. Buatlah file README.md dan tuliskan penjelasan dari setiap langkah praktikum beserta
screenshotnya.<br>
5. Commit hasilnya pada repository masing-masing.<br>
6. Kirim URL repository pada e-learning ecampus<br>

#### 1. Membuat Dokumen HTML
Membuat struktur dasar HTML dengan elemen `<header>`, `<nav>`, dan `<div>` untuk konten. Tujuannya agar halaman siap diberi style CSS.
<br>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/1.png" width="300"/><br>

#### 2. Mendekralasikan CSS Internal
Menambahkan CSS di dalam tag `<style>` pada bagian `<head>`.  Contoh: mengatur font, warna, dan posisi teks. mudah dipakai untuk halaman tunggal.
<br>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/2.png" width="300"/><br>

#### 3. Menambahkan inline CSS
Menambahkan CSS langsung di atribut `style` pada elemen HTML.  
Contoh: `<p style="text-align:center; color:#ccd8e4;">`. Cepat untuk styling satu elemen, tapi kurang rapi.
<br>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/2.png" width="300"/><br>

#### 4. Membuat CSS Eksternal
Membuat file `.css` terpisah lalu dipanggil dengan `<link>` di `<head>`. ini lebih terstruktur, bisa dipakai di banyak halaman sekaligus.
<br>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/4.png" width="300"/><br>

#### 5. Menambahkan CSS Selector
**Elemen Selector:** langsung ke tag HTML (misalnya `p { color: green; }`).  **Class Selector:** pakai tanda titik `.` lalu dipanggil dengan atribut `class`.
**ID Selector:** pakai tanda `#` lalu dipanggil dengan atribut `id`. 
<br>
<img src="https://github.com/aramli/Lab3Web/raw/main/Praktikum3/5.png" width="300"/><br>

[![Lihat Hasil Praktikum](https://img.shields.io/badge/Go-Redirect-blue)](https://aramli.github.io/Lab3Web/lab2_css_dasar.html) → klik untuk lihat hasil praktikum
