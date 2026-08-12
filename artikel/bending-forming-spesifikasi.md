---
article_id: CUT-09-03
title: "Spesifikasi bending, rolling, dan forming untuk sheet serta plate: data, ukuran, toleransi, dan pemeriksaan asumsi"
slug: "bending-forming-spesifikasi"
description: "Pembaca dapat mengumpulkan input, menyatakan unit dan toleransi, memeriksa asumsi, serta menyiapkan spesifikasi bending, rolling, dan forming untuk lembaran dan pelat yang dapat ditinjau vendor."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-11-29"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-09
primary_intent: "Menyusun spesifikasi terukur untuk bending, rolling, dan forming untuk sheet serta plate"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/bending-forming-spesifikasi.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
---

# Spesifikasi bending, rolling, dan forming untuk sheet serta plate: data, ukuran, toleransi, dan pemeriksaan asumsi

Halo, Sobat Cutting.co.id! Jangan mulai dari pertanyaan “mesin ini bisa menekuk berapa milimeter?”. Mulailah dari bentuk akhir, material yang benar, datum pengukuran, dan toleransi yang benar-benar dibutuhkan. Spesifikasi yang dapat ditinjau vendor menyebutkan data itu secara tertulis; bukan sekadar “buat U” atau “roll sesuai gambar”.

Jawaban singkatnya: buat satu lembar spesifikasi yang mengunci identitas material, ukuran awal dan akhir, jenis proses (bending, rolling, atau forming), arah dan urutan deformasi, radius atau diameter target, toleransi, kondisi tepi, pemeriksaan, serta rekaman revisi. Angka akhir tidak boleh ditebak dari kebiasaan bengkel. Grade dan temper material, arah serat, springback, kemampuan alat, fungsi komponen, dan basis penerimaan proyek dapat mengubah keputusan. Karena itu, dimensi atau klaim kesesuaian untuk struktur dan layanan berisiko harus ditahan dengan penanda **[NEEDS REVIEW: data material, desain, dan acceptance basis proyek]** sampai engineer dan vendor menyetujuinya.

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

Hasil yang dicari adalah dokumen kerja yang bisa dibaca sama oleh perancang, estimator, drafter, pembeli, dan vendor. Dokumen itu tidak harus panjang, tetapi setiap angka harus punya satuan, referensi ukur, dan alasan fungsional. Orang yang berwenang menyetujui geometri dan beban tetaplah engineer atau pemilik desain; penulis spesifikasi menerjemahkan kebutuhan itu menjadi data produksi.

Sebelum meminta penawaran, siapkan gambar atau model dengan nomor revisi, daftar material, fungsi komponen, kuantitas, kondisi permukaan, dan batas ruang kerja. Tetapkan apakah ukuran adalah sebelum proses, sesudah proses, atau ukuran inspeksi. Paket fabrikasi yang terkendali lazimnya mengaitkan dokumen yang berlaku, datum, material, toleransi, urutan, titik tahan inspeksi, dan dasar penerimaan; katalog SNI 1729:2020 hanya mengidentifikasi standar, bukan memberi Anda nilai toleransi atau detail sambungan siap pakai ([BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)). Jika permukaan akan dicat, rujukan persiapan dan perlindungan korosi seperti [ISO 12944-5:2019](https://www.iso.org/standard/77795.html) tetap perlu dicocokkan dengan sistem coating yang dipilih; halaman standar tidak membuktikan kecocokan produk tertentu.

## Langkah 1 — tetapkan ruang lingkup

Tuliskan batas pekerjaan dalam kalimat yang dapat dicentang. Contoh: “Membentuk plate menjadi radius luar tertentu, memotong ujung sesuai garis trim, lalu menyerahkan part untuk inspeksi dimensi.” Nyatakan juga yang tidak termasuk: desain ulang, pengelasan sambungan, pengecatan, pemasangan di lapangan, atau perbaikan cacat yang belum disetujui. Detail setup dan antarmuka desain berada di dokumen proses terpisah; eksekusi lapangan bukan bagian dari lembar spesifikasi ini.

Bedakan tiga istilah kerja. Pembengkokan lokal (*bending*) biasanya terjadi pada garis atau zona tertentu. Penggulungan (*rolling*) membentuk lengkung berulang atau radius panjang dengan lintasan rol. Pembentukan dengan beberapa langkah atau cetakan (*forming*) adalah istilah payungnya. Pilih istilah yang sesuai dengan geometri, lalu sertakan sketsa penampang dan arah material. Jangan menganggap “radius 50” lengkap sebelum menulis radius dalam atau luar, titik ukur, dan apakah radius itu nominal atau batas.

Tentukan pula antarmuka: lubang, slot, tepi potong, area las, bidang dudukan, dan zona yang tidak boleh tergores. Jika bagian akan menahan beban, tekanan, temperatur, getaran, atau menjadi bagian keselamatan, hentikan penetapan ukuran final sampai basis desain dan persetujuan profesional tersedia (**[NEEDS REVIEW: GATE-04/GATE-05]**).

## Langkah 2 — kumpulkan dan cocokkan bukti

Gunakan tabel input agar asumsi terlihat sebelum harga diminta.

| Kelompok | Isian minimum | Cara memeriksa |
|---|---|---|
| Material | grade/temper, tebal nominal, ukuran blank, identitas heat atau batch bila diwajibkan | cocokkan mill certificate atau laporan pemasok dengan part dan revisi |
| Geometri | panjang, lebar, sudut, radius/diameter, arah lengkung, allowance trim | tandai datum A-B-C dan definisikan radius dalam atau luar |
| Proses | bending, rolling, atau forming; jumlah langkah; kebutuhan alat bantu | minta vendor menyatakan asumsi alat dan urutan, bukan hanya kapasitas umum |
| Toleransi | ukuran kritis, sudut, kelurusan, ovalitas, twist, dan kondisi tepi | tulis ± atau batas atas-bawah beserta metode ukur |
| Permukaan | sisi tampak, film pelindung, larangan bekas tekan, coating setelah forming | cocokkan dengan spesifikasi coating dan kondisi substrat |
| Bukti | laporan first-off, alat ukur, foto penandaan, NCR dan disposisi | pastikan nomor part, revisi, tanggal, dan penanggung jawab tercatat |

Catat sumber data, bukan hanya nilainya. Sertifikat bahan dan identitas batch membantu penelusuran, tetapi tidak otomatis membuktikan material itu cocok untuk radius atau lingkungan tertentu. ISO 3834-6 memberi kerangka informasi mutu untuk pengelasan/fabrikasi, sedangkan data produk dan kompatibilitas tetap perlu diverifikasi terhadap material serta kondisi aktual ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)). Untuk bahan berlapis atau akan dicat, pisahkan catatan produk, batch, dan instruksi aplikasinya; jangan menyalin rasio campur atau masa simpan dari label generik.

Samakan unit sejak awal. Pilih mm untuk dimensi gambar, derajat untuk sudut, dan nyatakan bila radius atau diameter memakai satuan lain. Tulis “tebal nominal” dan, bila tebal aktual memengaruhi hasil, kolom “tebal terukur”. Ukuran blank, bend allowance, dan springback adalah input proses yang harus dikonfirmasi vendor; jangan mengubahnya menjadi angka pasti tanpa material dan uji yang relevan.

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman untuk paket RFQ adalah sebagai berikut:

1. Catat revisi gambar, datum, material, dan fungsi sebagai satu acuan kerja. Tandai ukuran kritis dengan alasan, misalnya harus bertemu bidang sambungan.
2. Minta vendor memeriksa kelayakan awal: rentang tebal, ukuran blank, radius, kapasitas alat, akses pengukuran, serta risiko tanda tekan. Jawaban “bisa” harus disertai asumsi.
3. Setujui metode dan urutan pembentukan di tingkat konsep. Jangan menjadikan metode itu sebagai instruksi operator rinci sebelum prosedur kerja, penilaian risiko, dan review kompeten tersedia.
4. Lakukan *first-off* atau sampel awal dengan identitas part dan revisi. Ukur datum, sudut, radius/diameter, twist, dan kondisi tepi memakai alat yang sesuai dan status verifikasinya tercatat.
5. Bandingkan hasil dengan toleransi dan dasar penerimaan. Jika tidak sesuai, buka laporan ketidaksesuaian (NCR); jangan mengubah toleransi secara lisan. Setiap deviasi harus memiliki alasan, dampak waktu/biaya, persetujuan, dan revisi.
6. Setelah disetujui, lepaskan produksi sesuai revisi yang sama dan jaga keterlacakan material serta catatan inspeksi.

Kawan Cutting.co.id, jangan mengirim model CAD (desain berbantuan komputer) tanpa menyebut versi perangkat lunak atau unit. File yang terbaca berbeda dapat mengubah skala, datum, atau fitur yang dianggap referensi. Jika vendor membutuhkan konversi, simpan salinan PDF berdimensi dan daftar perubahan agar sumber kebenaran tetap jelas.

## Titik tahan dan kondisi berhenti

Hentikan penawaran atau pembentukan ketika grade material belum terbukti, arah rolling tidak diketahui padahal memengaruhi fungsi, atau gambar memiliki dua datum yang bertentangan. Berhenti juga ketika radius, sudut, atau toleransi tidak dapat diukur dengan metode yang disepakati, dan ketika permintaan menyentuh struktur, tekanan, pengangkatan, atau keselamatan tanpa persetujuan desain (**[NEEDS REVIEW: GATE-03, GATE-04, GATE-05, GATE-07]**).

Keselamatan bukan catatan alat pelindung diri di bagian bawah RFQ. Identifikasi energi mesin, titik jepit, benda panas, bahan kimia, ventilasi, kebakaran, akses angkat, dan orang di sekitar harus mengikuti kondisi lokasi serta aturan K3 Indonesia. UU Keselamatan Kerja dan Permenaker tentang keselamatan dan kesehatan kerja lingkungan kerja menjadi rujukan hukum, tetapi tidak menyediakan prosedur spesifik untuk setiap mesin atau lokasi; penanggung jawab K3 harus menyetujui pengendalian tugas aktual ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

Untuk inspeksi, satu pengukuran atau tampilan visual tidak cukup untuk menyimpulkan “lulus”. ISO 17635 menempatkan metode, cakupan, teknik, personel, alat, kondisi permukaan, pelaporan, dan dasar penerimaan sebagai bukti terpisah; ISO 9712 juga berkaitan dengan kualifikasi personel pemeriksaan tanpa merusak (NDT). Nilai acceptance, interval kalibrasi, dan teknik spesifik tetap harus berasal dari standar penuh dan prosedur proyek ([ISO 17635:2025](https://www.iso.org/standard/85705.html), [ISO 9712:2021](https://www.iso.org/standard/75614.html)).

## Verifikasi hasil dan serah terima

Sebelum menerima part, cocokkan daftar berikut dengan revisi terakhir:

- identitas part, material, batch, dan jumlah;
- ukuran utama, datum, sudut, radius/diameter, kelurusan, dan kondisi tepi;
- toleransi yang dipakai serta metode dan alat ukurnya;
- laporan first-off, hasil inspeksi produksi, foto penandaan, dan daftar NCR;
- perubahan, deviasi, atau substitusi yang disetujui;
- status pekerjaan lanjutan seperti trim, las, coating, packing, dan transport;
- nama penerbit, tanggal, revisi, dasar penerimaan, hasil, dan otorisasi.

Serah terima bukan sekadar barang tiba atau pembayaran selesai. Lingkup garansi, pengecualian, bukti yang disimpan, serta jalur respons harus tertulis dalam kontrak; dokumen checklist tanpa identitas item dan dasar penerimaan tidak membuktikan kesesuaian ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

### Jalan pintas yang sering gagal

Jalan pintasnya adalah mengirim foto contoh dan satu ukuran “panjang × lebar × tebal”, lalu meminta vendor menebak radius serta toleransi. Cara ini gagal ketika material berbeda, springback mengubah sudut, atau bidang sambungan membutuhkan datum yang tidak terlihat di foto. Alternatif yang lebih dapat ditinjau adalah mengirim gambar berdimensi, tabel input, kriteria penerimaan, dan daftar asumsi yang harus dikonfirmasi sebelum produksi. Harga boleh dibandingkan setelah lingkup, pengukuran, pengujian, rework, transport, dan dokumentasi dijelaskan; total harga saja tidak menunjukkan isi pekerjaan.

Untuk pertanyaan lanjutan yang sangat lokal, gunakan hanya rujukan yang sesuai wilayah pekerjaan, misalnya [rujukan bending di Wonosobo](/bending-wonosobo.html) atau [rujukan bending di Wonogiri](/bending-wonogiri.html). Keduanya bukan pengganti gambar kerja dan persetujuan teknis pada paket ini.

## Kesimpulan dan langkah berikutnya

Spesifikasi bending, rolling, dan forming yang siap ditinjau vendor memuat material yang terlacak, geometri dengan datum dan unit, radius atau sudut yang didefinisikan, toleransi terukur, urutan konseptual, titik berhenti, serta paket bukti saat handover. Buat lembar RFQ satu revisi, minta vendor mengembalikan asumsi dan metode ukurnya, lalu lakukan review engineer untuk fungsi berisiko sebelum angka final dibekukan.

Teman Cutting.co.id, aturan operasinya sederhana: bila data material, basis desain, metode ukur, atau pengendalian K3 belum jelas, jangan mengisi kekosongan dengan angka kebiasaan. Tandai **[NEEDS REVIEW]**, tahan pekerjaan pada hold point, dan lanjutkan hanya setelah pihak yang berwenang menyetujui bukti yang relevan.
