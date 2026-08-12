---
article_id: CUT-06-01
title: "Panduan dasar plasma, oxy-fuel, dan waterjet cutting: istilah, komponen, dan cara kerja"
slug: "plasma-flame-waterjet-cutting-dasar"
description: "Pembaca dapat menjelaskan thermal/jet mechanisms, conductive/material limits, thickness, taper, HAZ, dross, consumables, gases/pressure, water/abrasive, ventilation, and economics, istilah yang sering tertukar, komponen, mekanisme, serta pertanyaan awal yang perlu diajukan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-08-24"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-06
primary_intent: "Memahami fondasi plasma, oxy-fuel, dan waterjet cutting sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/plasma-flame-waterjet-cutting-dasar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
---

# Panduan dasar plasma, oxy-fuel, dan waterjet cutting: istilah, komponen, dan cara kerja

Halo, Teman Cutting.co.id! Kalau Anda menerima gambar kerja lalu diminta memilih proses potong, kebingungan biasanya muncul karena tiga istilah terdengar sama-sama kuat: plasma, oxy-fuel, dan waterjet. Jawaban singkatnya, ketiganya dibedakan oleh cara energi memisahkan material, jenis material, ketebalan, mutu tepi, dan kendali lingkungan kerja.

Plasma dan oxy-fuel memakai panas; waterjet memakai aliran air bertekanan tinggi, kadang dengan bahan abrasif. Karena mekanismenya berbeda, istilah seperti *kerf* (lebar jalur yang hilang), *taper* (kemiringan sisi potong), HAZ atau zona terpengaruh panas, *dross* (lelehan yang menempel), gas, tekanan, dan bahan habis pakai harus dibaca sebagai sebab-akibat. Data material, gambar revisi, target tepi, serta kondisi lokasi dapat mengubah kesimpulan. Artikel ini membangun fondasi istilah dan cara kerja; pilihan kasus dan angka spesifik memerlukan telaah terpisah.

![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)

*Ilustrasi umum dari aset lokal Cutting.co.id; bukan dokumentasi proyek tertentu.*

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: after the opening has answered the main question, before the first detailed H2
**Exact Markdown to insert:** `![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies Mesin Advertising CNC Plasma Cutting Machine as relevant content media; no pixels were inspected.
Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Tiga mekanisme dasar: panas, nyala, dan jet air

Sebelum membandingkan hasil, pahami apa yang mengikis atau melelehkan benda kerja. Bagian ini mencegah anggapan bahwa semua mesin CNC hanya berbeda kecepatan; kita melihat sumber energi, komponen utama, dan konsekuensinya pada tepi potong.

### Plasma: busur listrik dan gas terionisasi

Plasma adalah gas yang diberi energi hingga menjadi aliran terionisasi. Sumber daya menghasilkan busur listrik antara elektroda dan benda kerja konduktif; gas pembawa membentuk aliran panas melalui nosel. Kepala potong, elektroda, nosel, kabel massa, sumber daya, meja, dan kendali gerak bekerja sebagai satu sistem.

Material meleleh lalu terdorong keluar dan meninggalkan *kerf*. Kecepatan, arus, jarak kepala, kondisi elektroda-nosel, serta gas memengaruhi lebar jalur dan dross. Panas juga membentuk HAZ, area sekitar garis potong yang mengalami perubahan termal meski tidak ikut terpotong. Tepi tampak rapi belum otomatis berarti tidak ada perubahan material.

Periksa apakah material konduktif, kabel massa dan meja mendukung rangkaian, serta *consumable* (komponen habis pakai seperti elektroda dan nosel) cocok dengan sistem. Tanpa catatan material dan kondisi consumable, jangan menjadikan satu hasil sebagai bukti kemampuan umum mesin.

### Oxy-fuel: pembakaran terarah dan oksidasi

Oxy-fuel, sering disebut *flame cutting*, memakai gas bahan bakar dan oksigen. Nyala pemanas menaikkan suhu lokal, kemudian semburan oksigen mendorong oksidasi dan mengeluarkan hasil reaksi dari celah. Komponennya meliputi tabung atau sumber gas, regulator, selang, katup, torch, ujung nosel, meja, dan kendali gerak.

Tekanan, kemurnian, desain ujung, jarak, dan urutan pemanasan memengaruhi kerf, terak, serta zona panas. Hasil dapat berbeda pada baja dengan komposisi atau kondisi permukaan berbeda. Sobat Cutting.co.id, anggap catatan gas sebagai jejak proses, bukan sekadar angka operator.

Pastikan identitas gas, jalur selang, kondisi regulator dan torch, serta pengendalian api dan asap sesuai penilaian K3 setempat. Rujukan keselamatan pemotongan menekankan bahaya energi, gas, api, dan lingkungan, sehingga prosedur generik tidak menggantikan tinjauan lokasi [OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252). Angka jarak, durasi, atau perlindungan tidak boleh ditebak.

### Waterjet: energi aliran dan abrasif

Waterjet memakai pompa untuk menghasilkan aliran air bertekanan tinggi melalui orifice kecil. Pada material sulit, aliran membawa abrasif sehingga erosi lebih efektif. Komponennya mencakup pompa, filtrasi, saluran tekanan tinggi, kepala potong, orifice, mixing tube, abrasif, bak penampung, dan penggerak CNC.

Tidak adanya panas utama berarti HAZ termal bukan mekanisme dominan, tetapi hasil tidak selalu tegak atau bebas masalah. Kecepatan, keausan orifice dan mixing tube, mutu air, jenis serta laju abrasif, jarak kepala, dan dukungan benda kerja memengaruhi taper dan tekstur tepi. Air limbah dan abrasif bekas perlu diidentifikasi serta dikelola menurut material dan aturan setempat; jangan menyebutnya aman tanpa karakterisasi.

## Istilah hasil potong yang sering tertukar

Istilah kualitas berguna bila dikaitkan dengan mekanisme dan cara memeriksanya. Nah, bagian ini membantu membaca lembar inspeksi tanpa mencampur masalah dimensi, panas, dan penampilan.

Kerf adalah lebar material yang hilang sepanjang jalur. Ia memengaruhi kompensasi jalur pada program CNC dan ukuran akhir, bukan lebar mata pisau. Mintalah metode ukur, lokasi ukur, dan revisi program sebelum menyimpulkan dimensi meleset.

Taper adalah perbedaan ukuran sisi atas dan bawah atau kemiringan dinding potong. Pada waterjet, geometri aliran dan kecepatan dapat membuat sisi tidak tegak; pada proses panas, bentuk busur, arah gerak, dan pelelehan ikut berpengaruh. Ukur beberapa titik dengan alat yang sesuai gambar kerja, bukan hanya melihat pantulan cahaya.

HAZ adalah zona yang menerima panas dan berpotensi mengubah sifat lokal; dross adalah material sisa yang menempel di tepi. Dross banyak dapat menandakan kombinasi parameter, consumable, material, atau arah gerak yang tidak cocok, tetapi penyebab tidak dapat dipastikan dari foto. Catat sisi, posisi, waktu, material, dan kondisi mesin sebelum memutuskan rework.

## Komponen, data, dan urutan kerja yang perlu dipastikan

Pembaca sering melompat ke pilihan merek atau daya mesin. Untuk keputusan awal, susun paket data agar setiap komponen dan langkah punya alasan yang dapat ditelusuri.

Mulai dari gambar kerja yang mencantumkan material, tebal, ukuran, toleransi, datum, radius, lubang, dan revisi. Cocokkan dengan identitas lembar atau pelat, batch bila dibutuhkan, serta kondisi permukaan. Dokumen mutu yang baik memisahkan identitas material, consumable, peralatan, inspeksi, dan hasil; prinsip ketertelusuran fabrikasi diringkas dalam [ISO 3834-6:2024](https://www.iso.org/standard/83335.html). Jika data belum lengkap, tandai [NEEDS MATERIAL AND ACCEPTANCE BASIS REVIEW] sebelum meminta penawaran.

Tetapkan tujuan tepi: apakah cukup untuk potongan kasar, perlu deburring, atau harus memenuhi toleransi dan inspeksi tertentu. Jangan menyamakan terlihat halus dengan lulus penerimaan. Basis penerimaan, alat ukur, jumlah sampel, dan kewenangan menyetujui harus tertulis dalam dokumen proyek. Untuk mengenali istilah mesin plasma dan komponen yang biasanya dibahas, Anda bisa membaca [halaman pengantar plasma cutting](/cnc/mesin/advertising/plasma-cutting); rute itu bukan pengganti data proyek.

Petakan sistem: sumber energi, kepala potong, meja dan penahan, gas atau air-abrasif, pembuangan fume, kendali gerak, serta consumable. Untuk bahan kimia atau gas, identitas produk dan lembar data keselamatan harus cocok dengan wadah dan penggunaan; konsep komunikasi bahaya dijelaskan dalam [OSHA 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200), tetapi itu bukan otomatis hukum Indonesia.

Jalankan urutan konseptual: verifikasi revisi gambar, cek material dan tumpuan, konfirmasi program serta kompensasi kerf, lakukan uji awal yang disetujui, amati parameter dan hasil, lalu dokumentasikan ukuran serta cacat. Uji awal bukan izin mengubah parameter tanpa batas; perubahan harus memiliki alasan, pencatatan, dan persetujuan sesuai sistem mutu.

## Ventilasi, energi, dan kondisi berhenti

Kualitas potong tidak terpisah dari keselamatan. Teman Cutting.co.id, kacamata atau sarung tangan saja tidak menyelesaikan asap, api, listrik, tekanan, dan gerak mesin.

Pengendalian dimulai dari menghilangkan atau mengganti sumber bahaya bila memungkinkan, lalu rekayasa seperti pelindung, penangkapan fume, isolasi energi, dan penghalang; administrasi serta APD melengkapi lapisan itu. UU Keselamatan Kerja Indonesia menempatkan keselamatan sebagai tanggung jawab kondisi kerja, sehingga detail kendali harus disesuaikan dengan tempat dan tugas [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970). Untuk status aturan sektor, cek pembaruan resmi karena sebagian ketentuan dapat berubah atau dicabut sebagian [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026).

Hentikan persiapan bila material, gambar, gas, kabel massa, saluran tekanan, ventilasi, atau pelindung mesin tidak dapat diidentifikasi dan diverifikasi. Hentikan pula bila ada kebocoran, kerusakan selang, interlock tidak berfungsi, asap mengarah ke orang, atau sisa potong tidak tertahan. Pekerjaan panas dekat bahan mudah terbakar, area berpenghuni, atau ruang terbatas memerlukan penilaian dan persetujuan K3 spesifik; artikel ini tidak memberi angka gas-test, jarak, tekanan, atau prosedur penyelamatan.

## Biaya dan jalan pintas yang menyesatkan

Harga per meter atau per lembar dapat menyembunyikan setup, pemuatan, program, gas, abrasif, pengolahan sisa, inspeksi, deburring, transport, dan rework. Kawan Cutting.co.id, minta ruang lingkup tertulis: material siapa, toleransi apa, cara ukur, jumlah uji, dokumen yang diserahkan, serta apa yang terjadi bila hasil tidak sesuai.

Jalan pintasnya adalah memakai proses sama untuk semua bahan karena mesin sudah ada. Itu gagal ketika material tidak konduktif untuk plasma, ketebalan dan reaksi permukaan tidak cocok untuk oxy-fuel, atau mutu tepi dan limbah waterjet tidak dihitung. Alternatifnya adalah matriks pertanyaan: material dan tebal, kebutuhan HAZ, mutu serta ketegakan tepi, akses ventilasi, utilitas, waktu, dan bukti penerimaan. Matriks belum memilih metode; ia membuat permintaan penawaran dapat dibandingkan adil.

## Verifikasi hasil dan serah-terima

Sebelum menerima hasil, cocokkan identitas benda dengan gambar dan revisi, jumlah serta bentuk, dimensi kritis, kerf atau taper relevan, dross dan kerusakan tepi, serta kebersihan permukaan. Simpan foto dan pengukuran bersama nomor pekerjaan, operator atau mesin bila diwajibkan, material, consumable, program, dan penyimpangan yang disetujui.

Jika ada cacat, pisahkan pertanyaan “apa yang terlihat”, “mengapa terjadi”, dan “boleh dipakai atau harus diperbaiki”. Jangan menutup bukti dengan gerinda atau cat sebelum pihak berwenang menentukan pemeriksaan. Serah-terima yang baik menyebut item, revisi, tanggal, basis penerimaan, hasil, penyimpangan, dan siapa yang mengesahkan; sertifikat kosong tidak membuktikan kesesuaian.

## Kesimpulan: fondasi sebelum memilih proses

Plasma memusatkan busur listrik dan gas pada material konduktif, oxy-fuel menggabungkan pemanasan dan oksidasi dengan gas, sedangkan waterjet mengikis melalui aliran air bertekanan dengan atau tanpa abrasif. Kerf, taper, HAZ, dross, consumable, gas, tekanan, ventilasi, dan biaya adalah akibat mekanisme serta kondisi sistem, bukan label promosi.

Langkah berikutnya adalah mengumpulkan gambar revisi, identitas material dan tebal, target tepi serta toleransi, kondisi lokasi, dan basis penerimaan; tanyakan bukti ketertelusuran dan batas tanggung jawab vendor. Jika data belum ada, tandai [NEEDS PROJECT AND PROFESSIONAL REVIEW] dan jangan mengubah artikel dasar ini menjadi keputusan spesifikasi. Aturan operasinya sederhana: pahami mekanismenya, cocokkan bukti dengan kasus, lalu hentikan pekerjaan ketika kondisi keselamatan atau kewenangan penerimaan belum jelas.
