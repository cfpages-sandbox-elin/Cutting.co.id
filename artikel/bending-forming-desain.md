---
article_id: CUT-09-04
writing_contract_version: "native-id-v2"
title: "Perencanaan proses bending, rolling, dan forming untuk sheet serta plate: setup, workholding, urutan, dan dependensi"
slug: "bending-forming-desain"
description: "Pembaca dapat memetakan input, datum, setup, workholding, urutan operasi, allowance, pemeriksaan, dan dependensi lanjutan bending, rolling, dan forming untuk lembaran serta pelat."
status: draft
publication_date: "2025-12-02"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Merencanakan setup dan aliran kerja bending, rolling, dan forming untuk sheet serta plate agar dapat diproduksi konsisten"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/bending-forming-desain.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
---

# Perencanaan proses bending, rolling, dan forming untuk sheet serta plate: setup, workholding, urutan, dan dependensi

Halo, Sobat Cutting.co.id! Kualitas hasil pembengkokan (bending), pengerolan (rolling), atau pembentukan (forming) biasanya diputuskan sebelum benda kerja menyentuh mesin. Rencana yang baik mencatat data awal (input), datum, cara menahan material, urutan operasi, sisa bahan (allowance), dan titik pemeriksaan. Rencana yang hanya berisi “tekuk sesuai gambar” mudah menghasilkan bentuk yang tampak benar tetapi tidak pas saat dirakit.

Jawaban singkatnya: mulai dari fungsi dan antarmuka akhir, tetapkan datum yang dapat diulang, susun penyiapan (setup) dengan penahan benda kerja (workholding) yang tidak merusak permukaan, lalu urutkan operasi dari kondisi paling stabil menuju bentuk akhir. Verifikasi dilakukan pada benda kerja pertama (first-off) sebelum pekerjaan berulang. Nilai radius, pemulihan elastis (springback), sisa bahan (allowance), toleransi, material, dan dasar penerimaan tidak boleh ditebak; semuanya bergantung pada gambar terbit, kelas material (grade) dan kondisinya, kemampuan alat, serta persetujuan insinyur proyek (engineer proyek). [NEEDS PROJECT REVIEW: material, dasar desain, toleransi, dan kriteria penerimaan belum tersedia dalam paket ini.]

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-010`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi jasa bending](/wp-content/uploads/2023/01/jasa-bending.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `jasa bending` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-010]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->
![Ilustrasi jasa bending](/wp-content/uploads/2023/01/jasa-bending.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil yang dicari bukan sekadar sudut atau lengkung, melainkan komponen yang dapat diukur, dipindahkan, dirakit, dan diterima tanpa mengulang penyiapan. Penanggung jawab desain mengesahkan fungsi, antarmuka, dan toleransi; perencana proses menerjemahkannya menjadi lembar rute; operator menjalankan instruksi kerja yang sudah disetujui; pemeriksa merekam bukti. Artikel ini membantu pembagian kerja tersebut, bukan menggantikan keputusan pemilihan metode atau petunjuk pengoperasian mesin.

Sebelum membuat rute, kumpulkan gambar dan revisinya, model atau sketsa dengan datum, spesifikasi material dan arah serat bila relevan, daftar sambungan, kondisi permukaan, sisa bahan yang disetujui (allowance), kebutuhan pelapisan (coating), urutan perakitan, serta ruang untuk inspeksi dan pengangkatan. Paket fabrikasi terkendali lazimnya menghubungkan dokumen yang berlaku, dimensi, identitas material dan sambungan, toleransi, urutan fabrikasi, titik tahan (hold point), dasar penerimaan (acceptance basis), dan deviasi yang disetujui; katalog BSN hanya mengidentifikasi SNI, bukan membuka seluruh klausulnya ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

## Langkah 1 — tetapkan lingkup

Tuliskan apa yang dibentuk dan apa yang datang dari proses sebelumnya. Untuk lembar awal (blank) hasil pemotongan (cutting), catat nomor komponen (part), sisi referensi, arah pengerolan material bila ditentukan, tepi yang harus dilindungi, dan fitur yang belum boleh dikerjakan. Untuk pelat besar atau bentuk silinder, catat batas angkat, akses ukur, sambungan memanjang (longitudinal) atau melingkar (circumferential), serta permukaan yang akan menerima komponen lain. Dengan begitu, “selesai bending” berarti status yang dapat diperiksa, bukan asumsi visual.

Pisahkan tiga keputusan. Pertama, keputusan desain: bentuk, fungsi, beban, dan toleransi. Kedua, keputusan proses: datum, penyiapan (setup), alat bantu, urutan, dan sisa bahan (allowance). Ketiga, keputusan pelaksanaan: parameter mesin dan kontrol operator. Artikel ini berada pada keputusan kedua. Pemilihan bending versus rolling versus forming secara umum dan instruksi menjalankan mesin sengaja tidak dibahas di sini.

Buat matriks antarmuka sederhana: fitur masuk, datum yang dipakai, operasi yang mengubahnya, fitur keluar, dan proses lanjutan (downstream) yang bergantung padanya. Lubang yang harus sejajar, tepi yang menjadi referensi las, atau bidang dudukan yang harus rata adalah dependensi; jangan menempatkannya sebagai catatan kecil di akhir gambar.

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dengan identitas material yang benar-benar dapat ditelusuri: penamaan material (designation), tebal dan dimensi, nomor peleburan (heat) atau kelompok produksi (batch) bila diwajibkan proyek, serta sertifikat atau laporan yang merujuk ke item. Catat juga produk pelapis atau bahan habis pakai (consumable) yang akan dipakai kemudian, termasuk batch dan rekaman penyimpanan bila diminta. ISO 3834-6 menempatkan informasi material dan bahan habis pakai sebagai bagian dari pengendalian fabrikasi; lembar keselamatan produk membantu mengenali bahaya, tetapi contoh aturan OSHA bukan hukum Indonesia dan tidak memberi izin untuk menebak kompatibilitas, umur simpan, atau cara pencampuran ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html), [OSHA hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).

Lakukan pemeriksaan kecocokan sebelum menyusun penyiapan:

- Apakah revisi gambar, model, dan daftar material sama?
- Apakah datum pada gambar bisa disentuhkan kembali setelah benda diputar?
- Apakah sisa bahan dan garis ukur sudah dibedakan dari ukuran nominal jadi?
- Apakah penahan benda kerja menyisakan akses untuk alat ukur, las, pelapisan, dan pengangkatan?
- Apakah setiap nilai toleransi memiliki dasar penerimaan yang dapat diakses?

Jika salah satu jawaban bergantung pada standar berlisensi, prosedur klien, atau kondisi material yang belum ada, tahan keputusan dan minta [NEEDS DOCUMENT REVIEW: gambar acuan, sertifikat material, dan dasar penerimaan]. Jangan mengisi celah itu dengan tabel radius generik dari internet.

## Langkah 3 — jalankan urutan kerja

Susun rute dalam urutan yang menjaga referensi. Tandai material dan datum pada blank; periksa kerusakan, geram tajam (burr), dan orientasi. Lakukan penyiapan awal dengan permukaan tumpu yang bersih dan titik penahan yang mencegah geser tanpa membuat penyok. Rekam konfigurasi perlengkapan penahan (fixture), ganjal (shim), pembatas (stop), dan alat ukur sebagai identitas penyiapan, bukan hanya foto.

Berikutnya lakukan operasi yang mengunci geometri utama saat akses dan kekakuan masih baik. Untuk beberapa tekukan, dahulukan fitur yang akan tertutup atau sulit dicapai setelah lipatan berikutnya, tetapi pastikan langkah itu tidak menghilangkan datum untuk operasi berikut. Pada pengerolan (rolling) atau pembentukan (forming) bertahap, catat tahap antara dan titik ukur; bentuk antara menjadi kontrol terhadap akumulasi deviasi, bukan sekadar pekerjaan sementara.

Sisa bahan (allowance) harus terlihat di rute: sisakan material untuk pemangkasan, sambungan, atau kompensasi yang memang disetujui, dan tandai kapan sisa itu dihapus. Jangan mengubah ukuran jadi hanya karena hasil benda kerja pertama (first-off) tidak sesuai sebelum penyebabnya dipahami. Pemulihan elastis (springback), variasi tebal, dan perubahan arah dapat menggeser hasil; koreksi harus mengikuti prosedur dan otorisasi proyek, bukan intuisi operator.

Setelah setiap penyiapan, lakukan pemeriksaan yang menjawab risiko berikutnya. Ukur datum dan fitur kritis sebelum memindahkan benda. Cocokkan profil dengan templat atau alat ukur yang ditentukan. Setelah operasi terakhir, lakukan uji pasang tanpa paksaan (dry-fit) terhadap antarmuka dan simpan identitas komponen, revisi penyiapan, alat ukur, hasil, serta status nonkonformitas. Metode, cakupan, teknik, personel, kondisi permukaan, status verifikasi alat, laporan, dan dasar penerimaan adalah bukti terpisah; ISO 17635 juga mengingatkan bahwa level penerimaan pemeriksaan tak merusak (NDT) tidak otomatis sama dengan level mutu pengelasan ([ISO 17635:2025](https://www.iso.org/standard/85705.html), [ISO 9712:2021](https://www.iso.org/standard/75614.html)).

## Titik tahan dan kondisi berhenti

Hentikan rute sebelum pembentukan (forming) berikutnya jika material, revisi, atau datum tidak cocok; perlengkapan penahan bergerak atau merusak permukaan; sisa bahan hilang; hasil benda kerja pertama keluar dari toleransi; atau akses pengukuran tidak tersedia. Jangan “mengejar ukuran” dengan pemanasan, penekanan ulang, atau pemotongan tambahan tanpa instruksi tertulis dan tinjauan desain. Untuk bagian struktural, bertekanan, pengangkat, atau keselamatan-kritis, [NEEDS QUALIFIED DESIGN REVIEW: kelayakan penggunaan, sisa umur, dan metode koreksi harus disahkan pihak berwenang proyek].

K3 juga menjadi titik tahan, bukan catatan alat pelindung diri (PPE) di akhir. Identifikasi energi gerak, titik jepit, massa yang diangkat, tepi tajam, bahan kimia, ventilasi, dan pekerjaan panas; pilih pengendalian rekayasa dan administratif sebelum PPE. Kewajiban keselamatan kerja harus dibaca dari aturan Indonesia yang berlaku dan kondisi lokasi, termasuk UU No. 1 Tahun 1970 dan Permenaker No. 5 Tahun 2018 ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)). Tidak ada detail paket ini yang menetapkan jarak, durasi pengawasan api, ventilasi, atau pilihan PPE; minta persetujuan K3 setempat sebelum mulai.

## Verifikasi hasil dan serah terima

Serah terima (handover) harus menjawab “apa yang dibuat, dengan dasar apa, dan siapa yang menerima”. Serahkan gambar serta revisinya, kartu rute (route card), identitas material, log penyiapan dan perlengkapan penahan, rekaman sisa bahan dan benda kerja pertama, hasil ukur, laporan pemeriksaan tak merusak bila dipersyaratkan, daftar nonkonformitas dan disposisinya, serta deviasi yang disetujui. Setiap rekaman sebaiknya memuat item, revisi, tanggal, pemeriksa, alat atau metode, hasil, dasar penerimaan, dan otorisasi.

Jangan menyamakan daftar periksa kosong dengan penerimaan. Tanyakan apakah proses lanjutan membutuhkan datum tertentu, permukaan bebas pelapis, atau akses sambungan sebelum komponen dikirim. Bila ada perubahan ruang lingkup, tulis permintaan, alasan, dampak waktu/biaya, persetujuan, dan revisi; harga total saja tidak menunjukkan pekerjaan apa yang termasuk ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)). Kawan Cutting.co.id, simpan bukti ini bersama nomor komponen (part) agar masalah di proses berikutnya tidak kembali menjadi perdebatan ingatan. Untuk membandingkan kebutuhan lapangan, gunakan [contoh halaman bending Yalimo](/bending-yalimo.html) dan [contoh halaman bending Yahukimo](/bending-yahukimo.html) hanya sebagai rujukan tujuan layanan, bukan sebagai bukti kapasitas atau hasil proyek.

## Jalan pintas yang sering gagal

Jalan pintas yang umum adalah memakai satu penyiapan lama untuk semua lembaran atau pelat dengan alasan bentuknya mirip. Kesamaannya bisa menipu: kelas material (grade), tebal, arah material, kondisi permukaan, datum, dan kebutuhan proses lanjutan dapat berbeda. Perlengkapan penahan lama mungkin menutup titik ukur atau memberi beban lokal; sisa bahan lama mungkin sudah tidak berlaku. Alternatif yang lebih aman adalah membuat lembar penyiapan baru berbasis revisi dan material aktual, lalu membuktikannya dengan satu benda kerja pertama dan titik ukur yang disepakati sebelum produksi berulang.

## Kesimpulan

Perencanaan bending, rolling, dan forming yang konsisten memetakan input, datum, cara menahan benda, urutan, sisa bahan, pemeriksaan, dan dependensi dalam satu rute yang dapat ditelusuri. Sobat Cutting.co.id, langkah berikutnya adalah meminta paket gambar terbit, sertifikat material, dasar penerimaan, dan persetujuan K3/tinjauan desain yang relevan; setelah itu susun lembar penyiapan dan titik tahan untuk benda kerja pertama. Tanpa bukti tersebut, rencana ini hanya kerangka kerja—bukan izin untuk menetapkan ukuran, kapasitas, kepatuhan, atau kelayakan komponen.
