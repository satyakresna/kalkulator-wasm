# Kalkulator dengan Web Assembly

Menulis ulang kode dari tutorial [**Web Assembly(WASM) Calculater Created in JavaScript**](https://www.youtube.com/watch?v=JqCaynNwtOA) menggunakan C dan emscripten untuk menghasilkan file web assembly yang digunakan untuk kalkulasi.

## Bagaimana cara menjalankannya.

Untuk mendapatkan hasil file berekstensi **.wasm** gunakan perintah emscripten di bawah.

```
emcc arithmetic.c -s WASM=1 -o arithmetic.html
```

Hapus file `arithmetic.html` dan `arithmetic.js`. Yang dibutuhkan hanya `arithmetic.wasm`!

Berikutnya, klik kanan di file index.html dan pilih open with [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) untuk menjalankan proyek ini.