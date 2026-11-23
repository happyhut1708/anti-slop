# antislop-15 — 15 Aturan Inti (Fork happyhut1708)

> Versi ringkas dari 40 aturan asli (v3.2.32). Dipakai bareng `DESIGN.md` — kalau konflik, `DESIGN.md` menang.
> Target: hemat token (dari ~23.000 ke ~4.000-6.000), tetap jaga hasil UI/copy tidak generik.
> Cara pakai: tempel file ini + `DESIGN.md` ke AI coding agent (Claude Code / Cursor / Codex) di tiap sesi, atau instal skill dari fork ini.
> Bukan alat bypass detektor AI. Bukan penjamin fakta — verifikasi semua angka dan klaim manual.

## Aturan (NEVER / ALWAYS, tanpa pengecualian kecuali disebut di DESIGN.md)

1. **NEVER pakai gradien ungu-biru, gradien neon, atau glow berlebihan.** Satu aksen warna saja per halaman, sesuai DESIGN.md.
2. **NEVER pakai badge "AI POWERED", ikon sparkle / magic / lightning, atau label Beta/New sebagai dekorasi.**
3. **NEVER pakai em dash (—) bertubi-tubi di copy.** Maksimal 1 per halaman, dan hanya kalau memang perlu.
4. **NEVER pakai kata klise AI:** Revolutionary, Seamless, Elevate, Unlock, Delve, Tapestry, Cutting-edge, Game-changer.
5. **NEVER mengarang angka, testimoni, logo klien, atau klaim kepatuhan (misal SOC 2).** Tidak ada data nyata = tulis `[PLACEHOLDER]`, jangan isi sendiri.
6. **ALWAYS beri alasan tertulis untuk tiap teknik visual.** Kalau jawabannya cuma "biar kelihatan bagus / aman", buang teknik itu.
7. **NEVER pakai template SaaS generik** (Hero → Subtitle → 2 CTA → Screenshot → Feature Grid → Testimoni → FAQ → CTA → Footer) tanpa alasan spesifik untuk urutan itu.
8. **ALWAYS satu ide per section, satu tugas utama per halaman.** Video/showreel di above the fold, bukan di bawah tumpukan kartu.
9. **NEVER pakai elemen palsu:** terminal palsu, tombol yang tidak berfungsi, statistik "10K+ users" tanpa sumber, pricing 3 tier dengan tier tengah di-highlight tanpa alasan.
10. **ALWAYS pakai tipografi sesuai DESIGN.md:** maksimal 3 keluarga font, headline jauh lebih besar dari body, monospace hanya untuk timecode / metrik.
11. **ALWAYS jaga kontras & aksesibilitas:** teks utama minimal 7:1, teks sekunder minimal 4.5:1, semua kontrol bisa dipakai keyboard, focus state terlihat.
12. **ALWAYS mobile dulu:** tidak ada horizontal overflow, tap target minimal 44px, video 9:16 terbaca penuh tanpa terpotong.
13. **NEVER biarkan motion / dekorasi mengganggu isi.** Animasi hanya kalau membantu user memahami, bukan sekadar hiasan.
14. **ALWAYS tulis komentar kode yang bermakna saja.** Buang banner ASCII, emoji, dan komentar yang mengulang isi kode.
15. **Delivery Gate — ALWAYS laporkan PASS/FAIL sebelum kirim, dengan bukti.** PASS hanya kalau: build jalan, console bersih, tiap tombol/link diklik dan berfungsi, tampilan dicek di desktop + mobile. Jangan tulis PASS tanpa memeriksa.

## Yang sengaja DIBUANG dari 40 aturan asli
- Aturan backend / database / arsitektur API enterprise.
- Aturan testing berat dan error-handling skala enterprise.
- Instruksi filosofis / abstrak ("Write like a senior craftsperson") — tidak terukur, boros token.
- Aturan yang duplikatif dengan DESIGN.md.

## Versi
- Fork: `happyhut1708/anti-slop`, `3.2.32-custom.1`
- Asli: `miqdadbadjuber/anti-slop` v3.2.32 (40 aturan, 19 Hard Gate / 12 Purpose-Gate / 9 Quality Locks)
