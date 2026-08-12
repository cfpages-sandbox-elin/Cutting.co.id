---
article_id: CUT-04-03
writing_contract_version: "native-id-v2"
title: "Spesifikasi toleransi, kerf, kualitas tepi, akurasi, dan acceptance: data, ukuran, toleransi, dan pemeriksaan asumsi"
slug: "toleransi-kerf-kualitas-cutting-spesifikasi"
description: "Pembaca dapat mengumpulkan input, menyatakan unit dan toleransi, memeriksa asumsi, serta menyiapkan spesifikasi toleransi, kerf, kualitas tepi, akurasi, dan acceptance yang dapat ditinjau vendor."
status: draft
publication_date: "2025-07-01"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-04
primary_intent: "Menyusun spesifikasi terukur untuk toleransi, kerf, kualitas tepi, akurasi, dan acceptance"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/toleransi-kerf-kualitas-cutting-spesifikasi.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/77795.html"
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

# Spesifikasi toleransi, kerf, kualitas tepi, akurasi, dan acceptance: data, ukuran, toleransi, dan pemeriksaan asumsi

Halo, Sobat Cutting.co.id! Jangan mulai dari kalimat “potong sesuai gambar”. Spesifikasi yang dapat ditinjau vendor harus menyebut datum dan ukuran, satuan, toleransi tiap fitur, batas kerf yang disepakati, mutu tepi, cara mengukur, serta keputusan lulus atau tidak lulus. Kerf adalah lebar material yang hilang akibat proses potong; nilainya memengaruhi ukuran bersih dan kompensasi jalur alat, tetapi bukan pengganti toleransi gambar.

Jawaban singkatnya: buat satu lembar spesifikasi yang memisahkan kebutuhan fungsi dari cara pembuatannya. Kunci dulu material, tebal, jumlah, referensi datum, ukuran nominal, toleransi, kondisi tepi, metode inspeksi, dan dokumen acceptance. Nilai angka, rentang proses, serta kecocokan untuk kondisi berisiko hanya boleh diisi dari gambar terbit, prosedur, data mesin, dan review engineer—bukan dari asumsi umum. [NEEDS GATE-01: nilai toleransi dan acceptance proyek belum tersedia]

![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil akhir yang realistis bukan janji “pasti presisi”, melainkan paket kerja yang bisa dibaca ulang oleh estimator, drafter, operator, pemeriksa, dan vendor. Paket itu sekurang-kurangnya berisi gambar dengan revisi, daftar material dan tebal, file potong yang identitasnya cocok, tabel karakteristik kritis, rencana pemeriksaan, serta formulir penyimpangan.

Tetapkan siapa yang berwenang menyetujui perubahan: pemilik desain atau engineer untuk fungsi dan antarmuka, vendor untuk kemampuan proses yang ditawarkan, dan pemeriksa untuk bukti hasil. ISO 17635 menempatkan metode, cakupan, teknik, personel, peralatan, kondisi permukaan, verifikasi kalibrasi, pelaporan, dan dasar acceptance sebagai bukti yang terpisah; satu hasil ukur tidak cukup untuk menyimpulkan mutu keseluruhan ([ISO 17635:2025](https://www.iso.org/standard/85705.html)).

Sebelum meminta penawaran, pastikan tersedia: satuan (misalnya mm), sistem koordinat atau datum, orientasi permukaan, status revisi, kuantitas, kebutuhan finishing, dan kondisi penerimaan. Jika salah satunya belum ada, tandai sebagai pertanyaan terbuka—jangan membiarkan vendor menebak.

## Langkah 1 — tetapkan cakupan

Tuliskan objek yang dipotong dan batas pekerjaan: pemotongan saja, deburring, pelapisan, penandaan, atau inspeksi. Bedakan ukuran bahan masuk, ukuran setelah potong, dan ukuran setelah finishing. Nyatakan antarmuka yang memang menjadi input, tanpa mengambil alih detail desain sambungan atau pekerjaan pemasangan; keduanya memerlukan dokumen dan persetujuan tersendiri.

Buat daftar karakteristik kritis berdasarkan fungsi. Contohnya, lubang yang menjadi referensi posisi memerlukan datum dan toleransi lokasi; tepi yang akan dilas memerlukan kondisi tepi dan kebersihan; bidang tampak memerlukan kriteria visual. Hindari label “rapi” atau “presisi” tanpa cara ukur.

Untuk setiap fitur, pakai format: nominal — toleransi — datum — metode ukur — rekaman. Toleransi umum hanya boleh dipakai jika gambar atau standar proyek menyatakannya. [NEEDS GATE-02: datum, toleransi umum, dan fitur kritis harus disetujui engineer/desainer]

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dari kecocokan identitas, bukan angka. Cocokkan nomor gambar dan revisi dengan file manufaktur berbantuan komputer (CAM), material, tebal, kuantitas, serta batch bahan bila ketertelusuran diwajibkan. Untuk pekerjaan yang melibatkan pengelasan, prosedur, kualifikasi juru las, material, proses, posisi, rentang tebal, kontinuitas, dan acceptance adalah rekaman berbeda; ISO 15614-1, ISO 9606-1, dan ISO 3834-6 membantu menjaga pemisahan itu ([ISO 15614-1:2017](https://www.iso.org/standard/51792.html), [ISO 9606-1:2012](https://www.iso.org/standard/54936.html), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)). Jangan menganggap kartu juru las atau spesifikasi prosedur pengelasan (WPS) otomatis membuktikan sambungan akhir diterima.

Kumpulkan bukti proses yang benar-benar relevan: identitas mesin dan program, verifikasi alat ukur, kondisi permukaan, metode sampling, foto atau peta fitur, dan laporan ketidaksesuaian. Bila mutu tepi terkait pelapisan, catat produk, batch, permukaan, dan status aplikasi; ISO 12944-5 memberi konteks sistem perlindungan korosi, bukan angka performa untuk produk tertentu ([ISO 12944-5:2019](https://www.iso.org/standard/77795.html)).

Gunakan tabel kecocokan sederhana:

| Item | Yang harus cocok | Bukti |
|---|---|---|
| Identitas | Gambar, revisi, file potong | daftar dokumen |
| Material | Spesifikasi, tebal, batch bila diminta | sertifikat atau laporan bahan |
| Geometri | Nominal, datum, toleransi, kerf allowance | gambar dan program |
| Tepi | burr, dross, bevel, kebersihan sesuai kebutuhan | kriteria visual/ukur |
| Acceptance | metode, extent, pemeriksa, disposisi | rencana inspeksi dan pengujian (ITP) dan laporan |

Sobat Cutting.co.id, bila kolom bukti kosong, statusnya bukan “lulus bersyarat”; statusnya “belum dapat diputuskan”. [NEEDS GATE-03: bukti material, program, alat ukur, dan personel belum diverifikasi]

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman dimulai dari pemeriksaan dokumen, lalu verifikasi bahan dan datum, kemudian first-off atau sampel awal sebelum kuantitas diteruskan. Ukur fitur yang paling memengaruhi fungsi lebih dahulu. Bandingkan ukuran bersih dengan toleransi gambar, dan catat kerf sebagai parameter proses yang diverifikasi—bukan angka yang diisi agar hasil tampak cocok.

Definisikan kualitas tepi secara operasional. Sebutkan apakah burr, dross, sudut tajam, taper, panas terpengaruh, atau perubahan warna boleh ada, pada permukaan mana, dan dengan metode apa diperiksa. Jika tepi akan menjadi permukaan las atau lapis, minta persyaratan persiapan permukaan dari dokumen proyek. Jangan menetapkan ambang numerik tanpa sumber dan persetujuan.

Acceptance harus menjawab empat pertanyaan: apa yang diperiksa, seberapa luas atau berapa sampel, siapa yang memutuskan, dan apa tindakan bila tidak sesuai. ISO 5817 membahas tingkat mutu ketidaksempurnaan las, sedangkan ISO 17635 mengingatkan bahwa tingkat acceptance pengujian tak merusak (NDT) tidak diterjemahkan satu banding satu dari tingkat mutu tersebut ([ISO 5817:2023](https://www.iso.org/standard/80209.html), [ISO 17635:2025](https://www.iso.org/standard/85705.html)). Karena itu, jangan menyalin tabel dari internet ke spesifikasi cutting.

Rujuk dokumen baja atau struktur yang memang ditetapkan proyek; halaman katalog SNI 1729:2020 hanya mengonfirmasi identitas publik standar, bukan membuka klausul, kombinasi, toleransi, atau acceptance ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)). [NEEDS GATE-04: standar pengendali, metode ukur, cakupan, dan nilai acceptance harus ditetapkan]

## Titik tahan dan kondisi berhenti

Tahan pekerjaan dan minta review ketika gambar tidak memiliki datum, material atau tebal berbeda dari penawaran, kerf mengubah ukuran fungsi, tepi akan dipakai untuk sambungan tetapi persiapannya tidak didefinisikan, alat ukur tidak terverifikasi, atau hasil first-off menyimpang. Hentikan juga bila pihak yang menandatangani acceptance tidak jelas.

Untuk kondisi berisiko, artikel ini tidak menggantikan desain atau persetujuan engineer. Pekerjaan lapangan dapat mengubah akses, cuaca, inspeksi, dan pengendalian bahaya; keputusan memindahkan pekerjaan ke lapangan memerlukan penilaian K3 dan dokumen tugas aktual. [NEEDS GATE-05: review engineer dan K3 untuk kondisi berisiko/lapangan]

## Verifikasi hasil dan serah terima

Sebelum serah terima, cocokkan daftar berikut dengan purchase order dan ITP:

- nomor gambar, revisi, material, tebal, dan kuantitas cocok;
- ukuran kritis, datum, toleransi, dan kondisi tepi memiliki hasil ukur atau catatan inspeksi;
- kerf allowance dan perubahan program terdokumentasi;
- alat ukur, metode, extent/sampling, dan identitas pemeriksa tercatat;
- ketidaksesuaian memiliki disposisi tertulis dan persetujuan berwenang;
- file gambar, program, laporan, sertifikat bahan, serta foto atau peta fitur dapat ditelusuri.

Jika hasil tidak memenuhi toleransi, jangan “mengoreksi” dengan mengubah angka acceptance. Buka laporan ketidaksesuaian (NCR) atau permintaan penyimpangan, jelaskan dampak fungsional, lalu minta keputusan pemilik desain. [NEEDS GATE-06: disposisi NCR dan persetujuan penyimpangan belum tersedia]

## Jalan pintas yang sering gagal

Jalan pintas yang sering dipilih adalah menulis “akurasi mesin ±X mm, tepi halus, QC standar” lalu meminta vendor menyesuaikan. Itu gagal karena tidak menjelaskan datum, fitur mana yang kritis, cara mengukur, kondisi tepi, atau siapa yang berhak menerima. Klaim kemampuan mesin juga bukan bukti hasil pada material, tebal, dan geometri tertentu.

Alternatifnya, kirim tabel karakteristik dan minta vendor mengonfirmasi kemampuan proses, asumsi kerf, rencana first-off, serta format laporan. Biarkan angka yang belum memiliki dasar tetap bertanda `[NEEDS GATE-07: konfirmasi kemampuan proses dan nilai angka oleh vendor serta engineer]`.

## Kesimpulan

Spesifikasi toleransi, kerf, kualitas tepi, akurasi, dan acceptance yang dapat dipertanggungjawabkan memisahkan kebutuhan fungsi, parameter proses, metode ukur, dan keputusan lulus. Langkah berikutnya adalah menerbitkan satu lembar dengan revisi terkunci, mengisi datum dan toleransi dari dokumen desain, meminta konfirmasi kemampuan vendor, lalu menyepakati first-off dan acceptance sebelum produksi penuh.

Kawan Cutting.co.id, jangan lanjut ketika asumsi utama belum tertulis atau bukti belum dapat ditelusuri. Minta review engineer dan pihak K3 untuk kondisi berisiko; nilai yang tidak tersedia harus tetap menjadi pertanyaan terbuka, bukan angka tebakan.

Untuk langkah administratif berikutnya, Anda dapat memakai format permintaan yang sama saat meminta penawaran [laser cutting Yalimo](/laser-cutting-yalimo.html) atau membandingkan kebutuhan [laser cutting Yahukimo](/laser-cutting-yahukimo.html); tetap kirim gambar, revisi, material, toleransi, dan acceptance yang sama agar vendor tidak menebak.
