---
article_id: CUT-11-03
title: "Spesifikasi design for manufacture, nesting, yield, setup, dan biaya cutting: data, ukuran, toleransi, dan pemeriksaan asumsi"
slug: "dfm-nesting-biaya-cutting-spesifikasi"
description: "Pembaca dapat mengumpulkan input, menyatakan unit dan toleransi, memeriksa asumsi, serta menyiapkan spesifikasi design for manufacture, nesting, yield, setup, dan biaya cutting yang dapat ditinjau vendor."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-31"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-11
primary_intent: "Menyusun spesifikasi terukur untuk design for manufacture, nesting, yield, setup, dan biaya cutting"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/dfm-nesting-biaya-cutting-spesifikasi.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
---

# Spesifikasi design for manufacture, nesting, yield, setup, dan biaya cutting: data, ukuran, toleransi, dan pemeriksaan asumsi

Halo, Sobat Cutting.co.id! Harga cutting yang tampak murah dapat berubah ketika ukuran bahan, arah serat, toleransi, jumlah setup, atau sisa material ternyata belum disepakati. Spesifikasi yang dapat ditinjau vendor bukan sekadar gambar dan jumlah komponen. Isinya harus mengunci data, unit, toleransi, cara menghitung nesting dan yield, pekerjaan setup, serta batas biaya.

Jawaban singkatnya: buat satu lembar spesifikasi yang menghubungkan fungsi komponen dengan data geometrinya, material dan ketebalan, kuantitas, toleransi, aturan nesting, kebutuhan penyiapan (setup), metode pemeriksaan, dan format penawaran. Tandai setiap asumsi yang belum dibuktikan. Nilai yield, waktu, dan biaya baru dapat dibandingkan setelah vendor menyatakan mesin, material aktual, kerf, strategi lintasan alat (toolpath), dan pekerjaan yang termasuk. [NEEDS GATE-02, GATE-03, GATE-04, GATE-07, GATE-10: konfirmasi proyek dan pemeriksaan kompeten sebelum angka final atau penerimaan.]

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

Mulailah dari fungsi dan hasil yang harus diterima. Tulis nama komponen, fungsi singkat, kondisi penggunaan yang relevan, jumlah per batch, jumlah batch, dan apakah komponen akan dirakit, dilas, dibengkokkan, atau dipasang ke bagian lain. Sertakan nomor gambar, revisi, tanggal rilis, dan siapa yang berwenang menyetujui perubahan.

Lembar input minimum sebaiknya memuat:

- file sumber yang dikirim (misalnya format CAD dan gambar PDF), satuan, datum, skala, dan orientasi;
- material, tingkat mutu atau penetapan material, ketebalan, bentuk stok, arah serat atau tekstur bila berpengaruh, serta kebutuhan sertifikat atau ketertelusuran;
- daftar part number, kuantitas baik, kuantitas cadangan yang disetujui, dan penandaan tiap part;
- dimensi kritis, geometri lubang atau slot, area yang tidak boleh diberi tanda, serta toleransi umum dan toleransi khusus;
- proses setelah cutting, seperti deburring, bending, coating, atau inspeksi tambahan;
- titik serah terima: komponen lepas, kit berlabel, atau paket yang sudah diproses lanjut.

Unit harus tertulis di judul atau blok informasi, bukan hanya diasumsikan dari kebiasaan. Pisahkan dimensi nominal dari batas atas-bawah. Jika toleransi belum ditetapkan, tulis “menunggu persetujuan desain”, bukan membiarkan vendor memilih diam-diam. Untuk komponen yang memengaruhi kekuatan, tekanan, pengangkatan, putaran, atau keselamatan, gambar dan toleransi harus ditinjau engineer yang bertanggung jawab; artikel ini tidak menggantikan persetujuan itu.

Paket fabrikasi yang terkendali lazimnya mengaitkan dokumen pengendali dan revisi, fungsi, datum, material, sambungan, toleransi, urutan kerja, titik inspeksi, basis penerimaan, dan deviasi yang disetujui. Gunakan dokumen proyek dan standar yang memang berlaku.

## Buat penawaran benar-benar sebanding

Nesting adalah penempatan banyak profil pada stok agar pemakaian bahan, jumlah lembar, dan sisa dapat dihitung. Yield adalah rasio bahan yang menjadi part yang diterima terhadap bahan yang dialokasikan menurut definisi yang Anda sepakati. Jangan menyamakan yield tinggi dengan biaya terendah: pola yang menghemat luas dapat menambah waktu pemotongan, pierce, perpindahan, atau penanganan.

Minta vendor mengembalikan tabel yang memisahkan paling tidak:

| Komponen penawaran | Yang harus dinyatakan |
| --- | --- |
| Data bahan | ukuran stok yang diasumsikan, tingkat mutu (grade), ketebalan, sertifikat atau pengganti yang diizinkan |
| Nesting dan yield | jumlah lembar, luas part, definisi sisa, arah orientasi, dan apakah kerf dihitung |
| Penyiapan (setup) | pemuatan, referensi nol, perlengkapan atau penjepitan benda kerja, pergantian material, pemrograman, dan sampel awal |
| Proses | metode cutting, operasi lanjutan, penandaan, deburring, pembersihan, dan pengepakan |
| Biaya | item satu kali, biaya per part atau per kelompok produksi, material, bahan habis pakai, inspeksi, transport, pajak, dan opsi |
| Asumsi dan eksklusi | akses, pengangkatan, utilitas, desain ulang, pekerjaan ulang, pengujian, dan perubahan revisi |

Total harga tanpa rincian tidak memberi tahu apakah survei, desain, bahan habis pakai, transport, pengujian, pekerjaan ulang, pajak, atau dokumentasi sudah termasuk. Untuk menjaga perbandingan, kirim permintaan penawaran (RFQ) yang sama kepada semua penyedia dan minta mereka mengisi format yang sama. Prinsip transparansi ruang lingkup ini membantu konsumen meminta informasi yang dapat dibandingkan, tanpa menjadikannya nasihat hukum atau janji hasil sengketa ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)).

Tuliskan juga aturan perubahan. Setiap perubahan harus menyebut permintaan asal, alasan, konsekuensi biaya dan waktu, persetujuan, serta revisi file yang dipakai. Jika vendor memakai stok yang berbeda dari RFQ, minta persetujuan tertulis sebelum nesting diulang. Kawan Cutting.co.id, di sinilah banyak “selisih kecil” menjadi tagihan besar: bukan karena rumusnya sulit, melainkan karena batas inputnya bergeser.

## Dokumen yang membuktikan hal berbeda

Pisahkan jenis bukti agar tidak tertukar. Gambar dan model menunjukkan geometri yang diminta; lembar material atau mill certificate mengaitkan bahan dengan penetapan/tingkat material (designation) dan kelompok produksi; laporan pengukuran menunjukkan hasil pada sampel atau part tertentu; catatan setup menunjukkan bagaimana pekerjaan dijalankan; sedangkan sertifikat personel hanya berbicara tentang lingkup metode, proses, rentang, dan masa berlaku orang tersebut.

Sertifikat personel memiliki lingkup tertentu dan tidak otomatis membuktikan seluruh perusahaan, mesin, material, hasil cutting, atau persetujuan desain. Minta salinan dokumen yang relevan, nomor identifikasi, penerbit, tanggal, lingkup, dan hubungan dokumen itu dengan kelompok pekerjaan.

Untuk coating atau consumable, catat produk, batch, dokumen keselamatan atau teknis yang berlaku, dan persetujuan substitusi. Jangan menyimpulkan kompatibilitas, umur layanan, atau parameter proses dari nama dagang saja. Bila material sisa terkontaminasi, jalur penyimpanan dan pembuangannya perlu ditentukan oleh aturan lokal dan pihak berwenang; spesifikasi cutting bukan tempat untuk mengklasifikasikan limbah tanpa karakterisasi.

## Pertanyaan wajib kepada penyedia

Kirim pertanyaan berikut bersama RFQ dan minta jawaban per nomor:

1. File, satuan, datum, dan revisi apa yang akan Anda jadikan master?
2. Material dan ukuran stok apa yang diasumsikan? Apakah pengganti memerlukan persetujuan?
3. Bagaimana Anda mendefinisikan yield, sisa, dan sisa potongan (scrap)? Apakah kerf, jalur masuk, jalur keluar, dan lubang kecil masuk hitungan?
4. Berapa setup yang diperkirakan, dan kondisi apa yang memicu setup tambahan?
5. Apa yang termasuk pemrograman, sampel awal (first-off), pemeriksaan dimensi, penandaan, deburring, dan pengepakan?
6. Instrumen atau metode apa yang dipakai untuk dimensi kritis, dan rekaman apa yang diserahkan?
7. Bagaimana part diberi identitas agar tidak tertukar setelah nesting dan pemotongan?
8. Apa batas kemampuan yang perlu ditinjau engineer: toleransi, deformasi panas, sambungan, atau antarmuka?
9. Bagaimana perubahan revisi, part kurang, kerusakan, dan rework disetujui serta dicatat?
10. Item apa yang jelas-jelas dikecualikan dari harga dan jadwal?

Jawaban harus merujuk pada konfigurasi mesin dan material yang benar-benar akan dipakai. Tidak ada bukti kapabilitas vendor tertentu di dalam artikel ini, sehingga jangan mengubah jawaban RFQ menjadi klaim “bersertifikat”, “SNI”, atau “pasti presisi” tanpa bukti primer yang masih berlaku.

## Tanda bahaya dan biaya yang sering tersembunyi

Waspadai penawaran yang hanya menampilkan harga per kilogram atau per meter tanpa jumlah part, stok, setup, dan definisi scrap. Red flag lain adalah toleransi “standar mesin” tanpa angka dan tanpa metode ukur; yield tinggi tanpa gambar nesting; material “setara” tanpa designation; serta janji jadwal yang tidak menyebut antrean, approval, atau revisi.

Biaya tersembunyi dapat muncul dari file yang perlu diperbaiki, stok tidak tersedia, pergantian ketebalan, fixture tambahan, pemuatan manual, marking, deburring, inspeksi ulang, pengemasan khusus, transport, akses, atau rework. Minta setiap item menjadi baris terpisah dengan pemicu yang jelas. Jika ada pekerjaan panas atau proses lain di lokasi, penilaian K3 harus mengikuti kondisi aktual—akses, ventilasi, sumber listrik, bahan mudah terbakar, lalu lintas, dan keadaan darurat—bukan menyalin resep asing. [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) menjadi titik rujuk, tetapi detail kontrol harus ditetapkan penanggung jawab K3 untuk tugas dan lokasi tersebut.

Shortcut yang sering dipilih adalah menyetujui harga terendah lalu membiarkan vendor “menyesuaikan gambar”. Itu dapat mengubah ukuran stok, orientasi, toleransi, atau proses tanpa jejak. Alternatif yang lebih aman: bekukan revisi, minta tabel asumsi, minta contoh layout nesting atau representasi datanya, lalu setujui penyimpangan satu per satu sebelum produksi.

## Penerimaan, serah terima, dan keputusan akhir

Sebelum pekerjaan dimulai, tetapkan siapa memeriksa apa. Pemilik desain memeriksa fungsi, datum, dan toleransi; vendor memeriksa kesesuaian input terhadap program dan mencatat hasil proses; penerima memeriksa identitas, kuantitas, dimensi kritis, kondisi tepi, dan dokumen yang dipersyaratkan. Buat formulir yang memiliki nomor part, revisi, tanggal, alat atau metode ukur, hasil, status, dan tanda tangan pihak berwenang.

Serah terima bukan hanya pemindahan barang. Paketnya dapat mencakup daftar part, revisi file, catatan material atau kelompok produksi (batch) bila diminta, hasil inspeksi, daftar deviasi yang disetujui, dan catatan sisa atau scrap. Cakupan garansi, durasi, pengecualian, jalur respons, dan tanggung jawab bukti harus tertulis di kontrak; jangan menganggap checklist umum sebagai bukti fitness atau kepatuhan ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)).

Teman Cutting.co.id, tahan keputusan dasar penerimaan atau pembayaran yang bergantung pada data yang belum lengkap. Jika part menyentuh struktur, tekanan, pengangkatan, putaran, atau keselamatan, hentikan persetujuan teknis dan minta tinjauan engineer serta pemeriksaan kompeten. Detail antarmuka dan urutan penyiapan lanjutan berada di dokumen desain proyek; pekerjaan eksekusi lapangan memerlukan kontrol lokasi tersendiri.

Untuk menyiapkan pertanyaan yang sama saat membandingkan penyedia berdasarkan wilayah, gunakan konteks layanan pada [laser cutting Wonosobo](/laser-cutting-wonosobo.html) dan [laser cutting Wonogiri](/laser-cutting-wonogiri.html) sebagai langkah pencarian berikutnya; tetap kirim spesifikasi dan tabel asumsi yang sama kepada setiap penyedia.

Kesimpulannya, spesifikasi DFM, nesting, yield, setup, dan biaya cutting yang kuat mengubah permintaan “potong sesuai gambar” menjadi paket terukur: input dan revisi jelas, unit serta toleransi tertulis, aturan yield disepakati, setup dan inklusi harga terurai, asumsi terlihat, dan penerimaan memiliki rekaman. Langkah berikutnya adalah mengirim lembar RFQ, meminta vendor mengembalikan tabel asumsi dan bukti yang relevan, lalu meminta review engineer atau K3 untuk bagian berisiko. Operasi yang belum memiliki bukti tidak boleh diperlakukan sebagai fakta—tunda persetujuan sampai gate proyek yang relevan ditutup.
