<h1 <p align="center"><b>Praktikum 2</b></p></h1> 

**Nama: Rini Ariza**

**NIM: 312210337**

**Kelas: TI.22.A3**

---

## 1. Membuat dokumen HTML

Buatlah dokumen HTML seperti berikut:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
</head>
<body>
    <header>
        <h1>CSS Internal dan <i>Inline </i>CSS</h1>
    </header>
    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eskternal.html">CSS Eskternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    <!-- CSS ID Selector -->
    <div id="intro">
        <h1>Hello World</h1>
        <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemograman Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS</p>

        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya</a>
    </div>
</body>
</html>
```

Kemudian simpan perubahannya dan buka web browser kemudian refresh, berikut hasilnya

![Screenshot (267)](https://github.com/rniarzz/lab2Web/assets/115542704/48974aa1-aab6-4e8e-8029-0974054f2821)


## 2. Mendeklarasikan CSS Internal

Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

``html
    <head>
        <title>CSS Dasar</title>
        <style>
            body {
                font-family: 'Open Sans', sans-serif;
            }
    
            header {
                min-height: 80px;
                border-bottom: 1px solid #77ccef;
            }
    
            h1 {
                font-size: 24px;
                color: #0f189f;
                text-align: center;
                padding: 20px 10px;
            }
    
            h1 i {
                color: #6d6a6b;
            }
        </style>
    </header>
   ```
