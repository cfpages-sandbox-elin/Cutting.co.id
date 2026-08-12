---
article_id: CUT-08-01
title: "Panduan dasar turning, bubut CNC, boring, dan korter: istilah, komponen, dan cara kerja"
slug: "bubut-korter-turning-dasar"
description: "Pembaca dapat menjelaskan benda kerja berputar, sumbu, pencekaman, simpangan putar, penyangga ujung, perataan muka, pembubutan, boring, pembuatan ulir, akses pahat, pasangan ukuran, permukaan, inspeksi, dan konteks perbaikan—termasuk istilah yang sering tertukar, komponen, mekanisme, serta pertanyaan awal yang perlu diajukan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-22"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-08
primary_intent: "Memahami fondasi turning, bubut CNC, boring, dan korter sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Kawan Cutting.co.id"
final_route: "/artikel/bubut-korter-turning-dasar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-009`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi bubut korter 2](/wp-content/uploads/2023/02/bubut-korter-2.jpeg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `bubut korter 2` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-009]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Panduan dasar turning, bubut CNC, boring, dan korter: istilah, komponen, dan cara kerja

Halo, Kawan Cutting.co.id! Banyak permintaan bubut berhenti di kata “korter” atau “turning”, padahal dua istilah itu belum menjawab benda kerja diputar atau alat potong yang bergerak, bidang mana yang dikerjakan, dan bagaimana hasilnya akan diperiksa. Jawaban singkatnya: pembubutan (turning) adalah keluarga proses ketika benda kerja berputar terhadap pahat; bubut dengan kendali numerik komputer (CNC) mengotomatisasi gerak tersebut dengan program; pembesaran lubang (boring) memperbesar atau memperbaiki lubang yang sudah ada; sedangkan korter adalah sebutan lapangan yang biasanya mengarah pada pembesaran lubang, terutama pada komponen berukuran besar.

Istilah itu baru menjadi keputusan teknis setelah Anda mencocokkannya dengan gambar, datum, material, akses pahat, toleransi, kondisi permukaan, dan cara inspeksi. Ukuran, putaran, pemakanan, atau pilihan mesin tidak boleh ditebak dari nama pekerjaan saja. [NEEDS PROJECT REVIEW: toleransi, material, ukuran, dan metode penerimaan harus ditetapkan dari gambar atau instruksi kerja yang berlaku.]

![Ilustrasi bubut korter 2](/wp-content/uploads/2023/02/bubut-korter-2.jpeg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil yang realistis dari pekerjaan dasar ini adalah permukaan atau lubang yang mengikuti gambar dan dapat dibuktikan dengan rekaman ukur. Orang yang meminta pekerjaan perlu menyebut fungsi komponen, bidang acuan, ukuran nominal, toleransi bila tersedia, material, jumlah komponen, dan apakah pekerjaan dilakukan di bengkel atau di lokasi. Pelaksana perlu memastikan mesin, pencekaman, pahat, alat ukur, dan prosedur keselamatan sesuai kondisi aktual. Jika salah satu data itu kosong, keluaran yang sah baru berupa klarifikasi, bukan janji ukuran.

Pisahkan tiga hal sejak awal: geometri yang diminta, proses yang mungkin dipakai, dan bukti penerimaannya. “Lubang harus pas” misalnya belum menjelaskan diameter, kebulatan, keselarasan sumbu, atau pasangan porosnya. Tanyakan juga apakah komponen akan dipakai kembali, diperbaiki, atau dibuat baru; konteks itu menentukan data awal dan pemeriksaan yang perlu disimpan. Untuk mengenali istilah layanan yang lebih spesifik, Anda dapat melihat penjelasan singkat tentang [pekerjaan korter](/bubut/korter) dan [bubut CNC](/bubut/cnc), lalu kembali ke gambar komponen Anda sendiri.

## Langkah 1 — tetapkan batas pekerjaan

Benda kerja berputar (*rotating work*) adalah kondisi ketika benda menjadi sumber gerak utama. Pada bubut konvensional atau CNC, poros utama (spindle) memutar benda dan pahat bergerak relatif terhadap sumbu itu. Sumbu memanjang lazim disebut Z, sedangkan gerak mendekati atau menjauhi garis pusat lazim disebut X; penamaan pada kontrol tertentu dapat berbeda, sehingga manual mesin tetap menjadi acuan. Pembesaran lubang dapat memakai benda kerja berputar dengan batang pahat masuk ke lubang, atau konfigurasi lain sesuai mesin. “Korter” bukan kelas akurasi; pastikan dulu pekerjaan yang dimaksud memang membesarkan, menyelaraskan, atau memulihkan lubang.

Tentukan antarmuka yang tidak boleh berubah: acuan ukur (datum), bahu, alur, ulir, alur pasak, permukaan perapat, dan area yang harus tetap dapat dipasang. Catat juga akses pahat dan ruang untuk mengukur. Pekerjaan perbaikan pada poros, rumah bantalan, atau dudukan dapat mengubah keselarasan, celah kerja, dan penahanan bagian mesin; aturan keselamatan kerja Indonesia, termasuk Permenaker No. 38 Tahun 2016, menuntut pengamanan energi dan bagian bergerak, bukan sekadar memakai pelindung diri. OSHA 1910.147 dan 1910.212 dapat menjadi rujukan pembanding Amerika Serikat, bukan pengganti aturan atau prosedur lokasi ([Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016), [OSHA 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147), [OSHA 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212)).


## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dari gambar atau sketsa yang memiliki versi jelas. Tandai acuan ukur (datum) dan sumbu, lalu cocokkan dengan benda nyata: bekas pencekaman, kerusakan, korosi, atau perubahan bentuk tidak otomatis menjadi ukuran desain. Pencekaman (chucking) adalah cara benda dijepit, misalnya dengan cekam (chuck), collet, pelat muka (faceplate), atau perangkat cekam (fixture). Penyimpangan putar (runout) adalah selisih saat permukaan atau sumbu diperiksa terhadap acuan putar; nilainya harus diukur pada lokasi dan kondisi yang ditetapkan, bukan dinilai dari mata.

Gunakan kepala lepas (tailstock) atau penyangga ujung (center) bila dukungan ujung diperlukan, tetapi pastikan lubang penyangga dan panjang benda memang mendukungnya. Catat apakah benda dijepit di satu ujung, dua ujung, atau perlu pembalikan. Pembalikan dapat memindahkan acuan ukur, sehingga rencana referensi dan pemeriksaan antarpenyiapan harus jelas. Untuk pembesaran lubang, ukur kondisi lubang sebelum proses: diameter di beberapa posisi, kemungkinan ketirusan, keselarasan, dan sisa dinding. Jangan menganggap satu pembacaan cukup untuk diagnosis.

## Langkah 3 — jalankan urutan kerja

Urutan konseptualnya adalah: telaah gambar dan risiko; siapkan benda serta acuan ukur; pilih pencekaman yang tidak merusak fungsi; setel referensi; lakukan pemotongan awal; sisakan material yang cukup untuk tahap akhir; lalu lakukan tahap akhir (finishing) dan pemeriksaan. Perataan muka (facing) meratakan muka, pembubutan (turning) membentuk diameter luar atau kontur, pembuatan alur (grooving) membuat alur, dan pembuatan ulir (threading) membentuk ulir. Pada pembesaran lubang, batang pahat memperbesar atau mengoreksi lubang; proses ini berbeda dari pengeboran awal (drilling) yang membuat lubang dengan mata bor.

Akses pahat (tool access) berarti pahat dapat mencapai seluruh bidang yang diminta tanpa menabrak cekam, bahu, dinding lubang, atau perangkat cekam. Akses yang tidak cukup dapat memaksa perubahan pahat, orientasi, atau urutan. Pasangan ukuran (fits) menjelaskan hubungan dua komponen—misalnya poros dan lubang—bukan sekadar “longgar” atau “tekan”. Kondisi permukaan (surface) mencakup arah bekas pahat dan kebutuhan perapat; angka kekasaran hanya boleh diambil dari gambar atau spesifikasi yang sah.

Pada CNC, program mengatur koordinat, urutan, dan kompensasi, tetapi tidak menggantikan verifikasi titik nol, simulasi, uji jalan tanpa pemotongan (*dry run*) yang disetujui, serta pemeriksaan benda pertama. Program yang benar untuk satu pencekaman dapat salah untuk pencekaman lain. Sobat Cutting.co.id, perlakukan program, koreksi koordinat (*offset*), dan revisi gambar sebagai rekaman terkendali; jangan menyalin angka dari pekerjaan lama tanpa memeriksa konteksnya.

## Titik berhenti dan kondisi berhenti

Hentikan pekerjaan dan minta tinjauan bila acuan ukur tidak dapat ditetapkan, benda bergeser, penyimpangan putar melampaui kriteria yang disepakati, pahat tidak memiliki akses aman, atau ditemukan retak, deformasi, dan dinding sisa yang tidak diketahui. Untuk perbaikan komponen yang terhubung dengan energi tersimpan, bagian bergerak, atau sistem bertekanan, isolasi dan pelepasan energi harus mengikuti prosedur pemilik serta aturan K3 yang berlaku; artikel pengantar ini tidak memberi urutan isolasi atau izin hidup kembali ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

## Verifikasi hasil dan serah-terima

Daftar periksa serah-terima minimal berisi identitas komponen dan revisi gambar; metode pencekaman dan acuan ukur; ukuran yang diperiksa beserta alat ukurnya; kondisi permukaan; status ulir, alur, dan bahu; hasil penyimpangan putar atau keselarasan bila dipersyaratkan; catatan penyimpangan dan disposisinya; serta siapa yang menyetujui penggunaan. Untuk pemeriksaan tak merusak (NDT), metode, cakupan, teknik, kondisi permukaan, kompetensi personel, status alat, dan dasar penerimaan merupakan bukti yang terpisah. Ringkasan resmi ISO 17635 menekankan bahwa metode NDT dan tingkat penerimaan tidak dapat diperlakukan sebagai terjemahan satu-banding-satu, sementara ISO 9712 membahas kompetensi personel; keduanya bukan pengganti prosedur proyek ([ISO 17635:2025](https://www.iso.org/standard/85705.html), [ISO 9712:2021](https://www.iso.org/standard/75614.html)).

## Jalan pintas yang perlu dihindari

Jalan pintas yang sering muncul adalah “langsung korter sedikit sampai pin masuk”. Itu dapat menghilangkan material yang dibutuhkan untuk keselarasan (alignment), menghasilkan lubang tirus (taper), atau menyembunyikan masalah pencekaman. Alternatif yang lebih dapat dipertanggungjawabkan ialah mengukur sebelum proses, menetapkan datum dan ukuran sasaran, menyisakan tahap akhir, kemudian memeriksa lubang dan pasangan komponennya dengan metode yang disepakati.

## Kesimpulan

Pembubutan menjelaskan hubungan benda berputar dan pahat; bubut CNC mengeksekusi gerak itu secara terprogram; pembesaran lubang atau korter menangani lubang yang sudah ada. Istilah perataan muka, pembubutan, pembuatan ulir, pencekaman, penyimpangan putar, penyangga ujung, akses pahat, pasangan ukuran, kondisi permukaan, dan inspeksi baru bermakna jika dikaitkan dengan acuan ukur, fungsi, bukti ukur, dan kondisi keselamatan.

Langkah Anda berikutnya: kumpulkan gambar revisi, tandai acuan ukur dan antarmuka, ukur kondisi awal, lalu ajukan pertanyaan “bagian mana yang wajib tetap, bagaimana penerimaannya, dan siapa yang menyetujui?”. Teman Cutting.co.id, gunakan dasar ini untuk menyamakan bahasa—bukan untuk menetapkan pilihan mesin, angka pemotongan, toleransi, atau izin operasi tanpa tinjauan teknis proyek.
