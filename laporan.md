# Instalalasi

#### Kebutuhan Sistem:
- Unix, Linux, atau Windows. 
- Nodejs v18.10.0
- npm v8.19.2

#### Proses Instalasi:
1. Pastikan seluruh paket kita *up-to-date*, dan install seluruh kebutuhan sistem seperti `nodejs` dan `npm`.
- Pada percobaan ini menggunakan Manjaro Linux (Arch-based).
```
$ sudo pacman -Syu
$ sudo pacman -S nodejs
$ sudo pacman -S npm
$ sudo pacman -S git
```
2. Clone / fork **Bubo Reader** ke dalam direktori kita.
```
$ git clone https://github.com/georgemandis/bubo-rss.git
```
3. Unduh package yang diperlukan oleh **Bubo Reader**
```
$ cd bubo-rss/
$ npm install
```
4. Jalankan **Bubo Reader**
```
$ npm run build:bubo
```
5. 
