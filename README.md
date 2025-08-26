## A. Heading

```txt
# = H1
## = H2
### = H3
#### = H4
##### = H5
###### = H6
```

_**e.g :**_

- # Heading 1

- ## Heading 2

- ### Heading 3

- #### Heading 4

- ##### Heading 5

- ###### Heading 6

---

## B. Teks Style

untuk membuat tulisan seperti Italic, Bold, Bold Italic dan Strikethrough.

```
Italic = *Tulisan*
Italic = _Tulisan_
Bold   = **Tulisan**
Strikethrough = ~~Tulisan~~

Digabung:
Bold Italic = **_Tulisan_**
```

**_e.g :_**

- Tulisan biasa
- _Tulisan Italic_
- **Tulisan Bold**
- ~~Tulisan Strikethrough~~
- ~~**_Tulisan Bold Italic dan Strikethrough_**~~

---

## C. Horizontal line

```
___         = untuk garis bawah
***         = untuk garis bawah
---         = untuk garis atas
gabungan --- dan ___ = untuk teksnya posisi tengah
```

**_e.g :_**

Garis Bawah

---

Garis Bawah

---

---

Garis atas

/////////////////////

---

## D. List

ada 2 jenis list yaitu : **Ordered List** dan **Unordered List**.

**Ordered List.**  
List yang menggunakan Number.

**_e.g :_**

1. Javascript
2. NodeJs
3. ReactJs
4. VueJs

**Unordered List**  
List yang Menggunakan - ( muncul Bullet ). **Unordered List** bisa menggunakan tanda - / + / bintang (\*).

**_e.g :_**

- Javascript
- NodeJs
- ReactJs
- VueJs

* Javascript
* NodeJs
* ReactJs
* VueJs

---

## E. Checkbox

```
- [ ]   --> ini belum di centang
- [X]   --> ini suda di centang
```

**_e.g :_**

- [ ] Belajar Pemrograman
- [x] Belajar javascript

Catatan : **wajib pakai tanda -**

---

## F. Blockqoute

Menggunakan tanda > untuk membuat sebuah blockqoute.

```
> "Tidak kenal lelah untuk Teknik Informatika. Bersama Informatika bisa!"
```

**_e.g :_**

> "Tidak kenal lelah untuk Teknik Informatika. Bersama Informatika bisa!"
>
>  <center>"Hidayat Lossen"</center>

Catatan: garis baru bisa pakai **spasi 2 kali** atau **\<br>**

---

## G. Inline Code

```
Untuk Memasukkan Code dalam Teks wajib menggunakna tanda backtick `Codenya` .
```

**_e.g :_**

Mencetak teks Hello World di Javascript `console.log("Hello World")`

---

## H. Code di Markdown

````
Menulis Code didalam markdown menggunan tanda
\```<typeBahasaPemrograman>  <-- pembuka

Teks atau code
yang ingin di tulis diletakkan antara tanda \```

\```   <-- penutup

````

**_e.g :_**

```json
{
  "firstName": "Hidayat",
  "lastName": "Lossen",
  "asal": "Maluku Utara"
}
```

---

## I. Link

```
1. Link langsung
    https://getbootstrap.com

2. Link Biasa Pakai Nama
    [kalimat](linknya)

3. Link Referensi
    [kalimat][referensenya]

    [namerefnya]: linknya

4. Link dan Title Hovernya
    [kalimat](linknya 'titlenya')
```

**_e.g :_**

1. Link langsung
   https://getbootstrap.com

2. Link inline (Pakai Nama)
   [Bootstrap](https://getbootstrap.com)

3. Link Referensi biasa dan referensi title
   [Bootstrap][contoh1]

   [contoh1]: https://getbootstrap.com
   [contoh2]: https://getbootstrap.com "Link Menuju Ke bootstrap"

4. Link dan Title Hovernya
   [Bootstrap](https://getbootstrap.com "Link Menuju Ke bootstrap")

---

## J. Image

```
Cara membuat gambar di Markdown:

1. Gambar biasa (alt text menangani gambar corrupt):
![alt text](link-gambar)

2. Gambar dengan Title Hover:
![alt text](link-gambar "Title hover muncul saat cursor di atas gambar")

3. Resize gambar pakai HTML:
<img src="link-gambar" width="200" height="100" alt="Alt text" title="Title hover">


```

**_e.g :_**

1. Gambar atau link yang corrupt  
   ![ini gambar bootstrap](https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.pn)
2. Gambar atau link yang tidak corrupt  
   ![ini gambar bootstrap](https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png)
3. Pakai Title Hover  
   ![ini gambar bootstrap](https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png "ini logo bootstrap")
4. Resize gambar pakai HTML  
   <img src="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png" 
     width="50" height="50" 
     alt="Logo Bootstrap" 
     title="Ini logo Bootstrap">

Catatan: Spasi 2 kali + enter:  
benar, tapi hanya berfungsi jika spasi benar-benar ada, tergantung platform. `<br>` lebih konsisten. Bisa ditambahkan catatan singkat.

---

## K. Tabel

```
untuk membuat table bisa menggunakan
tanda | (garis vertikal ) dan
- ( garis horizontal ).
```

**_e.g :_**  
|No | Nama | Nilai |
|---|----------|-------|
| 1 | Hidayat | 100 |
| 2 | Lossen | 100 |
| 3 | Tuasikal | 100 |

---

## L. Comment

```
Membuat comment wajib menggunakan
Commnet dari HTML
<!-- yang ingin di commnet -->
```

**_e.g :_**

1. `tanpa commnet `  
   Teks ini muncul di halam utama

2. `menggunakan comment`
<!-- teks ini tidak muncul di halam utama -->

---

## M. Baris Baru

```
Baris baru bisa pakai `spasi 2 kali + enter` atau
menggunakan tag `<br>`
```

**_e.g :_**

1. **Tanpa spasi 2 kali + enter dan tanpa \<br>**  
   Belajar Pemrograman `Javascript` dengan mudah Belajar algoritma dan Struktur data

2. **Menggunakan Spasi 2 Kali + Enter**  
   Belajar Pemrograman `Javascript` dengan mudah  
   Belajar algoritma dan Struktur data

3. **Menggunakan tag \<br>**  
   Belajar Pemrograman `Javascript` dengan mudah <br> Belajar algoritma dan Struktur data
