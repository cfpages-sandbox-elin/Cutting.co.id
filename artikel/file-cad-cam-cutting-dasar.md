---
article_id: CUT-03-01
title: "Panduan dasar gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi: istilah, komponen, dan cara kerja"
slug: "file-cad-cam-cutting-dasar"
description: "Panduan praktis untuk memahami isi gambar kerja dan file CAD/CAM, mengendalikan revisi, serta menyiapkan data produksi yang dapat ditelusuri sebelum pekerjaan dimulai."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-05-22"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-03
primary_intent: "Memahami fondasi gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Teman Cutting.co.id"
final_route: "/artikel/file-cad-cam-cutting-dasar.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/54936.html"
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

# Panduan dasar gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi: istilah, komponen, dan cara kerja

Halo, Teman Cutting.co.id! Banyak pekerjaan cutting meleset bukan karena mesin tidak mampu, melainkan karena orang mengirim gambar yang tampak benar tetapi tidak menjelaskan satuan, versi, titik acuan, atau bentuk garis yang harus dipotong. File CAD (perancangan berbantuan komputer) dan CAM (pembuatan berbantuan komputer) bukan sekadar gambar di layar; keduanya adalah instruksi yang harus bisa dibaca manusia, diproses perangkat lunak, lalu dilacak kembali ketika ada perubahan.

Jawaban singkatnya: perlakukan paket produksi sebagai satu kesatuan yang berisi gambar kerja, berkas geometri, catatan material dan proses, identitas revisi, serta bukti persetujuan. Sebelum file dilepas, cocokkan bentuk, satuan, skala, titik datum, toleransi, dan nama versi. Jika salah satu belum jelas, tahan pekerjaan dan minta klarifikasi; angka pilihan mesin atau spesifikasi akhir tetap memerlukan data proyek dan review teknis yang sesuai.

![Ilustrasi Mesin Advertising CNC Plasma Cutting Machine](/wp-content/uploads/2023/01/Mesin-Advertising-CNC-Plasma-Cutting-Machine.webp)
Ilustrasi umum dari aset lokal; gambar ini bukan dokumentasi proyek tertentu.

## Hasil akhir yang perlu tersedia sebelum file dikirim

Bagian ini menjelaskan bentuk paket yang dapat dipahami penerima, supaya Anda tidak mengira satu lampiran sudah cukup. Kita akan memisahkan dokumen yang menjelaskan maksud, data yang menggerakkan mesin, dan bukti siapa yang menyetujui.

Tujuannya bukan membuat template untuk semua proyek, melainkan memastikan pertanyaan dasar terjawab. Paket yang terkontrol biasanya menyebut fungsi komponen, dimensi dan titik acuan, material serta sambungan, antarmuka dengan bagian lain, toleransi, urutan pembuatan, pemeriksaan, dan cara menangani penyimpangan. Ringkasan SNI 1729:2020 dan abstrak ISO 3834-6:2024 sama-sama menempatkan dokumen pengendali, revisi, persyaratan fabrikasi, inspeksi, dan penerimaan sebagai bagian dari pekerjaan yang dapat ditelusuri; abstrak tersebut tidak menggantikan teks standar lengkap ([BSN SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

Mulailah dengan lembar gambar yang memuat judul, nomor dokumen, tanggal, pembuat, pemeriksa, penyetuju, satuan, dan status penerbitan. Di sampingnya, siapkan geometri untuk proses: format asli CAD, format pertukaran bila diperlukan, dan keluaran CAM yang memang disetujui. Catatan material, tebal, arah serat atau tekstur jika relevan, metode finishing, dan kebutuhan pemeriksaan jangan disebar di chat yang sulit dicari.

Pihak yang berwenang harus jelas. Pemilik kebutuhan menetapkan fungsi, perancang mengendalikan geometri, pengawas atau engineer menyetujui basis teknis, dan operator memastikan format dapat diproses. Bila kewenangan itu belum ditetapkan, tandai `[NEEDS BASIS PERSETUJUAN: siapa yang mengesahkan file untuk produksi]` daripada menebak bahwa pengirim file otomatis berwenang.

## Istilah geometri yang sering tertukar

Sebelum membaca menu perangkat lunak, pahami arti bentuk yang dikirim. Kesalahan di sini membuat hasil potong bergeser walau nama file dan gambar pratinjau terlihat sama.

Geometry berarti bentuk matematis objek: garis, busur, lingkaran, dan kurva yang membentuk kontur. Units adalah satuan, misalnya milimeter atau inci; scale adalah perbandingan tampilan terhadap ukuran nyata. Scale 1:1 hanya berguna bila satuan dan titik acuan sudah benar. File dapat tampak proporsional di layar tetapi tetap salah ukuran saat diimpor jika satuannya dibaca berbeda.

Layers (lapisan) memisahkan fungsi, misalnya garis potong, garis etsa, tanda tekuk, dan garis bantu. Closed vector atau vektor tertutup berarti ujung-ujung kontur bertemu membentuk batas tanpa celah. Mesin atau perangkat lunak CAM dapat memperlakukan kontur terbuka sebagai garis yang tidak punya bidang untuk diisi, sehingga hasil nesting atau pemotongan berbeda dari maksud gambar. Periksa dengan fungsi pengukuran dan pemeriksaan kontur, bukan hanya dengan zoom.

Datum adalah titik, garis, atau bidang acuan untuk memberi ukuran dan posisi. Ukuran dari datum yang konsisten mencegah setiap orang mengambil tepi yang berbeda sebagai nol. Untuk lubang, slot, dan fitur berulang, catat koordinat atau jarak dari datum serta arah sumbu. Jangan menyebut “di tengah” tanpa ukuran atau acuan yang dapat diuji.

Gambar kerja juga perlu catatan bend dan machining. Bend note menjelaskan garis atau maksud tekuk, sedangkan machining note menjelaskan fitur yang dibuat melalui proses pemesinan. Maknanya harus diterjemahkan ke operasi yang disetujui; simbol atau singkatan internal tanpa legenda mudah disalahpahami. Jika detail tekuk, radius, urutan, atau allowance belum tersedia, tinggalkan `[NEEDS DATA TEKUK]` dan hentikan pelepasan ke produksi.

## Satuan, toleransi, dan hubungan gambar dengan hasil nyata

Satuan menjawab “berapa besar”, sedangkan toleransi menjawab “seberapa jauh penyimpangan masih diterima”. Keduanya bekerja bersama: ukuran 100 dengan toleransi yang tidak ditulis tidak memberi batas penerimaan yang bisa dipakai pemeriksa. Toleransi umum, toleransi fitur khusus, dan kondisi pengukuran harus merujuk pada basis desain yang disetujui; jangan mengambil angka dari kebiasaan bengkel.

Sebagai contoh, toleransi posisi lubang memengaruhi pasangan baut, tetapi tidak otomatis membuktikan rangka akan kuat atau sambungan akan lolos pemeriksaan. ISO 17635:2025 menjelaskan bahwa metode, cakupan, teknik, personel, peralatan, kondisi permukaan, laporan, dan dasar penerimaan adalah bukti terpisah. Abstraknya juga mengingatkan bahwa tingkat penerimaan pemeriksaan tak merusak tidak diterjemahkan satu banding satu dari tingkat mutu pengelasan ISO 5817 ([ISO 17635:2025](https://www.iso.org/standard/85705.html), [ISO 5817:2023](https://www.iso.org/standard/80209.html), [ISO 9712:2021](https://www.iso.org/standard/75614.html)). Jadi, hasil ukur tunggal bukan diagnosis lengkap.

Tentukan cara verifikasi sejak awal: alat apa yang dipakai, permukaan mana yang menjadi acuan, siapa yang mengukur, dan catatan apa yang disimpan. Status “lulus” hanya berarti sesuatu jika batas penerimaannya, identitas fitur, metode, dan otorisasinya diketahui. Untuk struktur, tekanan, pengangkatan, atau bagian keselamatan, mintalah review profesional sebelum mengubah desain atau menyatakan layak.

## Kontrol revisi dan penamaan yang mencegah file lama terpakai

Revisi adalah riwayat perubahan yang dapat dibaca, bukan sekadar menambah angka di nama file. Setiap perubahan perlu alasan, bagian yang terdampak, konsekuensi terhadap material atau waktu, pemeriksa, penyetuju, dan tanggal. Prinsip ini membuat perubahan permintaan dapat dibandingkan secara wajar; harga total saja tidak menunjukkan apakah desain, material, pengujian, transportasi, atau dokumentasi termasuk di dalamnya ([UU No. 8 Tahun 1999 tentang Perlindungan Konsumen](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)).

Gunakan nama yang stabil, misalnya `proyek-komponen-area-tipe-revisi-status`, lalu jadikan nomor revisi dan status sebagai metadata yang terlihat. Bedakan “untuk ditinjau” dari “disetujui untuk produksi”; jangan menimpa file lama sehingga jejak perbandingan hilang. Di folder bersama, catat siapa menerima notifikasi perubahan dan bagaimana salinan lama ditarik dari area kerja.

Pemeriksaan sederhana membantu: buka gambar dan file CAM dari paket yang sama, cocokkan hash atau ukuran berkas bila sistem Anda menyediakannya, lalu pastikan nomor revisi di keduanya identik. Jika ada dua file bernama hampir sama, anggap itu risiko sampai pemilik dokumen mengonfirmasi mana yang berlaku. Teman Cutting.co.id, waktu singkat untuk membandingkan revisi jauh lebih murah daripada memotong material dari versi yang sudah dibatalkan.

## Data produksi, material, dan pengiriman yang aman

Data produksi menghubungkan geometri dengan benda nyata: identitas material, ukuran, batch atau heat bila diwajibkan proyek, catatan consumable, finishing, urutan operasi, pemeriksaan, dan pengemasan. Catatan keselamatan data bahan memakai konsep label dan lembar data keselamatan; rujukan OSHA 29 CFR 1910.1200 hanya ilustrasi sumber asing, bukan hukum Indonesia ([OSHA hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)). Jangan menebak komposisi, kompatibilitas, masa simpan, atau parameter proses dari nama dagang saja.

Untuk pekerjaan lapangan, perubahan akses, cuaca, listrik, penghuni, bahan mudah terbakar, ventilasi, dan ruang inspeksi dapat mengubah metode serta risikonya. UU No. 1 Tahun 1970 dan ketentuan Kemnaker menjadi pintu untuk review K3; panduan OSHA tentang pengelasan dan pemotongan tidak boleh diimpor sebagai jarak atau izin yang berlaku di Indonesia ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [OSHA welding, cutting, and brazing](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015)). Pengendalian energi, pelindung mesin, dan izin kerja perlu mengikuti kondisi mesin serta aturan lokal, bukan checklist generik ([Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016), [OSHA control of hazardous energy](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147), [OSHA machine guarding](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212)).

Limbah dan potongan material juga perlu identitas, kontaminasi, penyimpanan, pelabelan, pengangkutan, penerima berwenang, dan catatan yang sesuai aturan setempat. PP No. 22 Tahun 2021 memberi kerangka lingkungan, tetapi tidak otomatis mengklasifikasikan setiap sisa sebagai aman atau dapat didaur ulang ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)). Untuk pemasok, sertifikat personel hanya membuktikan ruang lingkup metode dan masa berlaku orang tersebut; itu bukan bukti seluruh perusahaan atau hasil proyek. ISO 9606-1 dan ISO 9712 perlu dibaca sesuai lingkup dan standar yang berlaku ([ISO 9606-1:2012](https://www.iso.org/standard/54936.html)).

## Titik berhenti sebelum file dinyatakan siap

Bagian ini penting karena pembaca sering ingin langsung mengirim berkas setelah melihat pratinjau. Berhenti bila satuan atau datum tidak jelas, kontur belum tertutup, revisi gambar dan CAM berbeda, material tidak teridentifikasi, toleransi utama hilang, atau penerima tidak tahu dasar penerimaan. Tanda visual pada benda juga tidak cukup untuk menyimpulkan cacat atau kelayakan; gunakan metode pemeriksaan, personel, alat, dan prosedur yang ditetapkan ([ISO 17635:2025](https://www.iso.org/standard/85705.html)).

Jika perubahan menyentuh sambungan, perlindungan mesin, energi, bahan kimia, atau pekerjaan panas, minta persetujuan dan penilaian K3 yang bertanggung jawab. Jika menyentuh struktur atau fungsi keselamatan, jangan mengandalkan “sudah pernah dipakai” sebagai bukti. `[NEEDS REVIEW: basis desain, penerimaan, dan kontrol K3 spesifik proyek]` adalah penanda yang lebih jujur daripada memberi izin umum.

## Verifikasi dan serah terima paket produksi

Sebelum handover, buat daftar yang mengikat setiap berkas dengan revisinya: gambar PDF atau keluaran baca, file CAD asli, file CAM, daftar material, catatan proses, rencana pemeriksaan, hasil ukur, daftar penyimpangan, dan bukti persetujuan. Tulis siapa menerbitkan, siapa memeriksa, tanggal, dasar penerimaan, hasil, dan tindakan jika tidak sesuai. Handover bukan sekadar mengirim tautan atau menerima pembayaran; ruang lingkup garansi, syarat, pengecualian, jalur respons, dan tanggung jawab bukti harus benar-benar tertulis bila diwajibkan kontrak.

Setelah paket diterima, minta penerima membuka satu salinan secara mandiri dan mengonfirmasi nomor revisi, satuan, serta fitur kritis. Simpan catatan pertanyaan dan jawaban di tempat yang dapat ditelusuri. Untuk langkah berikutnya, Anda bisa mempelajari contoh pekerjaan laser pada [panduan laser cutting Yalimo](/laser-cutting-yalimo.html) dan membandingkan konteks daerah lain melalui [laser cutting Yahukimo](/laser-cutting-yahukimo.html); keduanya bukan pengganti persetujuan desain proyek.

## Jalan pintas yang tampak praktis tetapi berisiko

Jalan pintas yang paling sering terjadi adalah mengirim screenshot atau PDF tanpa file sumber, lalu meminta operator “menyesuaikan saja”. Screenshot menyembunyikan satuan, layer, kontur terbuka, serta riwayat perubahan. Operator mungkin dapat menebak maksud, tetapi tebakannya tidak menjadi persetujuan desain dan sulit ditelusuri ketika hasil berbeda.

Alternatif yang lebih aman adalah mengirim paket kecil namun lengkap: gambar dengan satuan dan datum, sumber CAD, keluaran CAM, identitas revisi, catatan material, dan satu kontak pengesah. Jika ada bagian yang belum diketahui, tulis pertanyaan terbuka dan tahan pelepasan. Sobat Cutting.co.id, kejelasan batas yang belum terjawab adalah kemajuan karena mencegah material, waktu, dan bukti terlanjur hilang.

## Kesimpulan dan langkah Anda berikutnya

Gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi bekerja sebagai rantai: geometri menjelaskan bentuk, satuan dan datum menjelaskan ukurannya, toleransi menjelaskan batas, catatan proses menghubungkan ke mesin dan material, sedangkan revisi serta serah terima menjaga siapa yang menyetujui. Tidak ada satu file yang otomatis membuktikan kekuatan, kepatuhan, keselamatan, atau kelayakan sistem.

Kawan Cutting.co.id, sebelum mengirim paket berikutnya, minta penerima menyebutkan nomor revisi, satuan, datum, material, fitur yang dipotong, cara pemeriksaan, dan nama pemberi persetujuan. Cocokkan jawaban itu dengan berkas yang sama; bila salah satu tidak bisa dijawab, simpan `[NEEDS REVIEW]` dan dapatkan data proyek atau review profesional. Aturan operasinya sederhana: jangan produksi dari file yang bentuknya terlihat benar tetapi status, acuan, dan bukti penerimaannya belum dapat dilacak.

## Rujukan resmi yang digunakan

- [BSN SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)
- [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)
- [UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)
- [ISO 17635:2025](https://www.iso.org/standard/85705.html)
- [ISO 9712:2021](https://www.iso.org/standard/75614.html)
- [ISO 12944-5:2019](https://www.iso.org/standard/77795.html)
- [OSHA 29 CFR 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)
- [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)
- [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)
- [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)
- [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)
- [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015)
- [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)
- [Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016)
- [OSHA 29 CFR 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147)
- [OSHA 29 CFR 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212)
- [ISO 5817:2023](https://www.iso.org/standard/80209.html)
- [ISO 9606-1:2012](https://www.iso.org/standard/54936.html)
