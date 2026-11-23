# DESIGN.md — Fork happyhut1708/anti-slop (3.2.32-custom.1)

> Arah desain POSITIF untuk fork ini. File ini menang atas aturan anti-slop kalau ada konflik.
> Fork dari miqdadbadjuber/anti-slop v3.2.32. Aturan ringkas 15 butir ada di `antislop-15.md`.
> Dipakai untuk: portfolio video / AI video + web, landing page klien luar negeri.

## 1. Produk & audiens
- Produk: jasa video AI + web (bundel), portfolio showreel, landing page produk.
- Audiens: klien luar negeri, brand, founder. Mereka menilai dari karya, bukan dari klaim.
- Satu halaman = satu tugas utama. Jangan jual semuanya sekaligus.

## 2. Suasana visual
- Dark, minimalist, kontras tinggi. Bukan SaaS cerah generik.
- Palet inti: hitam pekat `#0B0B0F` sebagai dasar, putih tulang `#F5F2EA` untuk teks utama, abu `#9A9AA3` untuk teks sekunder.
- Satu aksen saja per halaman, pilih salah satu: kuning `#FFD60A` atau merah `#FF3B30`. Jangan pakai keduanya sekaligus.
- DILARANG: gradien ungu-biru, gradien neon, glassmorphism berlebihan, glow di mana-mana.

## 3. Tipografi
- Display: font tebal, rapat, untuk headline (contoh: Archivo Black / Anton).
- Body: font bersih dan mudah dibaca (contoh: Inter / Plus Jakarta Sans).
- Monospace: hanya untuk timecode, metrik, dan label teknis (contoh: JetBrains Mono).
- Maksimal 3 keluarga font per halaman. Ukuran headline jauh lebih besar dari body, jangan semua ukuran mirip.

## 4. Layout
- Above the fold: showreel / hero video player dulu, baru headline + 1 CTA.
- Video adalah buktinya. Jangan sembunyikan video di bawah tumpukan teks dan kartu.
- Satu ide per section. Kalau satu section butuh 3 kartu untuk menjelaskan dirinya, section itu terlalu kabur — sederhanakan.
- Spacing longgar dan konsisten. Jarak antar section jauh lebih besar dari jarak antar elemen di dalam section.
- DILARANG: template Hero → Subtitle → 2 CTA → Screenshot → Feature Grid → Testimoni → FAQ → CTA → Footer kalau tidak ada alasan spesifik untuk urutan itu.

## 5. Video
- Aspect ratio: 16:9 untuk showreel desktop, 9:16 untuk potongan vertikal / Reels.
- Player harus bersih: kontrol jelas, tanpa elemen UI yang menutupi video.
- Thumbnail harus frame asli dari video, bukan ilustrasi generik.
- Jangan pakai autoplay dengan suara. Mute + caption kalau autoplay.

## 6. Copy
- Jujur dan spesifik. Sebutkan apa yang dibuat, untuk siapa, dan hasilnya apa.
- Angka, klien, dan testimoni: pakai yang nyata, atau tulis `[PLACEHOLDER]` — jangan pernah mengarang.
- DILARANG: "Revolutionary", "Seamless", "Elevate", "Unlock", "Delve", "AI POWERED", dan em dash bertubi-tubi.
- CTA spesifik, contoh: "Tonton showreel 60 detik" atau "Buat invoice pertama" — bukan "Get Started" / "Learn More" tanpa konteks.

## 7. Aksesibilitas & mobile
- Kontras teks utama minimal 7:1 di atas background gelap, teks sekunder minimal 4.5:1.
- Semua kontrol bisa dipakai lewat keyboard, ada focus state yang terlihat.
- Mobile dulu: tidak ada horizontal overflow, tap target minimal 44px, video 9:16 terbaca penuh tanpa terpotong.

## 8. Aturan konflik
- Kalau anti-slop melarang sesuatu yang DESIGN.md ini perintahkan secara spesifik (misal: satu aksen kuning di hero), DESIGN.md yang menang. Sebutkan konfliknya di laporan Delivery Gate.
- Kalau tidak ada arahan di sini, ikuti `antislop-15.md`.
