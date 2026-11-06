# Web Surat Cinta

Halaman web statis sederhana untuk menyampaikan perasaan lewat surat digital. Dibuat dengan HTML, CSS, dan JavaScript tanpa framework atau proses build.

## Menjalankan secara lokal

1. Pastikan Python 3 terpasang, atau gunakan server web statis pilihanmu.
2. Dari folder proyek, jalankan:

   ```sh
   python -m http.server 8000
   ```

3. Buka <http://localhost:8000> di browser.

Kamu juga bisa membuka `index.html` langsung di browser, tetapi server lokal lebih cocok untuk pengembangan.

## Kustomisasi

- Ubah teks surat dan pilihan respons di `index.html`.
- Sesuaikan warna, tata letak, dan animasi di bagian `<style>` pada file yang sama.
- Tidak ada dependensi build. Font Google Fonts memerlukan koneksi internet; font fallback tersedia jika tidak tersambung.

## Lisensi

Proyek ini tersedia di bawah lisensi MIT. Lihat [LICENSE](./LICENSE).
