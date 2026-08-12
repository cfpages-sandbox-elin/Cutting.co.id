---
article_id: CUT-06-03
title: "Spesifikasi plasma, oxy-fuel, dan waterjet cutting: data, ukuran, toleransi, dan pemeriksaan asumsi"
slug: "plasma-flame-waterjet-cutting-spesifikasi"
description: "Pembaca dapat mengumpulkan input, menyatakan unit dan toleransi, memeriksa asumsi, serta menyiapkan spesifikasi plasma, oxy-fuel, dan waterjet cutting yang dapat ditinjau vendor."
status: draft
publication_date: "2025-08-31"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-06
primary_intent: "Menyusun spesifikasi terukur untuk plasma, oxy-fuel, dan waterjet cutting"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/plasma-flame-waterjet-cutting-spesifikasi.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `Mesin Advertising CNC Plasma Cutting Machine` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Spesifikasi plasma, oxy-fuel, dan waterjet cutting: data, ukuran, toleransi, dan pemeriksaan asumsi

Halo, Teman Cutting.co.id! Spesifikasi cutting yang dapat ditinjau penyedia (vendor) bukan sekadar menulis “potong plat 10 mm”. Dokumen yang berguna menyebut material dan kondisi awalnya, ukuran serta datum, proses yang diminta, toleransi, mutu tepi, jumlah, format berkas, pemeriksaan, dan apa yang belum diketahui. Tiga proses—plasma, oxy-fuel (nyala oksigen-bahan bakar), dan waterjet—memiliki batas proses berbeda; keputusan yang benar bergantung pada data pekerjaan, bukan nama mesin.

Jawaban singkatnya: mulai dari fungsi dan material, tetapkan satuan dan sistem koordinat, pisahkan ukuran nominal dari toleransi, lalu minta penyedia (vendor) mengonfirmasi kemampuan aktualnya. Jika tingkat mutu (grade) material, ketebalan efektif, kualitas tepi, atau dasar penerimaan belum tersedia, tandai sebagai asumsi dan jangan menjanjikan hasil. [NEEDS GATE-03/GATE-04: tingkat mutu (grade) material, dasar penerimaan (acceptance basis), dan kapabilitas penyedia (vendor) harus dikonfirmasi pada proyek.]

![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil yang dituju adalah paket spesifikasi satu halaman atau lampiran permintaan penawaran (RFQ) yang bisa dibaca sama oleh drafter, estimator, insinyur (engineer), dan vendor. Cantumkan identitas pekerjaan, nomor revisi, penerbit, tanggal, dan siapa yang berwenang menyetujui perubahan. Untuk bagian yang memengaruhi struktur, tekanan, pengangkatan, atau keselamatan, dokumen ini hanya menyiapkan input; desain dan persetujuan insinyur (engineer) tetap diperlukan.

Untuk memeriksa konteks mesin sebelum mengirim RFQ, Anda dapat melihat [rujukan plasma cutting pada halaman mesin](/cnc/mesin/advertising/plasma-cutting). Jika kebutuhan Anda ternyata beralih ke proses laser, bandingkan dulu [contoh halaman laser cutting](/laser-cutting-wonosobo.html) dan kembali ke tabel input di artikel ini; keduanya bukan bukti kapabilitas penyedia (vendor) untuk proyek Anda.

Sebelum meminta penawaran, siapkan gambar atau DXF/DWG yang status revisinya jelas, daftar part, material dan tebal, kuantitas, ukuran blank, datum, lubang atau fitur kritis, finishing setelah potong, serta cara bagian itu akan diukur. Nyatakan apakah ukuran berlaku sebelum atau sesudah finishing. Jika tidak ada informasi, tulis “belum ditentukan” dan minta pertanyaan balik, bukan angka rekaan.

## Langkah 1 — tetapkan batas pekerjaan

Tentukan apakah pekerjaan hanya pemotongan 2D atau mencakup marking, bevel, deburring, sorting, dan packing. Batas ini mencegah harga total terlihat murah karena utilitas, inspeksi, atau pengerjaan ulang belum masuk. Uraikan antarmuka: siapa menyediakan material, siapa memuat dan mengangkat, file apa yang menjadi master, dan siapa menerima hasil.

Pilih proses secara bersyarat. Plasma biasanya dipertimbangkan ketika laju pemotongan dan material konduktif menjadi prioritas; oxy-fuel memerlukan kombinasi material dan ketebalan yang kompatibel dengan reaksi pemotongan; waterjet dipertimbangkan ketika zona panas atau pengaruh termal perlu dihindari. Pernyataan itu adalah kerangka keputusan, bukan rating universal. Vendor harus mengembalikan rentang aktual untuk material, tebal, ukuran meja, dan mutu tepi yang diminta.

Tulis satuan secara eksplisit—misalnya mm dan derajat—serta definisikan datum A-B-C atau titik nol CAD. “Toleransi ±0,5” tidak lengkap tanpa satuan, fitur yang diukur, alat ukur, dan kondisi pengukuran. Bedakan toleransi dimensi, posisi lubang, sudut, kerataan, dan allowance untuk kerf (lebar material yang hilang karena proses). Jangan mengasumsikan kerf identik antarproses atau antarparameter.

Sobat Cutting.co.id, gunakan satu lembar “asumsi terbuka” untuk menandai setiap nilai yang belum diverifikasi. Lembar itu menghindarkan angka sementara terbaca sebagai persyaratan final.

Jika komponen terkait beban, tekanan, panas, atau keselamatan, hentikan pemilihan proses sampai gambar dan dasar penerimaan disahkan. Standar seperti SNI 1729:2020 dan abstrak standar ISO hanya mengidentifikasi lingkup dokumen; nilai desain dan acceptance harus berasal dari teks berlisensi serta spesifikasi proyek ([katalog SNI BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Langkah 2 — kumpulkan dan cocokkan bukti

Buat tabel input sebelum menulis angka penawaran:

| Kelompok | Isian minimum | Cara memeriksa |
| --- | --- | --- |
| Material | grade, bentuk (sheet/plate), tebal nominal dan aktual, heat/batch bila diwajibkan | cocokkan mill certificate atau dokumen pembelian dengan label dan gambar |
| Geometri | ukuran blank, datum, lubang, slot, bevel, radius, jumlah | overlay file revisi dengan drawing dan tandai fitur kritis |
| Proses | plasma, oxy-fuel, atau waterjet; urutan; marking; allowance | minta penyedia (vendor) menyatakan asumsi, bukan hanya nama mesin |
| Mutu | toleransi tiap fitur, kualitas tepi, burr/dross, kebutuhan finishing | sepakati metode dan alat ukur sebelum produksi |
| Serah-terima (handover) | laporan inspeksi, identitas part, sisa material, foto/rekaman bila perlu | tentukan format, penerbit, tanggal, dan status penerimaan |

Catat batch material, bahan habis pakai (consumable), dan produk kimia yang benar-benar digunakan bila relevan. ISO 3834-6 menjelaskan kerangka informasi kualitas, sedangkan aturan hazard communication OSHA dapat menjadi contoh mengapa label dan safety-data sheet perlu ditautkan; aturan OSHA bukan hukum Indonesia ([ISO 3834-6](https://www.iso.org/standard/83335.html), [OSHA 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)). Verifikasi komposisi, kompatibilitas, penyimpanan, dan pembuangan pada produk serta ketentuan Indonesia yang berlaku.

Minta vendor mengisi kolom “diterima”, “perlu klarifikasi”, dan “tidak tercakup”. Kapabilitas vendor, ukuran meja, parameter, dan hasil uji sampel awal (first-off) adalah bukti proyek-spesifik; jangan menggantinya dengan klaim “presisi tinggi”. Bila inspeksi diperlukan, tetapkan metode, cakupan (extent), alat, kalibrasi atau verifikasi, serta siapa yang berwenang menyatakan lulus. ISO 5817, ISO 17635, dan ISO 9712 dapat menjadi rujukan identitas QA/pemeriksaan tak merusak (NDT), tetapi abstraknya tidak memuat batas cacat atau setting alat ([ISO 5817](https://www.iso.org/standard/80209.html), [ISO 17635](https://www.iso.org/standard/85705.html), [ISO 9712](https://www.iso.org/standard/75614.html)).

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman adalah: (1) bekukan revisi dan daftar part; (2) validasi material, tebal, dan kondisi permukaan; (3) susun nesting dan arah potong sesuai datum serta allowance; (4) sepakati proses, parameter yang menjadi tanggung jawab vendor, dan kebutuhan sampel awal (first-off); (5) periksa sampel terhadap fitur kritis; (6) baru lanjutkan batch; (7) sortir, tandai, dan kemas sesuai daftar part.

Untuk plasma, minta penyedia (vendor) menyatakan kisaran tebal dan mutu tepi yang mampu dibuktikan pada material Anda, termasuk pengaruh heat-affected zone dan dross bila relevan. Untuk oxy-fuel, pastikan material dan perlindungan area kerja telah dinilai oleh penanggung jawab K3; jangan menyalin jarak, durasi fire watch, atau setelan gas dari panduan asing. Untuk waterjet, minta definisi taper, kemungkinan abrasive, pengelolaan air dan lumpur, serta bagaimana fitur kecil diukur. Semua angka tersebut harus berasal dari datasheet, prosedur vendor, atau uji sampel awal (first-off) yang disetujui—bukan asumsi artikel ini.

Perubahan setelah nesting dapat mengubah yield, waktu, dan harga. Simpan permintaan perubahan, alasan, konsekuensi biaya/waktu, persetujuan, dan nomor revisi. Praktik ini membuat penawaran dapat dibandingkan dan sejalan dengan prinsip informasi yang jelas dalam [UU Perlindungan Konsumen](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999); sumber tersebut tidak menjadi dasar untuk memprediksi sengketa atau hasil ganti rugi.

## Titik berhenti dan kondisi melanjutkan

Teman Cutting.co.id, berhenti sebelum start bila drawing tidak menyebut material atau datum, toleransi saling bertentangan, file CAD berbeda dari daftar part, atau vendor belum menyatakan asumsi proses. Berhenti juga bila pekerjaan menyentuh vessel, pipa bertekanan, ruang terbatas, bahan mudah terbakar, atau instalasi aktif. “Kosong” atau “tidak beroperasi” tidak otomatis aman; kondisi isolasi, atmosfer, izin, dan rencana penyelamatan memerlukan penilaian pemilik, K3, dan insinyur (engineer) ([Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

Kendali bahaya harus mengikuti kondisi lokasi: eliminasi atau substitusi bila mungkin, kendali rekayasa dan administratif, lalu alat pelindung diri (PPE) yang sesuai. Jangan mengarang nilai paparan, laju ventilasi, setelan listrik, atau konfigurasi silinder. [NEEDS GATE-01/GATE-08/GATE-09: aturan K3 terkini, kondisi lokasi, dan pengendalian tugas harus ditinjau pihak kompeten.] Detail penyiapan (setup) dan eksekusi lapangan berada di luar artikel ini.

## Verifikasi hasil dan serah terima

Sebelum menyatakan selesai, cocokkan nomor revisi, identitas material/part, jumlah, dimensi kritis, posisi fitur, kondisi tepi, dan status finishing. Rekam alat ukur dan kondisi pengukuran; bila hasil di luar toleransi, tahan part, buka nonkonformansi, dan minta keputusan disposition. Jangan menyebut “lulus SNI/ISO” hanya karena nama standar tercantum.

Paket serah terima minimal memuat drawing dan revisi yang dipakai, daftar part, catatan asumsi yang telah ditutup, laporan sampel awal (first-off) atau inspeksi sesuai kesepakatan, identitas batch/bahan habis pakai (consumable) yang relevan, daftar deviasi yang disetujui, dan status sisa pekerjaan. Sertifikat atau checklist bermakna jika mengidentifikasi item, tanggal, dasar penerimaan, hasil, dan pemberi otorisasi. [NEEDS GATE-07/GATE-10/GATE-13: metode ukur, bukti serah-terima (handover), dan kemampuan vendor harus diverifikasi pada proyek.]

## Menjawab jalan pintas yang sering dipilih

Jalan pintas (shortcut) yang sering dipilih adalah mengirim foto gambar dan meminta “harga potong per kilogram”. Cara itu gagal membandingkan kerf, toleransi, marking, deburring, inspeksi, transport, pajak, atau rework. Total harga tanpa rincian cakupan (scope) tidak menunjukkan layanan yang sama ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)). Alternatifnya, kirim RFQ dengan tabel input di atas dan minta penyedia (vendor) mengembalikan pengecualian serta asumsi tertulis.

## Kesimpulan

Spesifikasi plasma, oxy-fuel, dan waterjet yang siap ditinjau penyedia (vendor) berisi material terverifikasi, geometri ber-datum, satuan dan toleransi per fitur, mutu tepi, batas cakupan (scope), bukti proses, serta rencana inspeksi dan serah-terima (handover). Langkah Anda berikutnya: bekukan revisi gambar, isi tabel input, minta penyedia (vendor) menutup kolom asumsi, lalu lakukan review insinyur (engineer)/K3 untuk kondisi berisiko. Aturan operasinya sederhana: tanpa dasar penerimaan dan bukti kapabilitas yang cocok dengan pekerjaan, angka spesifikasi adalah permintaan klarifikasi—bukan janji hasil.

Kawan Cutting.co.id, jadikan pertanyaan klarifikasi dan bukti sampel awal (first-off) sebagai syarat sebelum batch berjalan; artikel ini tidak menggantikan persetujuan desain, K3, atau penerimaan proyek.
