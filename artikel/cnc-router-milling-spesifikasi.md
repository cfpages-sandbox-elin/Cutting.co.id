---
article_id: CUT-07-03
writing_contract_version: "native-id-v2"
title: "Spesifikasi CNC routing, milling, engraving, dan drilling: data, ukuran, toleransi, dan pemeriksaan asumsi"
slug: "cnc-router-milling-spesifikasi"
description: "Pembaca dapat mengumpulkan input, menyatakan unit dan toleransi, memeriksa asumsi, serta menyiapkan spesifikasi CNC routing, milling, engraving, dan drilling yang dapat ditinjau vendor."
status: draft
publication_date: "2025-10-01"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-07
primary_intent: "Menyusun spesifikasi terukur untuk CNC routing, milling, engraving, dan drilling"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/cnc-router-milling-spesifikasi.html"
technical_review: required
sources:
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
---

# Spesifikasi CNC routing, milling, engraving, dan drilling: data, ukuran, toleransi, dan pemeriksaan asumsi

Halo, Teman Cutting.co.id! Spesifikasi CNC yang dapat ditinjau vendor bukan sekadar menulis “potong sesuai gambar”. Dokumen yang berguna menyebut proses, material, ukuran dengan datum, satuan, toleransi, kualitas tepi atau permukaan, jumlah, serta bukti pemeriksaan. Dengan itu vendor dapat mengonfirmasi kemampuan dan Anda membandingkan penawaran pada dasar yang sama.

Jawaban singkatnya: mulai dari fungsi komponen dan fitur yang benar-benar kritis, lalu ubah menjadi tabel input–output yang terukur. Nilai toleransi, sisa pemesinan (allowance), kapasitas mesin, dan metode inspeksi tidak boleh diasumsikan; semuanya bergantung pada material, geometri, alat, penyiapan (setup), dan persyaratan proyek. [NEEDS PROJECT REVIEW: material, geometri, datum, toleransi, dan dasar penerimaan belum ditentukan.]

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-008`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi jasa CNC](/wp-content/uploads/2023/01/jasa-CNC.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `jasa CNC` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-008]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi jasa CNC](/wp-content/uploads/2023/01/jasa-CNC.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil akhir yang dituju adalah lembar spesifikasi dan berkas gambar/CAD yang bisa dibaca estimator, operator, pemeriksa mutu, dan pemberi persetujuan. Cantumkan nomor dokumen, revisi, pemilik keputusan, dan status persetujuan. Persetujuan engineer tetap diperlukan bila komponen memikul beban, memengaruhi keselamatan, atau menjadi bagian dari mesin.

Sebelum menulis angka, siapkan model atau gambar dengan datum yang jelas, daftar fitur (lubang, slot, kontur, ukiran), jenis proses yang diharapkan, material beserta kondisi awalnya, kuantitas, dan tujuan penggunaan. Jangan menulis klaim kesesuaian tanpa standar dan persetujuan yang benar-benar berlaku.

## Langkah 1 — tetapkan lingkup

Nyatakan apakah pekerjaan mencakup routing kontur lembaran, milling permukaan atau kantong, engraving (pengukiran dangkal), drilling (pengeboran), atau kombinasi. Pisahkan pekerjaan desain dari manufaktur: siapa yang menyediakan model, siapa yang menentukan datum, dan siapa yang menyetujui perubahan. Antarmuka seperti lubang baut, permukaan referensi, dan ruang gerak alat harus ditandai sebagai fitur kritis.

Tuliskan juga yang tidak dikerjakan. Artikel ini tidak menggantikan desain, pemilihan mesin, perencanaan setup, atau persetujuan engineer; detail antarmuka dan eksekusi lapangan memerlukan dokumen proyek tersendiri. Jika komponen terkait pengaman atau bagian bergerak, spesifikasi harus meminta verifikasi keselamatan sebelum produksi. Panduan pengendalian energi OSHA dapat menjadi rujukan umum untuk memisahkan kondisi servis dari operasi, tetapi bukan pengganti ketentuan K3 Indonesia ([OSHA 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147)).

Teman Cutting.co.id, tanyakan: “Fitur mana yang menentukan fungsi, dan apa akibatnya bila bergeser?” Jawaban itu menentukan datum, toleransi, serta prioritas inspeksi—bukan sekadar memperbanyak angka desimal.

## Langkah 2 — kumpulkan dan cocokkan bukti

Buat matriks agar setiap persyaratan memiliki sumber dan cara verifikasi:

| Item | Yang dicatat | Bukti atau metode cek |
|---|---|---|
| Material | tingkat mutu/deskripsi (grade), ketebalan atau diameter, kondisi awal, kelompok produksi (batch) bila diwajibkan | sertifikat atau identitas material; konfirmasi substitusi |
| Geometri | dimensi nominal, datum, orientasi, fitur kritis, chamfer/radius | gambar ber-revisi dan model yang sama |
| Proses | routing, milling, engraving, drilling; alat atau strategi yang disepakati | konfirmasi kemampuan vendor; jangan menebak parameter |
| Toleransi | toleransi umum dan khusus per fitur, satuan, allowance | basis desain/proyek; [NEEDS TOLERANCE BASIS] bila belum ada |
| Permukaan | kekasaran, burr, tepi tajam, perlakuan setelah proses | simbol gambar atau kriteria tertulis |
| Kuantitas | jumlah, kelompok produksi (lot), kebutuhan sampel awal (first-off) atau sampel | pesanan pembelian (purchase order) dan rencana pemeriksaan |
| Serah-terima (handover) | laporan ukur, identitas bagian, deviasi | daftar dokumen penerimaan |

Pisahkan fakta, asumsi, dan keputusan. “Tebal 12 mm” adalah input jika ada gambar; “bisa dipotong satu setup” hanyalah asumsi yang harus dikonfirmasi. Bila material atau produk pelapis belum pasti, mintalah identitas produk dan batch; informasi terdokumentasi membantu menjaga mutu proses.

Untuk inspeksi, sebutkan alat, titik ukur, kondisi permukaan, dan siapa yang berwenang menerima. ISO 17635 dan ISO 9712 menempatkan metode, cakupan, personel, peralatan, status verifikasi, laporan, dan dasar penerimaan sebagai item terpisah; abstraknya tidak memberi nilai penerimaan atau interval kalibrasi. Tulis “ukur sesuai prosedur proyek” dan lampirkan prosedurnya, bukan mengarang ambang sendiri ([ISO 17635:2025](https://www.iso.org/standard/85705.html), [ISO 9712:2021](https://www.iso.org/standard/75614.html)).

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman:

1. Bekukan revisi gambar, unit, datum, material, kuantitas, dan tujuan fitur.
2. Minta vendor menandai kemampuan mesin, ukuran benda kerja, penjepitan, akses alat, dan risiko deformasi sebagai konfirmasi tertulis.
3. Tetapkan fitur kritis dan metode ukurnya; gunakan pemeriksaan sampel awal (first-off) sebelum kelompok produksi penuh bila risiko atau ketidakpastian tinggi.
4. Catat deviasi yang diusulkan. Perubahan alat, material, setup, urutan proses, atau datum tidak setara tanpa persetujuan pemilik desain.
5. Setelah proses, cocokkan hasil ukur dengan revisi yang sama dan simpan identitas bagian/kelompok produksi.

Jika lubang samping atau pola lubang menjadi antarmuka, jelaskan sumbu, kedalaman, ulir, dan referensinya di gambar; [contoh layanan side-hole drilling](/cnc/mesin/side-hole-drilling) hanya membantu merumuskan pertanyaan, bukan bukti kapasitas atau toleransi proyek. Untuk milling umum, [referensi layanan CNC milling](/cnc/milling) juga bukan pengganti konfirmasi tertulis vendor.

## Titik henti dan kondisi berhenti

Hentikan penerbitan untuk produksi ketika datum bertentangan, unit tidak konsisten, toleransi tidak memiliki basis, material belum teridentifikasi, atau fitur kritis tidak punya metode ukur. Hentikan juga bila vendor mengganti material, alat, setup, atau proses tanpa persetujuan. [NEEDS HOLD-POINT APPROVAL: tetapkan pihak yang boleh menyetujui deviasi dan sampel awal.]

Untuk mesin yang disentuh saat servis atau penyesuaian, isolasi energi dan verifikasi kondisi aman harus mengikuti prosedur tempat kerja serta ketentuan Indonesia yang berlaku; artikel ini tidak menyediakan urutan penguncian, setting pengaman, atau izin restart. Sobat Cutting.co.id, anggap permintaan “langsung jalan saja” sebagai sinyal untuk memeriksa kembali asumsi, bukan sebagai persetujuan teknis.

## Verifikasi hasil dan serah terima

Checklist penerimaan minimal memuat nomor revisi, identitas material/kelompok produksi, jumlah, daftar fitur kritis, hasil ukur aktual, alat ukur dan status verifikasinya, catatan nonkonformitas, keputusan disposisi, serta tanda tangan pihak berwenang. Simpan file CAD/gambar yang benar-benar dipakai, bukan hanya PDF tanpa riwayat revisi. Jika hasil tidak memenuhi toleransi, jangan mengubah angka setelah fakta; buka permintaan deviasi atau kerjakan ulang berdasarkan keputusan tertulis.

Shortcut yang sering dipilih adalah mengirim screenshot CAD dengan catatan “toleransi standar”. Ini gagal ketika vendor memakai standar umum yang berbeda atau ketika lubang referensi dan permukaan dudukan memiliki kebutuhan khusus. Alternatif yang lebih andal ialah memberi tabel fitur kritis, menyebut standar toleransi yang disetujui, dan meminta vendor mengembalikan pertanyaan klarifikasi sebelum harga atau jadwal dikunci.


[UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) menjadi rujukan umum keselamatan kerja Indonesia; kewajiban spesifik tetap memerlukan penilaian K3 lokasi dan persetujuan berwenang. OSHA 1910.212 adalah contoh persyaratan penjagaan mesin Amerika Serikat, bukan pengganti aturan Indonesia [OSHA 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212).

## Kesimpulan

Spesifikasi CNC routing, milling, engraving, dan drilling yang siap ditinjau berisi fungsi, material, datum, dimensi, satuan, toleransi, kualitas permukaan, kuantitas, proses yang dikonfirmasi, metode inspeksi, dan aturan deviasi. Langkah berikutnya adalah minta engineer atau pemilik desain mengisi [NEEDS PROJECT REVIEW] di atas, lalu kirim paket revisi yang sama kepada vendor untuk konfirmasi kemampuan dan sampel awal. Kawan Cutting.co.id, jangan menyatakan komponen “lulus” hanya dari satu ukuran atau katalog mesin; penerimaan tetap bergantung pada bukti proyek dan persetujuan yang berwenang.
