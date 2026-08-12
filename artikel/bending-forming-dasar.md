---
article_id: CUT-09-01
title: "Panduan dasar bending, rolling, dan forming untuk sheet serta plate: istilah, komponen, dan cara kerja"
slug: "bending-forming-dasar"
description: "Pembaca dapat memahami geometri tekuk, radius dalam, arah material, balik elastis, dasar perhitungan bentangan, perkakas, kebutuhan gaya, urutan proses, distorsi, dan pemeriksaan hasil."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-11-22"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Memahami fondasi bending, rolling, dan forming untuk sheet serta plate sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/bending-forming-dasar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
---

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

# Panduan dasar bending, rolling, dan forming untuk sheet serta plate: istilah, komponen, dan cara kerja

Halo, Teman Cutting.co.id! Kesalahan paling mahal pada pekerjaan pelat sering dimulai sebelum mesin bergerak: orang menyebut proses menekuk (bending) untuk semua pembentukan, memberi ukuran akhir tanpa menjelaskan sisi acuan, atau meminta tonase dari tebal material saja. Jawaban singkatnya, menekuk bekerja pada garis atau zona tertentu, pembentukan lengkung berlanjut atau pengerolan (rolling) membentuk kelengkungan sepanjang benda kerja, sedangkan pembentukan dengan cetakan (forming) mencakup perubahan bentuk yang lebih luas melalui tekanan atau kombinasi keduanya. Ketiganya baru bisa dinilai setelah material, geometri, arah pengerolan, alat, urutan, dan kriteria pemeriksaan ditulis jelas.

Istilah dasar membantu percakapan, bukan otomatis menjadi resep produksi. Nilai radius minimum, gaya mesin, kompensasi balik elastis (springback), toleransi, dan penerimaan akhir bergantung pada kelas serta kondisi material, ketebalan, ukuran, perkakas (tooling), dan gambar kerja yang berlaku. [NEEDS PROJECT REVIEW: material, geometri, mesin, dan dasar penerimaan belum tersedia.] Artikel ini menjelaskan cara berpikir dan pertanyaan awal; bukan penetapan opsi terbaik atau angka spesifikasi untuk kasus tertentu.

![Ilustrasi jasa bending](/wp-content/uploads/2023/01/jasa-bending.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil yang baik bukan sekadar pelat “sudah berbentuk”. Anda perlu dapat menunjukkan bentuk target, ukuran yang diukur dari datum mana, material yang dipakai, dan bukti bahwa hasil diperiksa terhadap dokumen yang disetujui. Untuk itu, siapkan gambar atau model dengan revisi, daftar material, arah material bila relevan, urutan fitur, serta siapa yang berwenang menyetujui perubahan. Paket fabrikasi yang terkendali lazimnya mengaitkan identitas material, dimensi, datum, toleransi, urutan, titik tahan pemeriksaan, dan dasar penerimaan; katalog BSN untuk SNI 1729:2020 hanya mengonfirmasi identitas dokumen, bukan isi klausul atau toleransinya ([BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

Komponen yang perlu dikenali adalah benda kerja, penekan (punch) atau rol, cetakan (die) atau pasangan rol, pengukur belakang (back-gauge) atau penahan, meja dan penjepit, sistem penggerak, serta alat ukur. Pada pembentukan dengan cetakan, tambahkan penahan bahan awal (blank-holder) dan cetakan atas-bawah bila memang ada. Catat juga kelompok produksi (batch), nomor peleburan material (heat), dan dokumen sertifikat yang disyaratkan proyek. ISO 3834-6 menekankan bahwa dokumentasi mutu dan rekaman harus disesuaikan dengan kebutuhan pekerjaan, bukan digantikan oleh klaim umum “sudah standar” ([ISO 3834-6](https://www.iso.org/standard/83335.html)).

## Langkah 1 — tetapkan ruang lingkup

Mulailah dengan memisahkan tiga objek. **Geometri tekuk (bend geometry)** menjelaskan sudut, garis atau sumbu tekuk, panjang sayap (flange), dan **radius dalam (inside radius)** pada sisi dalam tekukan. **Arah material (material direction)** atau arah pengerolan menunjukkan orientasi lembaran terhadap garis tekuk; orientasi ini dapat memengaruhi kecenderungan retak atau hasil balik sehingga tidak boleh diasumsikan sama untuk semua kelas material. **Balik elastis (springback)** adalah pemulihan elastis setelah beban dilepas; sudut aktual dapat membuka dibandingkan posisi saat ditekan.

Rolling berbeda karena benda kerja melewati atau berputar di antara roller sehingga kelengkungan terbentuk sepanjang panjangnya. Forming adalah istilah payung: gaya, cetakan, dan penahan memaksa blank mengikuti geometri tertentu, sering dengan lebih dari satu zona deformasi. Jadi, “bending” tidak sama dengan “rolling”, dan “forming” bukan nama mesin tertentu.

Tetapkan pula batas antarmuka: tepi hasil pemotongan, lubang yang sudah dibuat, area las, lapisan pelindung (coating), serta ruang untuk alat ukur. Jangan mencampur ukuran sebelum dan sesudah balik elastis. **Faktor K (K-factor)** adalah parameter posisi sumbu netral yang dipakai dalam perhitungan bentangan; **panjang tekuk (bend allowance)** adalah panjang material pada zona lengkung yang dimasukkan ke perhitungan pola datar (flat pattern). Keduanya adalah konsep perhitungan, bukan nilai universal. Nilai aktual perlu dikalibrasi terhadap material, perkakas, dan metode kerja yang disetujui.

Teman Cutting.co.id, jika gambar hanya memuat ukuran luar tanpa datum, tanyakan: “Ukuran ini diambil dari tangent, permukaan dalam, atau permukaan luar?” Satu pertanyaan itu mencegah dua orang mengukur hasil yang sama dengan cara berbeda.

## Langkah 2 — kumpulkan dan cocokkan bukti

Buat lembar masukan sederhana sebelum meminta penawaran atau mengatur pekerjaan:

- identitas material, tebal nominal, ukuran blank, dan arah material;
- geometri: sudut, radius dalam, panjang flange, bentuk kontur, serta area yang tidak boleh tergores;
- metode yang direncanakan: press brake, tiga- atau empat-roller, atau forming dengan cetakan;
- perkakas: tipe penekan/cetakan atau diameter dan jarak rol, tanpa menganggap kapasitasnya cocok sebelum diverifikasi;
- urutan fitur dan allowance untuk perubahan bentuk, pemotongan, atau penyambungan berikutnya;
- dasar penerimaan: ukuran, profil, tampilan, dan pemeriksaan yang diminta pada gambar atau kontrak.

Jangan menebak **kebutuhan gaya tekan (tonnage)** dari tebal saja. Masukan gaya mencakup setidaknya panjang tekuk, geometri perkakas, material, dan konfigurasi mesin. [NEEDS SPECIFICATION REVIEW: rumus, kapasitas, dan faktor keselamatan harus berasal dari manual mesin serta desain yang berlaku.] Pada pengerolan, jumlah lintasan, posisi rol, dan urutan pengukuran memengaruhi distorsi; angka lintasan tidak dapat dipukul rata.

Pisahkan bukti proses dari bukti hasil. Catatan pengaturan (setup) menunjukkan apa yang dilakukan; pengukuran menunjukkan apa yang terjadi. Untuk pemeriksaan, ISO 17635 mengingatkan bahwa metode, cakupan, teknik, kondisi permukaan, personel, peralatan, dan dasar penerimaan adalah unsur terpisah; abstraknya tidak memberikan nilai lulus-gagal untuk proyek tertentu ([ISO 17635](https://www.iso.org/standard/85705.html)). Bila pemeriksaan memerlukan pengujian tanpa merusak (NDT), kompetensi personel dan ruang lingkup sertifikasinya juga harus cocok; ISO 9712 membahas kualifikasi personel NDT, bukan kelulusan seluruh produk ([ISO 9712](https://www.iso.org/standard/75614.html)).

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman adalah: (1) tinjau revisi gambar dan identifikasi material; (2) periksa kondisi mesin, perkakas, penahan, dan alat ukur; (3) rencanakan orientasi serta urutan tekuk atau lintasan pengerolan agar fitur yang sudah terbentuk tidak menghalangi langkah berikutnya; (4) lakukan pengaturan dan percobaan yang disetujui; (5) ukur sudut, radius, panjang sayap, dan distorsi terhadap acuan ukur (datum); (6) dokumentasikan hasil sebelum produksi berlanjut.

Saat menekan, gaya membentuk zona plastis sementara bagian lain menahan elastisitas. Setelah beban dilepas, balik elastis mengubah sudut atau radius. Pada pengerolan, distribusi gaya antar-rol mengatur kelengkungan dan dapat meninggalkan ujung lurus atau ovalitas; pada pembentukan, penahan yang tidak seimbang dapat menimbulkan kerutan atau penipisan lokal. Sebut gejalanya dengan tepat—perubahan sudut, puntiran, lengkung memanjang, kelengkungan menyamping, ovalitas, atau kerutan—karena penyebab dan tindakan koreksinya berbeda.

Jangan mengoreksi hasil dengan pukulan tambahan atau panas secara spontan. Perubahan seperti itu dapat mengubah material, meninggalkan jejak, atau merusak acuan ukur. Hentikan langkah dan minta peninjauan ketika hasil percobaan menyimpang, perkakas tidak teridentifikasi, material tidak tertelusur, atau urutan baru diperlukan. Catatan perubahan harus menyebut permintaan, alasan, dampak waktu/biaya, persetujuan, dan revisi dokumen.

## Titik tahan dan kondisi berhenti

Pekerjaan tidak boleh diteruskan ke produksi atau pemasangan bila salah satu berikut belum jelas: grade dan tebal material, radius atau datum pengukuran, kapasitas serta tooling yang terverifikasi, urutan yang memengaruhi akses, atau dasar penerimaan. Untuk pekerjaan di lapangan, lingkungan, akses angkat, sumber listrik, cuaca, area publik, dan pekerjaan panas dapat mengubah pengendalian risiko. UU No. 1 Tahun 1970 menjadi kerangka keselamatan kerja Indonesia, tetapi kontrol spesifik tetap memerlukan penilaian K3 dan kondisi lokasi ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

Sobat Cutting.co.id, pasang titik tahan (hold point) sebelum menyentuh benda kerja jika material tidak cocok dengan sertifikat, alat ukur tidak memiliki status verifikasi yang diminta, atau ada indikasi retak, sobek, delaminasi, dan deformasi yang tidak direncanakan. [NEEDS K3/ENGINEERING REVIEW: metode aman, batas operasi, dan keputusan kelayakan belum dapat ditetapkan dari artikel ini.] Jangan menyatakan “aman dipakai” atau “memenuhi SNI/ISO” hanya dari tampilan atau satu ukuran.

## Verifikasi hasil dan serah terima

Gunakan checklist yang menghubungkan setiap hasil dengan identitasnya:

1. Nomor item, revisi gambar, material dan batch tercatat.
2. Datum, sudut, inside radius, panjang flange, profil rolling, dan distorsi diukur dengan metode yang disepakati.
3. Alat ukur, kondisi permukaan, metode inspeksi, personel, dan laporan dapat ditelusuri.
4. Ketidaksesuaian diberi disposisi: terima dengan persetujuan, kerjakan ulang (rework) secara resmi, atau tolak—bukan dihapus dari catatan.
5. Rekaman pengaturan, perubahan, foto yang diizinkan, sertifikat, dan hasil pemeriksaan diserahkan bersama status penerimaan.

Sertifikat atau daftar periksa (checklist) hanya bermakna bila menyebut komponen, revisi, penerbit, tanggal, dasar, hasil, dan otorisasi. Serah terima fisik atau pembayaran tidak dengan sendirinya membuktikan kesesuaian atau garansi; ruang lingkup, durasi, pengecualian, dan tanggung jawab bukti harus mengikuti kontrak dan persetujuan yang berlaku.

## Jalan pintas yang sering terjadi

Jalan pintas yang sering dipilih adalah “pakai pengaturan pekerjaan sebelumnya; materialnya sama-sama plat.” Itu dapat gagal karena ketebalan, arah material, radius, perkakas (tooling), panjang tekuk, atau kondisi mesin berbeda. Bahkan dua lembar dengan nama material sama dapat memberi springback dan distorsi berbeda bila lot atau prosesnya berbeda. Alternatif yang lebih dapat dipertanggungjawabkan adalah membuat lembar pengaturan (setup sheet) berbasis gambar, melakukan percobaan yang disetujui, lalu mengukur hasil sebelum mengulangnya.

## Kesimpulan dan langkah berikutnya

Bending menekuk pada zona tertentu, rolling membentuk kelengkungan berlanjut, dan forming memakai gaya serta cetakan untuk geometri yang lebih luas. Kunci dasarnya adalah membedakan bend geometry, inside radius, material direction, springback, K-factor, dan bend allowance; mengenali komponen; menyusun urutan; lalu memisahkan bukti proses dari bukti inspeksi.

Langkah Anda berikutnya: minta gambar revisi, identitas material, acuan pengukuran, metode/perkakas yang diusulkan, dan dasar penerimaan sebelum membahas harga atau kapasitas. Untuk melihat bagaimana konteks wilayah dapat mengubah pertanyaan awal, gunakan [contoh halaman bending Yalimo](/bending-yalimo.html) dan [contoh halaman bending Yahukimo](/bending-yahukimo.html) sebagai bahan pertanyaan, bukan bukti kemampuan vendor. Jika salah satu data belum tersedia, tinggalkan [NEEDS PROJECT REVIEW] dan minta persetujuan teknis/K3 yang berwenang. Artikel ini memberi fondasi istilah dan alur—bukan keputusan pilihan untuk kasus tertentu atau pengganti verifikasi profesional.
