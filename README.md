# UTS_Pemrograman_Web2

Nama: Bagus aditya hermawan
Nim: 312410382
Kelas: I241C

## Tampilan Dashboard
Dashboard menampilkan login dengan usernam. Setelah login, laluakan ditampilkan layar chat antara 2 orang secara real-time

## Struktur folder
```
websocket-chat/
│──server.js
├── package.json
├── package-lock.json
└── README.md
```

## Hasil Eksperimen
##### ![Gambar 1](ss/gambar1.png).
##### ![Gambar 1](ss/gambar2.png).
Pada tab pertama mengisi Ussername Budi dan pada tab kedua mengisi Username Sari.

##### ![Gambar 1](ss/gambar3.png).
##### ![Gambar 1](ss/gambar4.png).
Pada kedua gambar tersebut. Terdapat notifikasi pada masing-masing tab ketika ke-dua user tersebut bergabung kedalam chat. kemudian, ketika Budi mencoba memulai pesan pertama, pesan tersebut langsung muncul pada tab yang digunakan oleh Sari. Hal ini membuktikan bahwa WebScoket tidak harus meminta ulang ketika permbaruaan terjadi.
##### ![Gambar 1](ss/gambar5.png).
Ketika Budi keluar dari percakapan maka sistem akan mengirim informasi bahwa Budi telah keluar dari chat.
