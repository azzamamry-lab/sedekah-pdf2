# Sedekah Subuh — Landing Page (Desain Halaman 2 PDF)

Landing page Sedekah Subuh untuk Yayasan Nur Mirah. Desain **ditiru persis** dari
halaman 2 PDF referensi.

## 🌐 Link Live

**https://azzamamry-lab.github.io/sedekah-pdf2/**

## Struktur (sesuai halaman 2 PDF)

1. **Header** — latar PUTIH, logo + navigasi + tombol "Dukung Sekarang"
2. **Hero** — 2 kolom: teks kiri, FOTO kanan (relawan menyiapkan makanan)
   - 3 ikon: Mudah & Aman, Berdampak Nyata, Transparan
   - Overlay di foto: "Kebaikan kecil hari ini, berarti besar bagi mereka."
   - Kotak putih: "Berbagi untuk Hari yang Lebih Baik"
3. **Mengapa Sedekah Subuh?** — 4 pilar dengan ikon lingkaran hijau muda
4. **Program Utama** — kartu krem 2 kolom: "Dapur Darurat Yayasan Nur Mirah"
   - Kotak hijau muda: "Kebutuhan operasional selama 30 hari" + "± Rp 30.000.000"
   - Foto relawan + kartu putih "300 - 400 porsi makan setiap hari"
   - Overlay: "Makanan hari ini, energi untuk hari esok."
5. **Program Lainnya** — 4 kartu foto (Bantuan Sosial, Dukungan Pendidikan,
   Pemberdayaan Masyarakat, Respon Kemanusiaan)
6. **Cara Ikut Sedekah Subuh** — 4 langkah timeline dengan panah penghubung
7. **Kebaikan yang Berkelanjutan** — foto sunrise + 3 item ikon
8. **FAQ** — 6 pertanyaan, 2 kolom
9. **Footer** — latar abu muda, 3 kolom

## Fitur

- Responsif penuh (sudah diuji di 390px, tanpa overflow)
- Menu mobile dengan tombol Escape (aksesibilitas keyboard)
- FAQ accordion
- Tanpa dependensi, tanpa build step

## Palette

| Warna | Kode | Dipakai untuk |
|---|---|---|
| Hijau utama | `#1F5C3E` | Tombol, aksen |
| Hijau tua | `#16432E` | Judul |
| Hijau muda | `#E4F2E9` | Latar ikon, kotak info |
| Krem | `#F7F2E8` | Kartu Program Utama |
| Abu muda | `#F3F3F1` | Kotak FAQ, footer |

## Tipografi

- **Judul**: Fraunces (serif)
- **Body**: Plus Jakarta Sans

## Foto

Semua dari Wikimedia Commons, lisensi bebas komersial.
Daftar lengkap: `img/SUMBER-DAN-LISENSI.txt`

## Yang Masih Perlu Diisi

- Nomor rekening dan QRIS (tidak ada di PDF referensi)
- Kontak dan link sosial media asli
- Nama yayasan (masih "Yayasan Nur Mirah" dari referensi)

## Menjalankan Lokal

```bash
python -m http.server 8091
```
lalu buka http://localhost:8091
