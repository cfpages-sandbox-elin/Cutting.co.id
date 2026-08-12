---
article_id: CUT-01-01
title: "Panduan dasar proses cutting dan machining: istilah, komponen, dan cara kerja"
slug: "proses-cutting-fundamental-dasar"
description: "Pembaca dapat menjelaskan perbedaan pemotongan termal, mekanis, abrasif, turning, milling, routing, bending, serta kapan tidak memakai CNC, istilah yang sering tertukar, komponen, mekanisme, serta pertanyaan awal yang perlu diajukan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-03-14"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-01
primary_intent: "Memahami fondasi proses cutting dan machining sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/proses-cutting-fundamental-dasar.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
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

# Panduan dasar proses cutting dan machining: istilah, komponen, dan cara kerja

Halo, Teman Cutting.co.id! Sebelum memilih mesin atau meminta penawaran, bedakan dulu dua pertanyaan: bagaimana material dipisahkan, dan bagaimana bentuk akhirnya dikendalikan. Cutting memisahkan material dari benda kerja; machining (pemesinan) mengatur bentuk, ukuran, atau permukaan dengan gerak alat terhadap benda kerja. Tidak semua pekerjaan perlu CNC, dan istilah “cutting” tidak otomatis berarti laser.

Jawaban singkatnya: pilih keluarga proses berdasarkan material, bentuk, ketelitian yang diminta, volume, akses, dan risiko pekerjaan. Pemotongan termal memakai panas, pemotongan mekanis memakai gaya alat, sedangkan abrasif mengikis dengan butiran keras. Turning memutar benda kerja, milling memutar alat, routing memakai spindle untuk pola atau tepi, dan bending membentuk tanpa memisahkan material. Data gambar, material, toleransi, serta kondisi pemasangan dapat mengubah pilihan; karena itu keputusan kasus tertentu tetap membutuhkan peninjauan teknis.

![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil yang realistis dari panduan ini adalah peta istilah dan urutan berpikir, bukan resep parameter mesin. Untuk memulai, siapkan gambar atau sketsa dengan satuan yang jelas, jenis dan bentuk awal material, kuantitas, permukaan yang terlihat, fungsi komponen, serta antarmuka dengan bagian lain. Tanyakan pula siapa yang menyetujui gambar, siapa yang memeriksa hasil, dan dokumen mana yang menjadi dasar penerimaan.

Pada pekerjaan fabrikasi yang dikendalikan, paket kerja dapat mencakup dokumen pengarah dan revisinya, dimensi serta datum, identitas material dan sambungan, toleransi, urutan fabrikasi, persyaratan inspeksi, titik tahan (hold point), dan dasar penerimaan. Katalog BSN hanya mengonfirmasi identitas publik SNI 1729:2020, sementara abstrak ISO 3834-6:2024 menjelaskan kerangka mutu; keduanya tidak menggantikan teks standar berlisensi atau gambar kerja yang diterbitkan ([BSN SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

Jika salah satu data itu belum ada, tandai sebagai asumsi terbuka. Jangan mengisi sendiri ukuran, kelas material, atau tingkat penerimaan hanya karena bentuknya tampak sederhana.

## Langkah 1 — tetapkan batas kerja

Mulai dengan batas benda kerja: bagian mana yang dipotong, bagian mana yang tetap, dan antarmuka apa yang harus cocok setelah proses. Catat juga apakah pekerjaan berlangsung di bengkel atau di lapangan. Pemindahan pekerjaan ke lapangan dapat mengubah akses, fit-up, pengangkatan, cuaca, listrik, asap, bahaya kebakaran, lalu lintas, dan akses inspeksi. Undang-Undang Keselamatan Kerja Indonesia menetapkan kerangka keselamatan, sedangkan Permenaker No. 5 Tahun 2018 mengatur aspek keselamatan dan kesehatan lingkungan kerja; kontrol aktual harus ditetapkan oleh penanggung jawab K3 sesuai kondisi setempat ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)).

Bedakan pekerjaan yang memang memisahkan material dari pekerjaan yang hanya mengubah bentuk. Cutting, drilling, dan sawing menghasilkan potongan atau lubang. Bending memberi deformasi terarah tanpa mengurangi kontur utama. Machining biasanya menyisakan chip (geram) untuk mencapai ukuran atau permukaan tertentu. Pengelompokan ini mencegah permintaan “potong lalu tekuk” diterjemahkan sebagai satu operasi yang tidak memeriksa urutan dan allowance.

## Langkah 2 — kumpulkan dan cocokkan bukti

Pemotongan termal meliputi laser, plasma, dan oxy-fuel. Energi panas melelehkan atau mengoksidasi bagian yang dilalui; zona terpengaruh panas, perubahan warna, atau tepi yang perlu dirapikan harus dipertimbangkan terhadap fungsi akhir. Pemotongan mekanis memakai gergaji, gunting, pisau, atau alat potong berputar; gaya jepit dan kondisi alat memengaruhi burr, deformasi, dan keselamatan. Pemotongan abrasif menggunakan roda atau butiran untuk mengikis; debu, percikan, dan keausan media menjadi bagian dari pengendalian pekerjaan. Jangan menyamakan ketiganya hanya dari nama mesin.

Dalam machining, istilah gerak menjelaskan mekanisme. Pada turning, benda kerja berputar di chuck atau collet dan pahat bergerak sepanjang atau menembus sumbu. Pada milling, cutter berputar di spindle sementara meja atau benda kerja bergerak pada satu atau beberapa sumbu. Routing adalah pemesinan dengan spindle dan cutter yang lazim dipakai untuk kontur, alur, atau panel; hasilnya tetap bergantung pada material, pencekaman, dan geometri alat. Bending memakai punch, die, atau rol untuk membentuk radius dan sudut, sehingga springback dan arah serat atau pengerolan material perlu dikonfirmasi, bukan ditebak.

Komponen dasar yang perlu dikenali adalah sumber energi dan penggeraknya, alat potong atau forming tool, sistem pencekaman, meja atau fixture, kendali gerak, media bantu (gas, coolant, atau pelumas bila digunakan), serta pelindung dan perangkat penghentian. CNC (computer numerical control) hanya berarti gerak dikendalikan program; CNC tidak otomatis menjamin material benar, tool tajam, datum tepat, atau hasil diterima.

Kumpulkan bukti yang cocok: revisi gambar, spesifikasi material dan batch bila diperlukan, program atau file geometri yang disetujui, identitas alat, catatan setup, serta rencana pemeriksaan. Untuk bahan kimia atau consumable, identitas produk, label, dan lembar data keselamatan harus dapat ditelusuri; aturan OSHA tentang hazard communication dapat menjadi ilustrasi konsep, bukan hukum Indonesia ([OSHA 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).

Jika Anda perlu melihat contoh konteks layanan tanpa menganggapnya sebagai bukti spesifikasi proyek, bandingkan halaman [laser cutting di Wonosobo](/laser-cutting-wonosobo.html) dan [laser cutting di Wonogiri](/laser-cutting-wonogiri.html) hanya sebagai rujukan navigasi awal.

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman dimulai dari tinjauan gambar dan material, pemeriksaan kesiapan mesin serta pencekaman, penetapan datum dan orientasi, uji awal yang disetujui, proses utama, lalu pembersihan dan pemeriksaan. Detail kecepatan, daya, tekanan, feed, atau ukuran alat harus berasal dari manual mesin, material, dan prosedur yang berlaku; panduan umum ini tidak menggantikannya.

Untuk pekerjaan berulang, simpan identitas program, revisi, operator, material, dan alat. Untuk pekerjaan panas, pisahkan sumber energi, ventilasi, pengendalian api, dan pengawasan sesuai penilaian risiko. OSHA 1910.252 menunjukkan bahwa welding, cutting, dan brazing memerlukan pengendalian bahaya khusus, tetapi jarak, izin, dan preskripsinya tidak boleh diimpor sebagai ketentuan Indonesia ([OSHA 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)).

Kapan tidak memakai CNC? Saat geometri sederhana dan jumlah sedikit, jig manual atau mesin konvensional mungkin lebih mudah ditinjau. CNC juga bukan jawaban tepat bila gambar belum stabil, datum belum disepakati, material tidak teridentifikasi, atau pekerjaan membutuhkan penyesuaian lapangan. Sebaliknya, pola berulang, banyak kontur, atau kebutuhan pencatatan program dapat membuat kendali numerik membantu. Ini adalah pertimbangan awal, bukan keputusan final untuk kasus Anda.

## Titik tahan dan kondisi berhenti

Hentikan proses bila material, revisi gambar, program, alat, pencekaman, atau hasil awal tidak cocok. Berhenti juga saat pelindung, interlock, penghentian darurat, ventilasi, atau pengendalian energi tidak siap. [NEEDS PROJECT REVIEW: penanggung jawab K3 dan engineering menetapkan kontrol task-spesifik, kriteria penerimaan, serta wewenang restart.]

Jangan melanjutkan hanya karena target waktu atau biaya. Teman Cutting.co.id, hold point bukan tanda pekerjaan gagal; ia mencegah satu asumsi kecil berubah menjadi komponen yang salah ukuran atau paparan bahaya yang tidak terkendali.

## Verifikasi hasil dan serah terima

Pemeriksaan harus mengikuti fungsi dan gambar: identitas material, dimensi penting, datum, lubang atau kontur, kondisi tepi, deformasi, dan kebersihan. Bila sambungan las terlibat, bedakan kualifikasi prosedur, spesifikasi prosedur pengelasan (WPS) produksi, kualifikasi juru las, pemeriksaan, dan penerimaan akhir. ISO 15614-1 dan ISO 9606-1 memisahkan jenis kualifikasi tersebut; abstrak publiknya tidak memuat rentang kualifikasi atau syarat uji, sehingga edisi dan teks lengkap harus diverifikasi ([ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html)).

Jika memakai inspeksi visual atau pengujian tak merusak (NDT), catat identitas sambungan, metode, teknik, extent, personel, peralatan, kondisi permukaan, laporan, hasil, dan disposisi ketidaksesuaian. ISO 5817, ISO 17635, dan ISO 9712 menyediakan kerangka berbeda untuk mutu las, pemilihan NDT, dan kompetensi personel; jangan mengambil tabel penerimaan atau interval kalibrasi dari abstrak saja ([ISO 5817](https://www.iso.org/standard/80209.html), [ISO 17635](https://www.iso.org/standard/85705.html), [ISO 9712](https://www.iso.org/standard/75614.html)). Handover yang baik menyertakan gambar dan revisi, catatan material, setup atau program, hasil pemeriksaan, daftar penyimpangan yang disetujui, serta otorisasi pelepasan.

## Cara cepat yang sering menyesatkan

Jalan pintas paling umum adalah mengirim foto benda dan meminta “potong persis seperti ini”. Foto tidak menetapkan datum, material, toleransi, sisi referensi, atau fungsi antarmuka. Alternatif yang lebih andal adalah mengirim gambar berdimensi, material, jumlah, tujuan komponen, dan pertanyaan penerimaan; bila belum tersedia, minta review teknis sebelum produksi.

## Kesimpulan dan langkah berikutnya

Cutting memisahkan material, machining membentuk ukuran atau permukaan, dan bending mengubah bentuk; termal, mekanis, abrasif, turning, milling, serta routing memiliki mekanisme dan risiko berbeda. CNC adalah sarana kendali, bukan jaminan mutu. Kawan Cutting.co.id, langkah berikutnya adalah membuat lembar singkat berisi material, geometri, kuantitas, toleransi, antarmuka, lingkungan kerja, dan siapa yang menyetujui hasil. Gunakan lembar itu untuk meminta penilaian proses, bukan untuk menebak parameter. Pilihan akhir, angka spesifikasi, dan pelepasan pekerjaan tetap menunggu dokumen proyek serta review kompeten.
