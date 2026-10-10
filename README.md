# Praktikum Pemrograman Web

## CSS Internal, Inline CSS, CSS Eksternal, dan CSS Selector

### Deskripsi

Praktikum ini bertujuan untuk mempelajari dasar-dasar penggunaan CSS (*Cascading Style Sheets*) dalam mengatur tampilan halaman HTML. Materi yang dipelajari meliputi CSS Internal, Inline CSS, CSS Eksternal, serta penggunaan ID Selector dan Class Selector.

## Tujuan Praktikum

1. Memahami struktur dasar dokumen HTML.
2. Memahami penggunaan CSS Internal.
3. Memahami penerapan Inline CSS pada elemen HTML.
4. Memahami cara menghubungkan file CSS Eksternal dengan dokumen HTML.
5. Memahami penggunaan ID Selector dan Class Selector.
6. Membuat tampilan halaman web sederhana menggunakan HTML dan CSS.

## Teknologi yang Digunakan

- HTML5
- CSS3
- Visual Studio Code atau editor teks lainnya
- Web browser, seperti Google Chrome, Microsoft Edge, atau Mozilla Firefox
- W3C CSS Validator untuk memvalidasi kode CSS

## Struktur File

```text
praktikum-pemrograman-web/
├── lab3_css_dasar.html
├── lab3_css_eksternal.html
├── lab1_tag_dasar.html
├── style_eksternal.css
├── screenshot/
│   ├── ss1.png
│   ├── ss2.png
│   ├── ss3.png
│   ├── ss4.png
│   ├── ss5.png
│   └── ss6.png
└── README.md
```

## Langkah-Langkah Praktikum

### 1. Membuat Dokumen HTML

Membuat file `lab3_css_dasar.html` yang berisi struktur dasar HTML dengan beberapa elemen, yaitu:

- `header` sebagai bagian judul halaman.
- `nav` sebagai menu navigasi.
- `div` dengan ID `intro` sebagai bagian pengenalan.
- Elemen heading, paragraf, dan tautan untuk menampilkan konten halaman.

#### Result

![Gambar 1 - Tampilan Dokumen HTML](screenshot/ss1.png)

### 2. Mendeklarasikan CSS Internal

Menambahkan elemen `<style>` pada bagian `<head>` dokumen HTML untuk mengatur tampilan halaman. Pengaturan CSS meliputi:

- Jenis font pada halaman.
- Tinggi minimum dan garis bawah pada header.
- Ukuran, warna, dan perataan teks heading.
- Warna teks miring menggunakan elemen `<i>` di dalam heading.

CSS Internal memungkinkan aturan CSS ditulis langsung di dalam dokumen HTML.

#### Result

![Gambar 2 - Penerapan CSS Internal](screenshot/ss2.png)

### 3. Menambahkan Inline CSS

Menambahkan atribut `style` secara langsung pada elemen HTML untuk memberikan pengaturan tampilan tertentu.

Contoh penerapan Inline CSS:

```html
<p style="text-align: center; color: #ccd8e4;">
    Paragraf dengan CSS Inline
</p>
```

Pada contoh tersebut, teks paragraf dibuat rata tengah dan diberi warna `#ccd8e4`.

Inline CSS digunakan untuk menerapkan gaya secara langsung pada elemen HTML tertentu.

#### Result

![Gambar 3 - Penerapan Inline CSS](screenshot/ss3.png)

### 4. Membuat CSS Eksternal

Membuat file `style_eksternal.css` untuk menyimpan aturan CSS secara terpisah dari dokumen HTML. Pemisahan ini membantu membuat kode lebih terstruktur dan mudah dikelola.

Untuk menghubungkan file CSS eksternal dengan dokumen HTML, tambahkan tag `<link>` pada bagian `<head>`:

```html
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
```

Dengan cara ini, aturan CSS yang terdapat di dalam file `style_eksternal.css` dapat diterapkan pada halaman HTML yang menghubungkannya.

#### Result

![Gambar 4 - Penerapan CSS Eksternal](screenshot/ss4.png)

### 5. Menambahkan CSS Selector

Menambahkan CSS Selector untuk mengatur tampilan elemen HTML berdasarkan elemen, ID, maupun class. Salah satu penerapannya adalah mengatur tampilan menu navigasi dan tautan menggunakan selector `nav` dan `nav a`.

Contoh kode CSS untuk menu navigasi:

```css
nav {
    background: #20A759;
    color: #fff;
    padding: 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 10px 20px;
}

nav .active,
nav a:hover {
    background: #0B6B3A;
}
```

Selain itu, ID Selector digunakan untuk memberikan gaya pada elemen HTML berdasarkan atribut `id`.

Contoh ID Selector:

```css
#merah {
    color: red;
}

#serif {
    font-family: serif;
}

#rata-tengah {
    text-align: center;
    font-size: 12pt;
}
```

Contoh penerapan ID Selector pada HTML:

```html
<h1 id="merah">Heading Berwarna Merah</h1>

<p id="rata-tengah">Paragraf dengan rata tengah</p>

<p id="serif">Paragraf dengan font serif</p>
```

Pada contoh tersebut:

- `#merah` digunakan untuk mengubah warna teks menjadi merah.
- `#serif` digunakan untuk mengatur jenis huruf menjadi serif.
- `#rata-tengah` digunakan untuk membuat teks rata tengah dengan ukuran font 12 pt.

Sementara itu, Class Selector digunakan untuk memberikan gaya pada satu atau beberapa elemen yang memiliki atribut `class` yang sama.

#### Result

![Gambar 5 - Penerapan CSS Selector](screenshot/ss5.png)

## Hasil Pengujian CSS dengan W3C CSS Validator

Validasi CSS dilakukan menggunakan W3C CSS Validator untuk memeriksa kesesuaian kode CSS dengan standar CSS. Proses ini membantu mengidentifikasi kesalahan sintaks atau peringatan yang mungkin terdapat pada kode.

#### Result

![Gambar 6 - Hasil Validasi CSS](screenshot/ss6.png)

## Hasil Praktikum

Berdasarkan praktikum yang telah dilakukan, halaman web sederhana dapat dibuat menggunakan HTML dan CSS. Halaman tersebut menampilkan judul, menu navigasi, paragraf pengenalan, dan tautan dengan tampilan yang diatur melalui CSS Internal, Inline CSS, dan CSS Eksternal.

Penggunaan CSS Selector juga memungkinkan pengaturan tampilan elemen HTML berdasarkan ID dan class sehingga halaman web menjadi lebih terstruktur dan menarik.

## Kesimpulan

Melalui praktikum ini, mahasiswa mempelajari penerapan CSS pada dokumen HTML menggunakan tiga metode, yaitu CSS Internal, Inline CSS, dan CSS Eksternal. Mahasiswa juga memahami penggunaan ID Selector dan Class Selector untuk mengatur tampilan elemen HTML.

Dengan memahami konsep tersebut, mahasiswa diharapkan mampu membuat halaman web sederhana dengan tampilan yang lebih rapi, terstruktur, dan mudah dikelola.

---

**Mata Kuliah:** Pemrograman Web  
**Materi:** CSS Dasar  
**Universitas:** Universitas Pelita Bangsa
