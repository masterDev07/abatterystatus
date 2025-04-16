# Abatterystatus 🚀

**Abatterystatus** adalah aplikasi Android yang tidak hanya memberi tahu Anda 
saat baterai perangkat Anda perlu diisi ulang atau dilepas dari charger, tetapi 
juga menyapa Anda dengan nama! 🎉 Aplikasi ini memberikan pengalaman yang lebih 
personal dan menyenangkan. Berbeda dengan aplikasi sejenis yang hanya memberikan 
notifikasi umum, Abatterystatus menjadikan setiap interaksi lebih akrab dan 
hangat. Dengan teknologi canggih yang kami tawarkan, Anda tidak hanya 
mendapatkan informasi penting tentang status baterai, tetapi juga sentuhan 
personal yang membuat Anda merasa lebih terhubung dengan perangkat Anda. Jangan 
biarkan baterai Anda habis tanpa peringatan—biarkan Abatterystatus menjadi 
asisten setia Anda dalam menjaga daya perangkat! 🔋✨

## Fitur Utama 🌟

- Notifikasi suara yang menyapa pemilik perangkat saat baterai perlu diisi
  ulang atau dilepas dari charger. 🔊
- Konfigurasi yang mudah untuk menyesuaikan pengaturan notifikasi dan volume. ⚙️
- Penjadwalan eksekusi notifikasi setiap menit. ⏰
- Dukungan untuk bahasa Indonesia. 🇮🇩

## Lokasi File Konfigurasi 📁

File konfigurasi Abatterystatus dapat ditemukan di:
```markdown
/data/data/com.termux/files/home/storage/shared/abatterystatus/abatterystatus_configuration.conf
```

### Isi File Konfigurasi 📝

Berikut adalah isi dari file konfigurasi `abatterystatus_configuration.conf`:

```plaintext
# file konfigurasi abatterystatus di android
# setelah tanda pagar tidak dibaca
# tiap menit untuk jadwal eksekusi abatterystatus
jadwalEksekusi: 7
# batas minimal dan maksimal baterai android untuk di charger maupun lepas charger
batasMindanMaxcas: 33 93
# volume android dari 1 hingga 15 dan jumlah putaran audio notifikasi
volumeDanjumlahPutaranaudio: 8 2
# bahasa yang dipakai dan notifikasi suara semua kata disambung
bahasa: indonesia
# notifikasi suara saat perlu lepas charger
hai bos endro, batrai hape anda $persenBatrai persen perlu lepas charger
# notifikasi suara saat perlu pasang charger
hai bos endro, batrai hape anda $persenBatrai persen perlu dicas
# non aktifkan abatterystatus pada rentang waktu pukul tertentu
nonaktifkanAudiorentangwaktu: 111 00:00 04:00
# nama hari dalam 1 minggu
namaHaridalamSatuminggu: Senin Selasa Rabu Kamis Jum'at Sabtu Minggu
```

### Konfigurasi yang Dapat Dilakukan ⚙️

Anda dapat mengonfigurasi beberapa pengaturan dalam file ini, termasuk:

- **Volume Speaker**: Atur volume notifikasi dari 1 hingga 15. 🔊
- **Jadwal Eksekusi**: Tentukan frekuensi notifikasi. ⏲️
- **Batas Minimal dan Maksimal Baterai**: Atur batas untuk pengisian dan pelepasan charger. 🔋
- **Notifikasi Suara**: Ganti pesan notifikasi sesuai keinginan Anda. Misalnya:
  ```
  Hai juragan bakso, batrai hape juragan $persenBatrai persen perlu dicas.
  ```
  Di mana `$persenBatrai` adalah variabel yang berisi nilai persentase baterai saat ini. 📊
  
### How to Install Abatterystatus 🚀

1. Go to your home directory on Termux
2. Clone this repository: 🖥️✨
   ```bash
   git clone https://github.com/masterDev07/abatterystatus
   ```
3. Create schedule for abatterystatus
   ```bash
   ./abatterystatus bj
   ```     
4. Create alias
   ```bash
   crontab -e
   alias sbat='/data/data/com.termux/files/home/abatterystatus/abatterystatus'
   ```   

### Batas Waktu Penggunaan ⏳

Aplikasi ini hanya tersedia secara gratis hingga **[Expired](kadaluwarsa.txt)**. 
Untuk yang ingin memesan aplikasi yang expired hingga 15 tahun, silakan hubungi 
pembuat Abatterystatus melalui kontak dibawah ini. 📧

## Kontak 📬

Jika Anda memiliki pertanyaan atau lainnya, silakan hubungi kami di:
- ✉️ Email: [duitmoro@yahoo.com](mailto:duitmoro@yahoo.com)

---

Terima kasih telah menggunakan Abatterystatus! Semoga aplikasi ini bermanfaat 
untuk Anda. 🎉

