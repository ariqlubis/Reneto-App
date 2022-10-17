# Konfigurasi Raneto App
Setelah proses instalasi Raneto app secara lokal telah selesai. Kita bisa mengkustomisasi isi konten dari docs wiki yang sudah disediakan oleh Raneto.
Sebelum kita _edit_ konfigurasinya, mari kita lihat file structure di bawah ini agar mempermudah dalam penjelasan mengakses filenya.

<p align="center">
  <img src="https://user-images.githubusercontent.com/73578698/196208479-151cdc12-1494-429d-ab5c-bd0ae9c8b4d9.png" width="130" alt="Logo for T3" />
</p>

## Langkah _edit content_ di dalam projek Raneto
Pertama-tama kita akses folder example/content. Lalu didalamnya Raneto sudah menyediakan _file structure_ dari isi konten yang tersedia untuk ditampilkan menjadi bagian
docs wiki yang ingin dibuat seperti pada gambar dibawah ini:

![image](https://user-images.githubusercontent.com/73578698/196211051-9dde1599-c81b-44b5-841e-363e4ab20f5b.png)

Misalkan kita mengubah title di dalam example/content/what-is-raneto.md di bagian header-nya dengan

```
---
Title: Apa itu Linux?
Sort: 1
ShowOnHome: true
---
```
Setelah file kita mengubah isi konten what-is-raneto.md, kita perlu _save_ hasil perubahan tersebut.

Jalankan _app_ projek Raneto dengan command npm dibawah ini sesuai dengan sistem operasi Anda: 

### Linux
``` npm run gulp && npm start ```

### Windows 
``` npm run start_win ``` 

Setelah itu kunjungi [http://localhost:3000](http://localhost:3000) di web browser anda.

Tampilan home yang baru akan terlihat seperti dibawah ini:

![image](https://user-images.githubusercontent.com/73578698/196215373-039cab35-d5ba-43e4-ba68-c9138625cd2b.png)

Selamat anda baru saja mengubah docs sesuai dengan keinginan anda, dengan _introduction_ seperti itu maka kita dapat mengubah konfigurasi isi konten dari docs.
