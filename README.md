# Bot WhatsApp Termux Using Baileys

Ini adalah bot WhatsApp sederhana menggunakan library Baileys yang bisa dijalankan di Termux.

## Prasyarat

- Termux di Android
- Node.js terinstal (`pkg install nodejs`)
- Koneksi internet stabil

## Cara Setup

1. Clone atau download repository ini di Termux:
    ```bash
    git clone https://github.com/username/bot-wa-termux.git
    cd bot-wa-termux
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Jalankan bot:
    ```bash
    npm start
    ```

4. Scan QR code yang muncul di terminal menggunakan WhatsApp di ponsel Anda.

5. Bot akan otomatis membalas pesan dengan:
    ```
    Hai! Ini bot WhatsApp dari Termux.
    ```

## Catatan

- Jika ingin logout dan reset, hapus file `auth_info.json`.
- Untuk pengembangan lebih lanjut, modifikasi `index.js`. 
