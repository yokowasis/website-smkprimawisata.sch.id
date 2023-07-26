# Website Sekolah

## Tutorial Dasar

### Mengedit File

![editfile](tutorial/edit.gif)

### Mengupload File

![uploadfile](tutorial/uploadfile.gif)

## Mengganti Identitas Sekolah

Untuk mengganti identitas sekolah, edit file `_config.yml`. Ganti bagian - bagian yang di rasa perlu.

## Mengganti Logo

1. Upload logo ke ke folder images. Disarankan menggunakan format file png dan background transparant. Ada 3 macam logo, yaitu logo bagian header, footer dan icon.
2. Edit file `_config.yml`. 

Rubah bagian

```
logo: /images/Capture.PNG
logofooter: /images/footer_logo.png
icon: /images/logo smk.png
```

Sesuai dengan nama file yang di upload. contoh :

```
logo: /images/logoheader.png
logofooter: /images/logofooter.png
icon: /images/logoicon.png
```

## Mengganti Slider
1. Upload file - file slider ke dalam folder `images`. Ukuran gambar yang disarankan adalah `1600 x 900` pixels. 
2. Edit file `_config.yml`. 

Rubah bagian

```
sliders:
  - title: xxx
    text: xxx
    image: xxx
    link: xxx
    linktext: xxx
```

Sesuai dengan nama file yang di upload. contoh :

```
sliders:
  - title: Judul Slider
    text: Deskripsi Slider
    image: /images/namafilderslider.jpg
    link: /berita/2023/07/27/contoh-url-post.html
    linktext: Berita Selengkapnya
```
