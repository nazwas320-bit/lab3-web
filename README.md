# PRAKTIKUM 3 — CSS DASAR

## Identitas

**Nama:** Nazwa Salsabila
**NIM:** 312510155
**Mata Kuliah:** Pemrograman Web
**Praktikum:** Praktikum 3 — CSS Dasar

---

## 1. Tujuan Praktikum

Praktikum ini bertujuan untuk:

1. Memahami konsep dasar CSS.
2. Memahami aturan penulisan CSS.
3. Memahami selector sebagai pengontrol CSS.
4. Membuat pengaturan CSS pada HTML.

---

## 2. Tools yang Digunakan

* Visual Studio Code
* Web Browser
* GitHub
* CSS Validator

---

## 3. Struktur File

File yang digunakan dalam praktikum:

```text
Lab3Web/
│
├── lab2_css_dasar.html
├── style_eksternal.css
└── README.md
```

---

# 4. Langkah-Langkah Praktikum

## Langkah 1 — Membuat Dokumen HTML

Pertama, membuat file HTML dengan nama:

```text
lab2_css_dasar.html
```

Kemudian membuat struktur dasar HTML yang terdiri dari `DOCTYPE`, `html`, `head`, `title`, dan `body`.

Pada bagian body dibuat:

* Header
* Navigation
* Konten `Hello World`
* Paragraf
* Tombol informasi

### Screenshot

![SS 1 - HTML Dasar](screenshots/ss1-html-dasar.png)

---

## Langkah 2 — Menampilkan HTML di Browser

Setelah kode HTML selesai dibuat, file dibuka menggunakan browser untuk melihat tampilan awal sebelum diberikan CSS.

### Screenshot

![SS 2 - Tampilan HTML Awal](screenshots/ss2-html-awal.png)

---

## Langkah 3 — Menambahkan CSS Internal

CSS Internal ditambahkan menggunakan tag `<style>` pada bagian `<head>`.

CSS digunakan untuk mengatur:

* Jenis font
* Header
* Ukuran tulisan
* Warna tulisan
* Posisi teks
* Tulisan italic

Contoh:

```css
body {
    font-family: 'Open Sans', sans-serif;
}

header {
    min-height: 80px;
    border-bottom: 1px solid #77CCEF;
}

h1 {
    font-size: 24px;
    color: #D4A017;
    text-align: center;
    padding: 20px 10px;
}
```

### Screenshot

![SS 3 - CSS Internal](screenshots/ss3-css-internal.png)

---

## Langkah 4 — Menambahkan Inline CSS

Selanjutnya digunakan Inline CSS pada elemen paragraf.

Contohnya:

```html
<p style="text-align: center; color: #ccd8e4;">
    Kami sedang belajar HTML dan CSS dasar.
</p>
```

Inline CSS ditulis langsung pada tag HTML menggunakan atribut `style`.

### Screenshot

![SS 4 - Inline CSS](screenshots/ss4-inline-css.png)

---

## Langkah 5 — Membuat CSS Eksternal

Selanjutnya dibuat file CSS baru dengan nama:

```text
style_eksternal.css
```

File tersebut digunakan untuk menyimpan kode CSS secara terpisah dari file HTML.

### Screenshot

![SS 5 - File CSS Eksternal](screenshots/ss5-css-eksternal.png)

---

## Langkah 6 — Menghubungkan CSS Eksternal

File CSS eksternal dihubungkan dengan HTML menggunakan tag `<link>` pada bagian `<head>`.

```html
<link rel="stylesheet"
      href="style_eksternal.css"
      type="text/css">
```

### Screenshot

![SS 6 - Link CSS Eksternal](screenshots/ss6-link-css.png)

---

## Langkah 7 — Membuat Navigation

CSS digunakan untuk mengatur tampilan navigation.

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

nav a:hover {
    background: #0B6B3A;
}
```

Navigation juga diberikan efek `hover` ketika kursor diarahkan ke menu.

### Screenshot

![SS 7 - Navigation](screenshots/ss7-navigation.png)

---

## Langkah 8 — Menggunakan ID Selector

ID Selector digunakan untuk memberikan pengaturan CSS pada elemen yang memiliki ID tertentu.

Contoh:

```css
#intro {
    background: #FFD54F;
    border: 1px solid #D4A017;
    min-height: 100px;
    padding: 10px;
}

#intro h1 {
    text-align: left;
    color: #5C4500;
}
```

Pada HTML digunakan:

```html
<div id="intro">
```

### Screenshot

![SS 8 - ID Selector](screenshots/ss8-id-selector.png)

---

## Langkah 9 — Menggunakan Class Selector

Class Selector digunakan untuk mengatur elemen yang mempunyai class tertentu.

Contoh:

```css
.button {
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
}

.btn-primary {
    background: #E42A42;
}
```

Kemudian digunakan pada HTML:

```html
<a class="button btn-primary" href="#intro">
    Informasi selengkapnya.
</a>
```

### Screenshot

![SS 9 - Class Selector](screenshots/ss9-class-selector.png)

---

# 5. Hasil Akhir

Setelah seluruh CSS diterapkan, halaman web memiliki:

* Header dengan pengaturan CSS.
* Navigation bar.
* Efek hover pada menu.
* Bagian `Hello World`.
* Paragraf dengan Inline CSS.
* Tombol `Informasi selengkapnya`.
* ID Selector.
* Class Selector.
* Tampilan dengan tema warna kuning.

### Screenshot Hasil Akhir

![SS 10 - Hasil Akhir](screenshots/ss10-hasil-akhir.png)

---

# 6. Validasi CSS

Setelah praktikum selesai, dilakukan validasi CSS menggunakan:

**W3C CSS Validator**

Validasi dilakukan untuk memeriksa kode CSS yang telah dibuat.

### Screenshot

![SS 11 - Validasi CSS](screenshots/ss11-validasi.png)

---

# 7. Kesimpulan

Pada Praktikum 3 ini telah dipelajari dasar-dasar CSS, mulai dari CSS Internal, Inline CSS, dan CSS Eksternal. Selain itu, dipelajari juga penggunaan ID Selector dan Class Selector untuk mengatur tampilan elemen HTML.

Dengan menggunakan CSS, tampilan halaman HTML dapat dibuat lebih terstruktur dan menarik.

---

# 8. Repository

Repository praktikum ini dibuat dengan nama:

```text
Lab3Web
```

Seluruh file praktikum dan README telah dimasukkan ke dalam repository GitHub.

### Screenshot Repository

![SS 12 - Repository GitHub](screenshots/ss12-github.png)
