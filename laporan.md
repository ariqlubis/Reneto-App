# Raneto [![CircleCI](https://dl.circleci.com/status-badge/img/gh/ryanlelek/Raneto/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/ryanlelek/Raneto/tree/master)

[![Raneto Logo](https://raw.githubusercontent.com/ryanlelek/Raneto/master/logo/logo_readme.png)](https://raneto.com/)

## Instalasi

#### Kebutuhan Sistem:
- Unix, Linux, atau Windows. 
- `nodejs` v18.10.0
- `npm` v8.19.2

#### Proses Instalasi:
1. Pastikan seluruh paket kita *up-to-date*, dan install seluruh kebutuhan sistem seperti `nodejs` dan `npm`.
- Pada percobaan ini menggunakan Manjaro Linux (Arch-based).
```
$ sudo pacman -Syu
$ sudo pacman -S nodejs
$ sudo pacman -S npm
$ sudo pacman -S git
```
2. Clone / fork **Raneto** ke dalam direktori kita.
```
$ git clone https://github.com/ryanlelek/Raneto.git
```
3. Unduh package yang diperlukan oleh **Raneto**
```
$ cd Raneto/
$ npm install
```
4. Jalankan **Raneto**
```
$ node server.js
```
5. Buka [http://localhost:3000](http://localhost:3000) di browser

![image](https://user-images.githubusercontent.com/88980651/196254649-bf1448db-e2b7-4ecb-9900-0a6c8966dfcb.png)
