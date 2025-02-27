```markdown
# Abatterystatus 🚀

**Abatterystatus** Bayangkan sebuah aplikasi Android yang tidak hanya memberi tahu Anda saat baterai perangkat Anda perlu diisi ulang atau dilepas dari charger, tetapi juga menyapa Anda dengan nama! 🎉 Abatterystatus hadir untuk memberikan pengalaman yang lebih personal dan menyenangkan. Berbeda dengan aplikasi sejenis yang hanya memberikan notifikasi umum, Abatterystatus menjadikan setiap interaksi lebih akrab dan hangat. Dengan teknologi canggih yang kami tawarkan, Anda tidak hanya mendapatkan informasi penting tentang status baterai, tetapi juga sentuhan personal yang membuat Anda merasa lebih terhubung dengan perangkat Anda. Jangan biarkan baterai Anda habis tanpa peringatan—biarkan Abatterystatus menjadi asisten setia Anda dalam menjaga daya perangkat! 🔋✨

## Fitur Utama 🌟

- Notifikasi suara yang menyapa pemilik perangkat saat baterai perlu diisi ulang atau dilepas dari charger. 🔊
- Konfigurasi yang mudah untuk menyesuaikan pengaturan notifikasi dan volume. ⚙️
- Penjadwalan eksekusi notifikasi setiap menit. ⏰
- Dukungan untuk bahasa Indonesia. 🇮🇩

## Lokasi File Konfigurasi 📁

File konfigurasi Abatterystatus dapat ditemukan di:
```
/data/data/com.termux/files/home/storage/shared/abatterystatus/abatterystatus_configuration.conf
```

### Isi File Konfigurasi 📝

Berikut adalah isi dari file konfigurasi `abatterystatus_configuration.conf`:

```plaintext
# file konfigurasi abatterystatus di android
# setelah tanda pagar tidak dibaca
# tiap menit untuk jadwal eksekusi abatterystatus
jadwalEksekusi: 7
# batas minimal dan maksimal batrai android untuk di charger maupun lepas charger
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
  hai juragan bakso, batrai hape anda $persenBatrai persen perlu dicas lho.
  ```
  Di mana `$persenBatrai` adalah variabel yang berisi nilai persentase baterai saat ini. 📊

### Batas Waktu Penggunaan ⏳

Aplikasi ini hanya tersedia secara gratis hingga **27 Juni 2025**. Untuk yang mau pesan aplikasi berbayar hingga 15 tahun, silakan hubungi pembuat Abatterystatus melalui email. 📧

## Kontak 📬

Jika Anda memiliki pertanyaan atau ingin mendapatkan versi berbayar, silakan hubungi kami di:
- **Email**: [emasmoro@gmail.com](mailto:emasmoro@gmail.com)

---

Terima kasih telah menggunakan Abatterystatus! Semoga aplikasi ini bermanfaat untuk Anda. 🎉
```

### Emotikon yang Digunakan

- 🚀: Menunjukkan inovasi dan teknologi.
- 👋: Menyapa pengguna.
- 🌟: Menyoroti fitur utama.
- 🔊: Menggambarkan notifikasi suara.
- ⚙️: Menunjukkan pengaturan dan konfigurasi.
- ⏰: Menunjukkan penjadwalan.
- 🇮🇩: Menunjukkan dukungan bahasa Indonesia.
- 📁: Menunjukkan lokasi file.
- 📝: Menunjukkan isi file konfigurasi.
- ⏲️: Menunjukkan waktu eksekusi.
- 🔋: Menunjukkan baterai.
- 📊: Menunjukkan data dan statistik.
- ⏳: Menunjukkan batas waktu.
- 📧: Menunjukkan kontak.
- 📬: Menunjukkan komunikasi.
