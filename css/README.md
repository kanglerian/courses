# **Pengenalan**
**_CSS_** (HTML) adalah bahasa markah standar untuk dokumen yang dirancang untuk ditampilkan di peramban internet. Ini dapat dibantu oleh teknologi seperti _Cascading Style Sheets_ (CSS) dan bahasa _scripting_ seperti JavaScript.

Sumber: Wikipedia

---

# **Apa itu Code Editor?**
Editor adalah sebuah aplikasi atau _software_ yang digunakan untuk mengedit `code` sebuah aplikasi atau website.

## Visual Studio Code
> **Visual Studio Code** adalah perangkat lunak penyunting kode-sumber buatan Microsoft untuk Linux, macOS, dan Windows. Visual Studio Code menyediakan fitur seperti penyorotan sintaksis, penyelesaian kode, kutipan kode, merefaktor kode, pengawakutuan, dan Git. Sumber: Wikipedia

[Download disini](https://code.visualstudio.com/ ':target=_blank')

![](/assets/images/vscode.jpg)

--- 

## Sublime Text
> Menurut Supono dan Putratama (2016:14) "Sublime text merupakan perangkat lunak text editor yang digunakan untuk membuat atau meng-edit suatu aplikasi. Sublime text mempunyai fitur plugin tambahan yang memudahkan programmer." 

[Download disini](https://www.sublimetext.com/ ':target=_blank')

![](/assets/images/sublime.jpg)

---

## Atom
> Atom adalah text editor yang bersifat free source dan open source bagi macOS, Linux, dan Microsoft Windows. Sumber: dewaweb.com  

[Download disini](https://atom.io/ ':target=_blank')

![](/assets/images/atom.jpg)

--- 

# **Element HTML**

> Sebuah Element HTML didefinisikan dengan memulai sebuah tag, isi dari _content_, dan akhir dari tag.

```HTML
<tagname>Isi kontent</tagname>
```

Ada beberapa macam tag yang biasa dipakai yaitu :
- `<!DOCTYPE html>` digunakan untuk mendeklarasikan HTML5.
- `<html>` digunakan untuk memulai sebuah code website.
- `<title>` digunakan untuk menuliskan judul sebuah website.
- `<head>` digunakan untuk menyimpan sebuah _link_, _meta data_, dan juga _title_.
- `<style>` digunakan untuk menambah _styling_ website.
- `<body>` digunakan sebagai wadah bagi _content_ yang akan ditampilkan.
- `<h1> - <h6>` digunakan untuk membuat sebuah _Heading_.
- `<p>` digunakan untuk membuat sebuah _paragraph_.
- `<img>` digunakan untuk menampilkan sebuah gambar.
- `<ul>` digunakan untuk menampilkan _list_ dengan sebuah **dots**.
- `<ol>` digunakan untuk menampilkan _list_ dengan nomor.
- `<footer>` digunakan untuk menampilkan atau membuat sebuah _footer_.
- `<h1>` digunakan menampilkan judul atau sub judul di webpage. Semakin besar angkanya maka semakin kecil ukuran hurufnya.
- `<hr>` adalah _Horizontal Rules_ digunakan untuk memberikan sebuah garis horizontal.
- `<br>` atau _Line Breaks_ digunakan untuk memberikan sebuah baris baru.
- `<tr>` digunakan untuk memulai sebuah baris tabel.
- `<td></td>` digunakan untuk menampilkan detail.
- `<th></th>` digunakan untuk menampilkan heading.
- `<li>` digunakan untuk memulai sebuah baris tabel.
- `<script>` digunakan untuk _client side_ JavaScript.
- dan yang lainnya.

---

## Block Element

- Selalui dimulai dari garis baru. 
- Full width.
- Memiliki _Top_ dan _Bottom_ _Margin_.

`<address>` `<h1> - <h6>` `<ol>` `<ul>` `<video>` `<article>` `<header>` `<p>` `<aside>` `<fieldset>` `<hr>` `<pre>` `<blockquote>` `<figcaption>` `<li>` `<section>` `<canvas>` `<aside>` `<figure>` `<main>` `<table>` `<footer>` `<nav>` `<div>` `<form>`

---

---

## Inline Element

- Tidak dimulai dari garis baru.

`<a>` `<button>` `<input>` `<code>` `<label>` `<script>` `<textarea>` `<time>` `<select>` `<b>` `<small>` `<span>` `<var>` `<i>` `<output>` `<strong>` `<table>` `<footer>` `<nav>` `<div>` `<form>` `<br>` `<img>`

---

# **Attribute HTML**

> Sebuah Attribute HTML didefinisikan dengan menambahkan sebuah _syntaks_ di dalam sebuah teks. Dan tidak semua attribute ini bisa kita pakai di dalam sebuah tag.

```HTML
<tagname attribute="">Isi kontent</tagname>
```

Ada beberapa macam _attribute_ yang biasa dipakai yaitu :
- `style` digunakan untuk menambahkan sebuah _styling_ pada tag.
- `href` digunakan untuk sumber atau lokasi _hyperlink_ yang akan diakses. Digunakan di : `<a>`
- `src` digunakan untuk sumber foto, audio atau video yang akan ditampilkan. Digunakan di : `<img>`
- `target` digunakan untuk dimana lokasi target membuka sebuah link. Digunakan di : `<a>`
- `width` digunakan untuk mengubah ukuran lebar gambar. Digunakan di : `<img>`
- `height` digunakan untuk mengubah ukuran tinggi gambar. Digunakan di : `<img>`
- `lang` digunakan untuk mendeklarasikan bahasa yang digunakan di sebuah website. Ini dimaksudkan untuk mempermudah pencarian google. Digunakan di : `<html>`
- `title` digunakan untuk menambahkan judul ketika di _hover_.
- `alt` digunakan untuk menampilkan teks jika gambar tidak tampil.
- `class` digunakan untuk menambahkan secara spesifik ke _Stylesheet_. Bisa digunakan beberapa kali.
- `id` digunakan untuk menambahkan identitas dari sebuah element.
- dan yang lainnya.

---

# **HTML Dasar**

Dibawah ini, kita akan belajar macam-macam tag yang digunakan HTML dalam membuat sebuah website. Pertama, kita tulis `code` dibawah ini untuk memulai :

```HTML
<!DOCTYPE html>
<html>
    <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

    </body>
</html>
```

## Heading

Heading adalah sebuah tag yang digunakan untuk menampilkan sebuah Header atau Teks seperti judul dan sub judul.

```HTML
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<hr>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<hr>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

![](/assets/images/screenshot/heading-looks.jpg)

---

## Paragraphs

Tag `<p>` digunakan untuk mendefinisikan sebuah paragraf.

```HTML
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

![](/assets/images/screenshot/paragraph-looks.jpg)

---

---

## Images

Tag `<img>` tanpa tag penutup, digunakan untuk menampilkan sebuah gambar. Bisa dengan format `.png`, `.jpg`, `.svg` atau `.gif`.

```HTML
<img src="url" alt="alternatetext">
<img src="/assets/images/sample/sample-1.jpeg" alt="laptop">
```

![](/assets/images/screenshot/img-looks.jpg)

---

## Table

Tag `<table></table>` digunakan untuk menampilkan sebuah tabel.

```HTML
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

![](/assets/images/screenshot/img-looks.jpg)

---

## List

Tag `<ul></ul>` atau `<ol></ol>` digunakan untuk menampilkan sebuah tabel.

```HTML
<ul>
    <li>Text 1</li>
    <li>Text 2</li>
    <li>Text 3</li>
    <li>Text 4</li>
</ul>

<ol>
    <li>Text 1</li>
    <li>Text 2</li>
    <li>Text 3</li>
    <li>Text 4</li>
</ol>
```

![](/assets/images/screenshot/list-looks.jpg)

---

---

## Links

Tag `<a>` digunakan untuk sebuah _hyperlink_. Kita bisa klik teks atau gambar ke `document` lain. Jangan lupa memakai tag penutup.

Macam-macam _value_ yang ada di tag `<a>` :
- `_blank` di dalam _attribute_ `target` digunakan untuk membuka halaman di _page_ baru

```HTML
<a href="url">Message</a>
<a href="https://kanglerian.github.io/">kanglerian</a>
```

![](/assets/images/screenshot/hyperlink-looks.jpg)

---

## Comment

Sintaks `<!-- content -->` digunakan untuk menjadikan sebuah tulisan atau tag lain menjadi tidak terbaca. Atau kita bisa menambah sebuah komentar untuk suatu sintaks.

```HTML
<!-- Not Showing on Your Page -->
```

---

## Class

Attribute `class` menambahkan sebuah _stylesheet_. Class dapat digunakan beberapa kali.

```CSS
.text-blue {
    color: blue;
}
```

```HTML
<p class="text-blue">This is Blue</p>
```

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .text-blue {
            color: blue;
        }
    </style>
</head>
<body>
    <p class="text-blue">This is Blue</p>
</body>
</html>  
```

![](/assets/images/screenshot/class-looks.jpg)

---

---

## ID

Attribute `id` menambahkan sebuah _identitas_ dapat juga digunakan sebagai _stylesheet_. ID hanya dapat digunakan sekali.

```CSS
#text-red {
    color: red;
}
```

```HTML
<p id="text-red">This is Blue</p>
```

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #text-red {
            color: red;
        }
    </style>
</head>
<body>
    <p id="text-red">This is ID red</p>
</body>
</html>  
```

![](/assets/images/screenshot/id-looks.jpg)

---

---

## JavaSript

Attribute `id` menambahkan sebuah _identitas_ dapat juga digunakan sebagai _stylesheet_. ID hanya dapat digunakan sekali.

```HTML
<script>
    document.getElementById(".demo").innerHTML = "Hello, ini Javascript!"
</script>
```

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="demo">This is ID red</p>

<script>
    document.getElementById("demo").innerHTML = "Hello, ini Javascript!"
</script>
</body>
</html>  
```

![](/assets/images/screenshot/javascript-looks.jpg)

---

