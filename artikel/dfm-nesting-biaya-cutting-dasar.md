---
article_id: CUT-11-01
title: "Panduan dasar design for manufacture, nesting, yield, setup, dan biaya cutting: istilah, komponen, dan cara kerja"
slug: "dfm-nesting-biaya-cutting-dasar"
description: "Pembaca dapat menjelaskan geometry simplification, common features, stock sizes, spacing, remnant, setup, programming, batch, cycle, secondary work, scrap, and change cost, istilah yang sering tertukar, komponen, mekanisme, serta pertanyaan awal yang perlu diajukan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-24"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-11
primary_intent: "Memahami fondasi design for manufacture, nesting, yield, setup, dan biaya cutting sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/dfm-nesting-biaya-cutting-dasar.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://www.iso.org/standard/83335.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
---

# Panduan dasar design for manufacture, nesting, yield, setup, dan biaya cutting: istilah, komponen, dan cara kerja

Halo, Sobat Cutting.co.id! Harga cutting yang tampak murah bisa berubah ketika gambar sulit diproduksi, lembar bahan tidak termanfaatkan, atau ada pekerjaan lanjutan yang tidak tertulis. Jawaban singkatnya: pahami dulu hubungan antara desain, susunan komponen di stock, waktu persiapan, waktu potong, pekerjaan sekunder, dan perubahan. Baru setelah itu bandingkan penawaran.

Design for manufacture (DFM) berarti menata geometri agar dapat dibuat secara konsisten dengan proses dan bahan yang tersedia. **Nesting** adalah penyusunan bentuk pada stock size (ukuran lembar atau batang bahan) untuk memakai ruang secara efisien. **Yield** menggambarkan porsi bahan yang menjadi bagian, sedangkan sisa yang tidak terpakai menjadi remnant atau scrap sesuai kondisi dan rute pengelolaannya. Setup, programming, batch, cycle, dan secondary work kemudian menjelaskan waktu serta aktivitas di luar gerakan potong. Hasil akhirnya tetap bergantung pada gambar revisi, material aktual, mesin, kontrol mutu, dan persetujuan proyek—hal yang belum dapat dipastikan dari istilah saja.

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
![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Definisikan kebutuhan sebelum meminta harga

Mulai dari fungsi bagian, kondisi kerja yang diketahui, jumlah dan pengulangan, material yang diizinkan, antarmuka dengan komponen lain, serta hasil penerimaan. Gambar kerja sebaiknya memiliki nomor dan revisi; paket fabrikasi yang terkendali dapat memuat dimensi, datum, material, toleransi, urutan kerja, titik inspeksi, dan dasar penerimaan. Halaman katalog [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya mengidentifikasi standar; persyaratan rinci tetap harus diambil dari teks berlisensi dan dokumen proyek yang berlaku.

Istilah berikut membantu memisahkan keputusan desain dari biaya proses:

| Istilah | Arti praktis | Pengaruh yang perlu ditanyakan |
| --- | --- | --- |
| Penyederhanaan geometri (geometry simplification) | Menyederhanakan sudut, kontur, lubang, atau detail yang tidak diperlukan fungsi | Apakah detail itu wajib, dan dapatkah dibuat dengan alat yang tersedia? |
| Fitur umum (common features) | Fitur berulang seperti lubang, slot, atau radius yang seragam | Apakah satu alat dan satu program dapat menangani pengulangan? |
| Ukuran stok (stock size) | Ukuran bahan yang benar-benar dibeli atau tersedia | Berapa ukuran dan ketebalan aktual, serta toleransi pemasoknya? |
| Jarak (spacing) | Jarak antarprofil dan dari tepi stok | Apakah jarak aman untuk kerf, penjepitan, panas, dan pemisahan? |
| Sisa bahan (remnant) | Sisa stok yang masih dapat diidentifikasi dan dipakai ulang | Bagaimana diberi label, disimpan, dan dimasukkan ke penyusunan berikutnya? |
| Hasil guna (yield) dan sisa buang (scrap) | Bagian bahan yang menjadi produk dibanding sisa yang tidak dipakai | Apakah definisi sisa dan satuan perhitungannya sama dalam penawaran? |
| Penyiapan (setup) dan pemrograman (programming) | Menyiapkan meja, penjepitan, alat, material, serta membuat atau memeriksa program | Dibebankan sekali per kelompok produksi atau tersebar per komponen? |
| Kelompok produksi (batch), siklus (cycle), pekerjaan sekunder | Kelompok produksi, waktu satu siklus potong, dan pembersihan/penyelesaian/penandaan setelahnya | Apa yang termasuk dan apa yang dikecualikan? |
| Biaya perubahan (change cost) | Dampak revisi pada program, material, penyiapan, inspeksi, dan jadwal | Siapa menyetujui perubahan dan bagaimana jejak revisinya disimpan? |

Sobat Cutting.co.id, jangan menyimpulkan yield hanya dari luas geometri. Spacing, arah serat atau tekstur, allowance, urutan potong, dan kebutuhan penjepitan dapat memaksa susunan berbeda. Karena itu minta contoh nest atau perhitungan berbasis stock aktual sebagai informasi pembanding, bukan sebagai jaminan hasil untuk semua proyek.

## Buat penawaran benar-benar sebanding

Minta setiap penyedia memecah harga menjadi material, nesting/programming, setup, cycle cutting, secondary work, pemeriksaan, pengemasan, dan transport. Nyatakan pula eksklusi: misalnya desain ulang, pengadaan material khusus, pengujian tambahan, lifting, atau rework. Menurut prinsip informasi konsumen dalam [UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999), total harga saja tidak menjelaskan isi pekerjaan; secara praktis, scope, asumsi, konsekuensi waktu-biaya, dan persetujuan perubahan perlu tercatat.

Gunakan satu lembar perbandingan dengan kolom: nomor revisi gambar, material dan stock, jumlah, basis yield, biaya setup, tarif atau dasar cycle, pekerjaan sekunder, inspeksi, masa berlaku penawaran, serta ketentuan bila gambar berubah. Jangan mengisi angka yang belum diberikan. Jika dua penawaran memakai definisi scrap atau batch berbeda, keduanya belum sebanding.

## Dokumen yang membuktikan hal berbeda

Berkas desain berbantuan komputer (CAD) menunjukkan geometri; drawing yang disetujui menunjukkan maksud dan revisi; daftar material menunjukkan identitas bahan; sertifikat material mengaitkan bahan dengan batch atau heat bila dipersyaratkan; laporan inspeksi menunjukkan apa yang diukur dan hasilnya; sedangkan metode kerja menjelaskan bagaimana proses dikendalikan. Sertifikat personal juga memiliki ruang lingkup metode dan masa berlaku—bukan bukti bahwa seluruh perusahaan, mesin, atau produk tertentu otomatis memenuhi persyaratan. Ringkasan [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) membantu melihat pentingnya sistem mutu, tetapi tidak membuka klausul rinci atau membuktikan hasil proyek tertentu.

Simpan hubungan antar-dokumen: nama file, revisi, tanggal, penerbit, dasar penerimaan, dan otorisasi. Foto atau label mesin dapat menjadi identifikasi aset, bukan bukti akurasi, kapasitas, atau kelulusan produk. Jika seseorang menyebut “bersertifikat” atau “sesuai SNI”, minta sertifikat lengkap, ruang lingkup, status berlaku, dan kaitannya dengan pekerjaan Anda. [NEEDS PROJECT-SPECIFIC REVIEW: GATE-03, GATE-04, GATE-07, GATE-13]

## Pertanyaan wajib kepada penyedia

Ajukan pertanyaan ini sebelum menyetujui program:

1. File dan revisi mana yang menjadi dasar pemotongan, dan siapa yang menyetujui revisi berikutnya?
2. Material, dimensi stock, dan identitas batch apa yang akan dipakai? Bagaimana remnant diberi label?
3. Bagaimana penyedia mendefinisikan yield, scrap, spacing, dan allowance dalam penawaran?
4. Setup dan programming dikenakan per batch, per material, atau per perubahan?
5. Apa yang dimaksud cycle: hanya waktu busur/potong, atau termasuk loading, unloading, dan handling?
6. Apakah deburring, marking, pemeriksaan dimensi, pengemasan, dan pengiriman termasuk?
7. Dokumen penerimaan apa yang diserahkan, dengan alat ukur dan dasar ukur yang mana?
8. Apa pemicu change cost, siapa yang memberi persetujuan, dan bagaimana pekerjaan dihentikan ketika revisi belum jelas?

Kawan Cutting.co.id, jawaban yang baik seharusnya menunjuk dokumen dan tanggung jawab, bukan sekadar “bisa”. Kapabilitas vendor tertentu tetap harus diverifikasi dari bukti terkini dan tinjauan teknis yang berwenang.

## Tanda bahaya dan biaya yang sering tersembunyi

Waspadai harga satuan tanpa basis material, “free setup” yang tidak menjelaskan batasnya, yield yang dihitung dari luas tanpa spacing, serta janji waktu tanpa definisi batch dan antrian. Perubahan kecil pada lubang atau kontur dapat memicu pemrograman ulang, nesting ulang, material baru, inspeksi ulang, dan pengiriman ulang. Catat permintaan, alasan, dampak waktu-biaya, persetujuan, dan revisi sebelum program dijalankan.

Jangan menganggap semua remnant otomatis dapat dipakai ulang atau semua scrap aman dibuang. Identitas, kontaminasi, tempat penyimpanan, pelabelan, pengangkutan, dan penerima menentukan rute limbah; [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021) menjadi salah satu rujukan kerangka lingkungan, bukan izin untuk mengklasifikasikan limbah tanpa data setempat. Untuk pekerjaan mesin dan cutting, pengendalian bahaya harus mengikuti aturan Indonesia dan kondisi tugas; [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) dapat menjadi pintu pemeriksaan, sementara detail kontrol memerlukan penilaian K3 aktual. [NEEDS CURRENT INDONESIAN K3 AND WASTE REVIEW: GATE-01, GATE-08, GATE-12]

## Penerimaan, serah terima, dan keputusan akhir

Tentukan sejak awal siapa memeriksa identitas material, dimensi, jumlah, kondisi tepi, tanda, dan dokumen. Checklist penerimaan sebaiknya menyebut nomor bagian, revisi gambar, alat atau metode ukur, hasil, tanggal, pemeriksa, dan tindakan bila tidak sesuai. Serah terima bukan sekadar barang tiba atau pembayaran dilakukan; status diterima, ditolak, atau diterima dengan penyimpangan harus memiliki dasar dan otorisasi tertulis. Jangan menjanjikan garansi atau kepatuhan hanya karena ada sertifikat umum; ruang lingkup kontrak dan rekaman aktual yang mengaturnya.

Shortcut “pilih penawaran termurah lalu rapikan detail belakangan” sering gagal karena biaya perubahan muncul setelah material dan program terlanjur disiapkan. Alternatif yang lebih aman adalah mengunci fungsi, revisi, material, definisi yield, pembagian setup-cycle-secondary work, dan kriteria penerimaan sebelum membandingkan angka. Untuk kasus struktural, keselamatan, atau toleransi kritis, minta tinjauan profesional sesuai proyek; artikel ini tidak memilih opsi terbaik atau menetapkan angka spesifikasi.

Jika Anda perlu membandingkan cara menyiapkan pertanyaan lokasi, lihat [contoh halaman laser cutting Yalimo](/laser-cutting-yalimo.html) dan [contoh halaman laser cutting Wonosobo](/laser-cutting-wonosobo.html). Keduanya bukan bukti otomatis tentang kapasitas penyedia untuk proyek Anda; gunakan hanya sebagai pengingat untuk memeriksa scope, material, dan akses.



## Kesimpulan: istilah menjadi keputusan yang dapat diaudit

DFM menyederhanakan geometri agar proses masuk akal; nesting menempatkan bagian pada stock; yield, remnant, dan scrap menjelaskan pemakaian bahan; setup, programming, batch, dan cycle menjelaskan waktu proses; secondary work dan change cost melengkapi biaya yang sering terlupakan. Langkah berikutnya adalah membuat lembar permintaan penawaran (RFQ) dengan gambar ber-revisi, material, jumlah, definisi biaya, dokumen penerimaan, dan pertanyaan perubahan, lalu meminta penyedia mengisi asumsi mereka. Teman Cutting.co.id, gunakan aturan operasi ini: jangan bandingkan harga sebelum scope dan bukti yang dibandingkan benar-benar sama; keputusan teknis final tetap memerlukan data proyek dan review yang kompeten.
