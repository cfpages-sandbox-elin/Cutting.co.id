---
article_id: CUT-10-03
title: "Spesifikasi tooling, workholding, fixture, gas, coolant, dan consumable: data, ukuran, toleransi, dan pemeriksaan asumsi"
slug: "tooling-fixture-consumable-spesifikasi"
description: "Panduan menyusun data, ukuran, toleransi, dan pemeriksaan asumsi untuk tooling, workholding, fixture, gas, coolant, serta consumable agar dapat ditinjau vendor."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-12-31"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-10
primary_intent: "Menyusun spesifikasi terukur untuk tooling, workholding, fixture, gas, coolant, dan consumable"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/tooling-fixture-consumable-spesifikasi.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
---

# Spesifikasi tooling, workholding, fixture, gas, coolant, dan consumable: data, ukuran, toleransi, dan pemeriksaan asumsi

Halo, Teman Cutting.co.id! Vendor sering menerima permintaan “fixture untuk benda ini” atau “gas dan consumable yang cocok”, tetapi tanpa ukuran, satuan, toleransi, dan kondisi kerja yang jelas. Akibatnya penawaran tampak lengkap padahal masih memuat asumsi tersembunyi. Jawaban singkatnya: spesifikasi yang dapat ditinjau harus mengubah kebutuhan menjadi data terukur, menunjukkan sumber setiap data, lalu menandai hal yang belum disetujui. Di artikel ini Anda akan menyusun paket itu tanpa menggantikan desain engineer atau persetujuan K3.

Mulailah dari fungsi dan kondisi nyata, bukan dari merek. Ukur benda kerja, definisikan datum atau acuan, tulis beban dan lingkungan yang diketahui, lalu pisahkan fakta, asumsi, serta keputusan yang menunggu review. Standar seperti ISO 3834-6 membantu kerangka informasi mutu pengelasan, sedangkan halaman katalog SNI hanya mengonfirmasi identitas dokumen, bukan isi klausul atau nilai toleransinya ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html), [katalog SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)).

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan
- Image ID: LOCAL-001
- Source type: local
- Placement: after opening
- **Exact Markdown to insert:** `![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)`
- Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- Selection basis: filename/source metadata identifies Mesin Advertising CNC Plasma Cutting Machine as relevant content media; no pixels were inspected.
- Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->
![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)
*Aset lokal proyek; bukan dokumentasi proyek tertentu.*

## Hasil akhir dan prasyarat

Bagian ini menjelaskan bentuk dokumen yang hendak Anda serahkan dan mengapa prasyarat mencegah vendor menebak. Sebelum menyebut ukuran, pastikan siapa pemilik keputusan, dokumen mana yang berlaku, dan kondisi apa yang belum tersedia.

Hasil akhirnya sebaiknya satu lembar spesifikasi induk dengan nomor revisi, daftar komponen, tabel data, gambar acuan, daftar asumsi, serta kolom pertanyaan vendor. Pemilik proses atau engineer menetapkan fungsi dan batas keselamatan; estimator menerjemahkannya menjadi kuantitas dan biaya; vendor mengonfirmasi kemampuan dan penyimpangan. Jika salah satu peran belum jelas, tulis “menunggu penetapan” daripada mengisi sendiri.

Kumpulkan gambar terbitan terakhir, material dan ketebalan, ukuran maksimum-minimum, target hasil, pola lubang atau bidang acuan, jenis mesin, ruang gerak, utilitas yang tersedia, serta frekuensi pemakaian. Gunakan satuan yang konsisten—misalnya milimeter untuk dimensi dan bar untuk tekanan—dan tulis satuan di setiap kolom. Toleransi ±0,1 mm bukan pengganti datum, metode ukur, atau kondisi temperatur; tiga hal itu perlu dicantumkan bersama nilainya bila memang disyaratkan.

## Langkah 1 — tetapkan ruang lingkup

Ruang lingkup yang jelas mencegah spesifikasi fixture berubah menjadi desain mesin atau instruksi pemasangan. Nyatakan benda yang ditahan, operasi yang dilakukan, sisi yang harus bebas, urutan pemrosesan, dan hasil yang diterima. Sebutkan juga yang sengaja di luar dokumen: desain antarmuka rinci berada pada paket desain berikutnya, sedangkan eksekusi lapangan memerlukan rencana kerja dan persetujuan setempat.

Buat daftar per komponen. Untuk tooling, tulis fungsi alat, jenis koneksi, jangkauan, material, dan batas penggunaan yang diberikan pabrikan. Untuk workholding atau sistem penjepit, tulis titik tumpu, arah gaya, permukaan kontak, akses alat ukur, dan cara melepas benda tanpa merusak permukaan. Untuk fixture, bedakan ukuran rangka dari lokasi datum, lubang referensi, dan fitur yang dapat diganti.

Gas, coolant, dan consumable harus punya identitas produk, bukan sekadar nama kelas. Catat gas, kemurnian atau campuran sebagaimana lembar data produk, jenis coolant dan kondisi pengenceran yang disetujui, serta klasifikasi bahan tambah atau elektroda. Jangan menyimpulkan kompatibilitas, umur simpan, rasio campur, atau parameter las dari label umum; tautkan lembar data dan nomor lot. Praktik ketertelusuran bahan, lot, sertifikat, penyimpanan, dan substitusi yang disetujui dibahas sebagai kebutuhan sistem mutu dalam abstrak ISO 3834-6, bukan sebagai nilai proses universal.

## Langkah 2 — kumpulkan dan cocokkan bukti

Jadikan setiap baris tabel dapat dijawab dengan “dari mana angka ini?”. Kolom minimalnya meliputi parameter, nilai, satuan, toleransi atau rentang, metode verifikasi, sumber, pemilik keputusan, dan status. Untuk material, simpan penunjukan material, dimensi, nomor heat atau batch bila dipersyaratkan, serta tautan sertifikat. Untuk consumable, simpan klasifikasi, lot, tanggal penerimaan, kondisi penyimpanan, dan substitusi yang disetujui.

Cocokkan bukti dengan kondisi. Foto kemasan tidak membuktikan isi tabung; nama gas tidak membuktikan debit yang boleh dipakai pada mesin; dan diameter nominal tidak membuktikan ulir atau kecocokan chuck. Minta vendor mengisi bagian “deviasi dari permintaan” sehingga perbedaan antara data Anda dan penawaran tidak tersembunyi. Baca lembar data keselamatan produk untuk identitas dan pengendalian bahaya; contoh konsep label dan lembar data keselamatan dari OSHA bukan hukum Indonesia, jadi kewajiban lokal tetap harus ditinjau ([OSHA hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).

Untuk pemeriksaan asumsi, tandai kalimat seperti “benda pasti datar”, “tekanan selalu sama”, atau “operator sudah tahu”. Ubah masing-masing menjadi pertanyaan terukur: berapa kerataan yang diterima, berapa rentang tekanan dari utilitas, dan dokumen pelatihan apa yang menjadi bukti kompetensi. Jika jawabannya belum ada, beri label [NEEDS GATE-01: data kondisi kerja dan persetujuan engineer belum tersedia].

## Langkah 3 — jalankan urutan kerja

Urutan dimulai dengan meninjau revisi gambar dan daftar komponen, lalu memastikan datum serta satuan. Setelah itu isi data benda kerja dan lingkungan, pilih kelas komponen yang diperlukan, dan minta vendor mengonfirmasi antarmuka. Baru kemudian bandingkan alternatif berdasarkan fungsi, risiko, ketersediaan data, dan kemudahan pemeriksaan—bukan berdasarkan merek yang paling dikenal.

Pada tahap tinjauan, lakukan pemeriksaan meja: apakah setiap ukuran memiliki titik ukur, apakah toleransi selaras dengan kemampuan proses, apakah bahan kontak cocok dengan permukaan, dan apakah consumable memiliki lot yang dapat dilacak. Simulasikan satu siklus dari pemasangan, pemotongan atau pengelasan, pemeriksaan, hingga pelepasan. Jika operator perlu menekan benda dengan tangan di dekat bagian bergerak, itu bukan detail kecil; hentikan dan minta rekayasa pengamanan.

Pengendalian energi juga bagian dari spesifikasi, tetapi bukan tempat untuk menyalin prosedur generik. Praktik penguncian dan pelabelan sumber energi (lockout/tagout) pada OSHA 1910.147 hanya contoh kerangka pengendalian; penerapan harus mengikuti persyaratan dan penanggung jawab Indonesia. Untuk mesin, perlindungan titik operasi dan bagian bergerak perlu ditinjau terhadap kondisi aktual, bukan diasumsikan aman karena fixture baru ([OSHA 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147), [OSHA 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212)).

## Titik berhenti dan kondisi berhenti

Hold point berarti pekerjaan berhenti sampai bukti tertentu ditinjau, bukan sekadar kolom tanda tangan. Tetapkan titik sebelum pembelian, sebelum pembuatan fixture, sebelum first-off, dan sebelum pelepasan ke operasi. Pada tiap titik, tulis bukti yang diperiksa, siapa yang berwenang, dan tindakan jika hasil tidak cocok.

Hentikan proses bila datum bertentangan, ukuran kritis tidak punya metode ukur, identitas gas atau consumable tidak jelas, label bahaya dan lembar data keselamatan tidak tersedia, atau desain menahan energi yang belum dianalisis. Regulasi K3 Indonesia dan status perubahan aturan harus diperiksa pada teks terkini; jangan mengandalkan ringkasan lama ([Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)). Jika pekerjaan melibatkan tekanan, ruang terbatas, bahan mudah terbakar, atau paparan yang belum dikaji, sisakan [NEEDS GATE-02: tinjauan K3 dan engineering wajib sebelum eksekusi].

Teman Cutting.co.id, jangan mengubah hold point menjadi janji bahwa proses pasti aman. Ia hanya bukti bahwa pertanyaan penting sudah dijawab oleh orang yang berwenang. Desain, pemilihan pengaman, dan keputusan kembali beroperasi tetap berada pada engineer, pemilik aset, dan penanggung jawab K3.

## Verifikasi hasil dan serah terima

Verifikasi penerimaan menguji dokumen dan benda secara bersamaan. Periksa identitas revisi, ukuran aktual terhadap toleransi, posisi datum, fungsi penjepitan, akses pemeriksaan, identitas lot gas atau consumable, serta catatan deviasi. Simpan hasil ukur dengan alat, tanggal, kondisi, dan nama pemeriksa; angka tanpa metode tidak mudah diaudit.

Handover yang baik memuat gambar terbitan, daftar komponen dan suku cadang, lembar data keselamatan, sertifikat atau laporan bahan, catatan first-off, daftar asumsi yang sudah ditutup, serta pertanyaan yang masih terbuka. Sertakan aturan penggantian: komponen pengganti harus memiliki identitas dan persetujuan yang sama, atau deviasinya direkam dan ditinjau. Jangan menjanjikan umur pakai, penghematan, atau kapasitas tanpa data penggunaan dan persetujuan pemilik.

## Jalan pintas yang sering menggoda

Jalan pintas paling umum adalah menyalin spesifikasi proyek lama lalu mengganti nama benda kerja. Cara ini gagal ketika material, datum, mesin, gas, atau lingkungan berubah; angka lama tampak rapi tetapi mekanismenya tidak lagi sama. Alternatif yang lebih aman ialah mempertahankan struktur tabelnya saja, kemudian mengisi ulang fakta, satuan, toleransi, sumber, dan pemeriksaan untuk kasus baru. Kawan Cutting.co.id, bila sebuah kolom tidak dapat dijawab, biarkan kosong dengan penanda kebutuhan review—itu lebih jujur daripada angka yang memberi rasa pasti palsu.

## Kesimpulan: ubah asumsi menjadi data yang dapat ditinjau

Spesifikasi tooling, workholding, fixture, gas, coolant, dan consumable yang siap ditinjau vendor bukan katalog merek. Ia adalah paket terukur: fungsi dan ruang lingkup, datum serta satuan, ukuran dan toleransi, identitas bahan atau produk, metode verifikasi, catatan asumsi, titik berhenti, dan kewenangan persetujuan. Langkah Anda berikutnya adalah mengambil satu pekerjaan nyata, membuat tabel parameter dengan kolom sumber dan pemilik keputusan, lalu meminta engineer serta penanggung jawab K3 menutup setiap [NEEDS ...] sebelum pembelian atau fabrikasi. Bila Anda memerlukan konteks umum, mulai dari [beranda Cutting.co.id](/).

Jika data antarmuka belum final, jangan menebak ukuran konektor atau gaya penjepit; arahkan ke paket desain dan tinjauan berikutnya. Aturan operasionalnya sederhana: tidak ada angka tanpa satuan dan acuan, tidak ada substitusi tanpa persetujuan, dan tidak ada eksekusi ketika bahaya atau kewenangan belum jelas.
