RESEARCH FINDER PRO — MOBILE WEB 0.1.0
Author: HARSANTOGanasBoys

APA YANG BISA DICOBA
- Buka index.html di browser modern.
- Pencarian metadata online OpenAlex (butuh internet).
- Filter tahun berjalan dan empat tahun sebelumnya.
- Simpan dan hapus artikel dalam localStorage browser.
- Deduplikasi berdasarkan DOI atau judul+tahun.
- Catatan pribadi lokal.
- Tabel penelitian terdahulu dasar.
- Ekspor koleksi ke CSV dan RIS.
- Identitas indeks Scopus/WoS tetap “Belum terverifikasi”.

PENTING
Ini adalah web app mobile yang bisa dibuka di HP, bukan APK native.
Untuk menjadikannya aplikasi PWA yang dapat dipasang dari Chrome, host berkas di HTTPS. File lokal dapat dibuka untuk penggunaan dasar tetapi PWA/service worker biasanya memerlukan HTTPS atau localhost.
Data tersimpan di browser yang sama dan bisa hilang jika data browser dibersihkan. Ekspor koleksi sebagai cadangan.

BATASAN
- Scopus API dan Web of Science API belum terhubung.
- Tidak menghasilkan XLSX/DOCX/PDF.
- Tabel editable saat ini belum menyimpan hasil edit semua sel sebagai dataset ekspor.
- Tidak ada klaim bahwa aplikasi telah diuji pada semua perangkat.
- Metadata dicari dari OpenAlex; status indeks resmi perlu diverifikasi melalui sumber resmi.

FITUR TAMBAHAN VERSI 0.1.1
- Tab Pemeriksaan Indeks Resmi.
- Tombol membuka pencarian Scopus dan Web of Science.
- Form catatan hasil pemeriksaan manual, URL bukti, catatan, dan tanggal.
- Status terverifikasi meminta URL bukti sebelum disimpan.
- Catatan pemeriksaan tersimpan lokal di browser.
Catatan: aplikasi tidak mengotomatisasi atau mengonfirmasi hasil situs eksternal. Pengguna harus memeriksa hasil secara langsung dan mencatat bukti yang valid. Status yang dipilih pengguna bukan verifikasi otomatis oleh aplikasi.

FITUR TAMBAHAN VERSI 0.1.2
- Tombol “Unduh artikel” pada hasil pencarian dan koleksi.
- Jika metadata OpenAlex menyediakan best_oa_location, aplikasi membuka tautan PDF/landing page yang tersedia.
- Jika tautan OA tidak tersedia, aplikasi membuka laman sumber/DOI dan mengingatkan pengguna agar mengunduh hanya jika aksesnya legal.
- Aplikasi tidak melewati paywall, tidak mengakali autentikasi, dan tidak menjamin setiap tautan akan berupa PDF.
