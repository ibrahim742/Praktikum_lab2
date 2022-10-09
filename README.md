# Praktikum_lab2
Tugas pertemuan3 pemograman web

# SOAL
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( `<p id="paragraf-1" class="text-paragraf">` )

# Jawaban
2. elemen `<p>` memanggil elemen yang tidak memilik class atau class di dalam class. Karena elemen `<p>` tidak memiliki group class
   elemen `#intro h1` memanggil class. Karena elemen `#intro h1` memiliki group class yang di dalamnya bisa beberapa tag tag yang lain
3. Deklarasi yang akan ditampilkan yaitu adalam deklarasi CSS internal. Karena deklarasi CSS internal sudah di satu kedalam `tag head` artinya tidak menggunakan memanggil css enternal.
   contoh: `CSS internal` sudah menyatuh ke dalam tag `html` yang posisi di `tag head`
           `CSS External` di luar tag html, jadi kita harus memanggil file CSS untuk menconek-kan file css ke dalam html
4. Keudanya sama saja sama sama akan di tampilkan pada browser. Tapi hanya saja beda pemanggilan di dalam CSS
   contoh: `<p id="paragraf-1>` pemanggillan di dalam CSS menggunakan `#paragraf-1`
           `<class="tex-paragraf">` pemanggillan di dalam CSS mengunakan `.text-paragraf` 