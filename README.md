# Instagram preview dummy

Dummy terpisah untuk menguji satu post Instagram publik nyata yang sudah diarsipkan lokal:

- halaman awal: cover harus langsung terlihat;
- hover: video MP4 lokal dibuat lalu diputar;
- pointer keluar: video dihapus dan cover tetap terlihat;
- klik: modal membuka embed Instagram publik.

## Menjalankan

```bash
python3 -m http.server 4911
```

Lalu buka http://127.0.0.1:4911.

Catatan: modal akan selalu terbuka. Isi iframe Instagram dapat putih/terblokir tergantung browser, cookie pihak ketiga, atau kebijakan Instagram. Itu adalah hasil uji popup yang perlu dilihat, bukan tanda bahwa kontennya berhasil dimuat.
