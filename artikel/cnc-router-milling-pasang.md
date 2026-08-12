---
article_id: CUT-07-05
title: "Tahapan produksi CNC routing, milling, engraving, dan drilling: persiapan, first-off, QC, dan serah terima"
slug: "cnc-router-milling-pasang"
description: "Pembaca dapat menyiapkan mesin dan area, memverifikasi material, mengurutkan operasi, menetapkan titik kendali mutu, dan mendokumentasikan serah terima CNC routing, milling, engraving, dan drilling."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-09"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-07
primary_intent: "Merencanakan serta mengendalikan pelaksanaan CNC routing, milling, engraving, dan drilling"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/cnc-router-milling-pasang.html"
technical_review: required
sources:
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
---

# Tahapan produksi CNC routing, milling, engraving, dan drilling: persiapan, first-off, QC, dan serah terima
## Hasil akhir dan prasyarat

Halo, Teman Cutting.co.id! Produksi CNC yang rapi bukan dimulai saat pahat menyentuh material. Urutan yang dapat dipertanggungjawabkan adalah: lingkup (scope) dan dokumen ditetapkan, mesin serta area dinyatakan siap, material dan program dicocokkan, satu benda pertama diperiksa, operasi berikutnya berjalan dengan titik kendali (hold point), lalu hasil dan catatan diserahterimakan. Memotong langsung dari file yang belum ditinjau sering membuat kesalahan baru terlihat setelah satu kelompok produksi selesai.

Hasil akhirnya bukan sekadar benda yang tampak sesuai gambar, melainkan produk dengan identitas material, revisi program, pemeriksaan, keputusan terhadap penyimpangan, dan status rilis yang jelas. Karena itu, dasar penerimaan, toleransi, dan siapa yang berwenang melepas titik kendali harus berasal dari dokumen proyek terkini dan peninjauan kompeten.

Sebelum penjadwalan, siapkan gambar atau model ber-revisi, daftar operasi (routing, milling, engraving, drilling), material dan jumlah, datum, toleransi yang memang disyaratkan, file program, alat potong, metode pengukuran, formulir inspeksi, serta jalur eskalasi. Pastikan sumber listrik, ekstraksi atau pengendalian serpihan, pencahayaan, akses, dan area penyimpanan tidak mengganggu pekerjaan lain. Ini bukan izin untuk mengoperasikan mesin di luar kompetensi; pekerjaan berbahaya memerlukan operator dan penanggung jawab K3 yang berwenang.

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


## Langkah 1 — tetapkan lingkup

Tuliskan apa yang dibuat dan apa yang tidak dibuat. Tandai permukaan referensi, datum, sisi yang akan terlihat, fitur yang harus konsentris atau sejajar, serta antarmuka dengan komponen lain. Bedakan pekerjaan di mesin dari pekerjaan lanjutan seperti pembersihan geram tajam (deburring), pelapisan (coating), perakitan, atau pemasangan di lapangan. Bila fungsi akhir bergantung pada struktur, angkur (anchor), beban, atau kondisi yang sudah ada, CNC hanya menyelesaikan bagian manufaktur; kecukupan sistem tetap perlu desain dan persetujuan tersendiri.

Buat matriks sederhana: fitur–alat/proses–cara verifikasi–rekaman–pemilik keputusan. Untuk routing dan engraving, fokuskan pada kontur, kedalaman, dan kualitas tepi yang diminta. Untuk milling, pastikan datum dan orientasi setup tidak berubah antaroperasi. Untuk drilling, kunci pola lubang, diameter, kedalaman, dan hubungan ke datum; jangan mengisi angka yang tidak ada pada gambar.

Teman Cutting.co.id, jadikan pertanyaan “apakah fitur ini benar-benar masuk scope?” sebagai pemeriksaan pertama. Permintaan lisan yang mengubah ukuran, material, atau urutan harus masuk revisi tertulis sebelum program diperbarui. Simpan versi lama sebagai jejak, bukan untuk dipakai kembali tanpa otorisasi.

## Langkah 2 — kumpulkan dan cocokkan bukti

Mulai dengan pemeriksaan identitas: nomor pekerjaan, revisi gambar, nama file program, material, kelompok produksi atau nomor panas bila diwajibkan, dan alat potong. Cocokkan label fisik dengan dokumen penerimaan; jika tidak cocok, tahan material. Untuk bahan habis pakai atau bahan kimia pendukung, catat identitas produk dan lembar data keselamatan yang berlaku. Jangan menyimpulkan kompatibilitas, umur simpan, atau parameter hanya dari label umum.

Periksa mesin dalam kondisi produksi: pelindung dan pengunci berfungsi, meja serta perlengkapan penjepit bersih dan stabil, alat potong teridentifikasi, sistem ukur atau sensor peraba berstatus verifikasi, dan area bebas benda lepas. Pengendalian energi berbahaya harus mengikuti prosedur perusahaan dan ketentuan yang berlaku; OSHA 1910.147 dapat dibaca sebagai rujukan konsep penguncian/pelabelan energi, bukan pengganti aturan Indonesia atau instruksi pabrikan (OEM) ([OSHA 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147)). Di Indonesia, kewajiban keselamatan kerja perlu ditelaah pada konteks tempat kerja dan kompetensi penanggung jawab, termasuk UU No. 1 Tahun 1970 ([BPK](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

Sebelum first-off, lakukan dry run atau simulasi yang diizinkan oleh prosedur internal untuk memeriksa arah koordinat, urutan tool, clearance, dan titik nol. Jangan menganggap simulasi membuktikan hasil akhir. Catat siapa yang meninjau program, mesin yang dipakai, tanggal, serta perubahan yang disetujui.

## Langkah 3 — jalankan urutan kerja

Kunci material dan datum, lalu pasang penjepitan benda kerja (workholding) yang menahan benda tanpa menutup area potong atau memaksa material berubah bentuk. Muat program dengan pemeriksaan identitas dan revisi. Jalankan operasi yang paling aman untuk memvalidasi referensi, kemudian lakukan first-off pada satu benda atau bagian yang disepakati. Setelah mesin berhenti, ukur fitur kritis dan periksa orientasi, tepi, burr, serta tanda gangguan; hasilnya dibandingkan dengan dasar penerimaan (acceptance basis), bukan dengan perkiraan mata.

Jika first-off diterima, tandatangani rilis untuk kelompok produksi (batch) atau operasi berikutnya. Jika tidak, hentikan, pisahkan benda, tandai statusnya, dan dokumentasikan penyimpangan sebelum mengubah offset, alat, atau program. Untuk pekerjaan multi-setup, ulangi verifikasi datum setiap kali benda dipindah. Urutkan roughing, finishing, engraving, dan drilling sesuai dependensi pada gambar serta risiko deformasi; urutan spesifik harus ditetapkan teknisi yang memahami mesin, material, dan program tersebut.

Selama produksi, gunakan pemeriksaan antaroperasi yang proporsional: identitas benda, jumlah, fitur kunci, kondisi alat, dan tren hasil ukur. Penggantian alat atau perubahan parameter adalah peristiwa rekaman, bukan catatan informal. Link internal seperti [layanan CNC milling](/cnc/milling) dan [referensi side-hole drilling](/cnc/mesin/side-hole-drilling) dapat membantu menyamakan istilah proses, tetapi tidak menggantikan review program dan gambar proyek.

## Titik kendali dan kondisi berhenti

Hold point wajib muncul sebelum material pertama dipotong, setelah first-off, setelah perubahan setup atau alat yang memengaruhi fitur, dan sebelum rilis akhir. Hentikan pekerjaan jika revisi dokumen tidak jelas, material tidak terlacak, penjepitan benda kerja bergeser, alat rusak, guarding atau interlock bermasalah, hasil ukur di luar dasar penerimaan, atau serpihan dan asap membuat kondisi kerja tidak terkendali.

Sobat Cutting.co.id, jangan “mengakali” hasil di luar toleransi dengan mengubah program berulang-ulang tanpa keputusan engineering. Isolasi benda terdampak dan minta disposisi: rework, repair, use-as-is, scrap, atau inspeksi tambahan hanya boleh dipilih oleh pihak yang ditunjuk proyek. Metode inspeksi, cakupan, teknik, personel, status peralatan, dan laporan adalah bukti terpisah; abstrak ISO 17635 dan ISO 9712 menegaskan bahwa metode dan kualifikasi tidak otomatis menjadi keputusan penerimaan ([ISO 17635](https://www.iso.org/standard/85705.html), [ISO 9712](https://www.iso.org/standard/75614.html)).

Untuk setiap penghentian, catat nomor benda, fitur, alat, program, waktu, kondisi, foto atau hasil ukur bila diizinkan, dan otoritas yang memberi keputusan. **[NEEDS PROJECT-SPECIFIC ACCEPTANCE BASIS, TOLERANCES, AND RELEASE AUTHORITY]** Marker ini harus ditutup dengan dokumen proyek dan review kompeten sebelum produksi dinyatakan lulus.

## Verifikasi hasil dan serah terima

Penerimaan akhir sebaiknya berupa paket, bukan hanya tanda tangan. Sertakan daftar benda dan status, revisi gambar/program, identitas material, catatan first-off dan inspeksi antaroperasi, hasil ukur fitur kritis, daftar nonkonformitas dan disposisinya, catatan perubahan alat/setup, serta daftar sisa pekerjaan. Jika ada coating, perakitan, atau instalasi lanjutan, nyatakan batas tanggung jawab dan kondisi saat diserahkan.

Gunakan checklist serah terima berikut:

- jumlah dan identitas benda cocok dengan daftar pengiriman;
- permukaan, tepi, lubang, dan engraving diperiksa sesuai dasar penerimaan;
- alat ukur dan metode pemeriksaan tercatat, dengan status verifikasi yang relevan;
- benda ditandai agar orientasi dan pasangan antarmuka tidak tertukar;
- penyimpangan terbuka memiliki pemilik, tenggat, dan keputusan tertulis;
- penerima memahami batas penggunaan, penyimpanan, dan pekerjaan lanjutan.

Jangan mengklasifikasikan offcut, coolant, kain terkontaminasi, atau kemasan secara serampangan. Ikuti prosedur fasilitas dan aturan lokal untuk identifikasi, penyimpanan, pengangkutan, serta penyerahannya.

## Jalan pintas yang sering gagal

Jalan pintas yang tampak hemat adalah menganggap satu benda pertama “sudah cukup” lalu melewati pemeriksaan setelah pergantian alat atau setup. Mekanismenya jelas: datum dapat bergeser, alat mengalami keausan, dan perubahan program dapat memengaruhi fitur yang tidak terlihat dari luar. Alternatif yang lebih andal adalah mempertahankan hold point berbasis perubahan dan tren, dengan jumlah pemeriksaan ditetapkan oleh rencana inspeksi proyek—bukan angka universal yang ditebak.

Prinsip umum penjagaan mesin pada OSHA 1910.212 hanya menjadi rujukan Amerika Serikat; persyaratan Indonesia dan prosedur pemilik mesin tetap menentukan [OSHA 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212).

## Kesimpulan

Kawan Cutting.co.id, tahapan produksi CNC routing, milling, engraving, dan drilling yang terkendali adalah lingkup yang jelas, bukti yang cocok, urutan setup–first-off–produksi, hold point saat risiko berubah, lalu handover dengan rekaman lengkap. Langkah Anda berikutnya: minta paket gambar dan dasar penerimaan ber-revisi, tetapkan pemilik rilis, dan jadwalkan review kompeten sebelum benda pertama dipotong. Bila salah satu dokumen atau kondisi keselamatan belum jelas, tahan pekerjaan; tidak ada hasil visual yang dapat menggantikan persetujuan dan bukti yang benar.
