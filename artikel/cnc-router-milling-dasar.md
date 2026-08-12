---
article_id: CUT-07-01
title: "Panduan dasar CNC routing, milling, engraving, dan drilling: istilah, komponen, dan cara kerja"
slug: "cnc-router-milling-dasar"
description: "Panduan dasar untuk memahami CNC routing, milling, engraving, dan drilling: istilah, komponen, alur kerja, perilaku material, serta pertanyaan awal sebelum menentukan pekerjaan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-09-24"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-07
primary_intent: "Memahami fondasi CNC routing, milling, engraving, dan drilling sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Kawan Cutting.co.id"
final_route: "/artikel/cnc-router-milling-dasar.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/64838.html"
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
  - "https://www.iso.org/standard/64835.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212"
---

# Panduan dasar CNC routing, milling, engraving, dan drilling: istilah, komponen, dan cara kerja

Halo, Kawan Cutting.co.id! Banyak orang melihat mesin CNC lalu langsung bertanya, “berapa putaran poros utama (spindle) dan seberapa cepat potongnya?” Padahal kesalahan paling mahal biasanya dimulai lebih awal: fungsi proses tertukar, benda kerja tidak benar-benar tertahan, atau gambar belum menjelaskan acuan ukur dan hasil akhir. Panduan ini membantu Anda membaca fondasinya lebih dahulu, bukan memilih merek, menetapkan angka parameter, atau memutuskan opsi terbaik untuk satu kasus.

Jawaban singkatnya, kendali numerik komputer (CNC) adalah sistem yang mengubah geometri dan urutan gerak terprogram menjadi gerak pahat terhadap benda kerja. Perutean (routing), pemesinan (milling), pengukiran (engraving), dan pengeboran (drilling) berbeda terutama pada tujuan pemotongan, bentuk pahat, arah serta kedalaman pengikisan, dan cara hasilnya diperiksa. Kualitas akhir tidak ditentukan poros utama saja; ia lahir dari kecocokan material, pahat, penjepitan, jalur pahat, pengeluaran geram, dan pemeriksaan. Data material, gambar terbitan yang berlaku, manual mesin, dan persetujuan penanggung jawab dapat mengubah keputusan.

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

Gambar ini adalah aset lokal situs, bukan dokumentasi proyek tertentu.

## Hasil akhir dan prasyarat: tentukan apa yang harus terbukti

Sebelum menyebut sebuah pekerjaan “pemesinan (milling)” atau “perutean (routing)”, nyatakan dulu hasil yang ingin dibuktikan. Apakah Anda membutuhkan lubang dengan posisi tertentu, bidang yang rata, alur, relief dangkal, kontur luar, atau hanya tanda pada permukaan? Jawaban ini menentukan informasi yang perlu disiapkan dan mencegah istilah proses menggantikan kebutuhan sebenarnya.

Mesin, pahat, sistem kontrol, meja, penjepit, penghisap atau pengarah geram, serta alat ukur bekerja sebagai satu rangkaian. Poros utama (spindle) adalah penggerak putar pahat; ia bukan jaminan bahwa setiap pahat cocok untuk setiap bahan. Sumbu atau arah gerak (axes) menjelaskan arah gerak relatif yang dikendalikan, sementara jalur pahat (toolpath) adalah urutan posisi yang dihitung dari geometri. Program yang terlihat benar tetap perlu dicocokkan dengan titik nol, ukuran benda kerja, dan orientasi nyata di meja.

Prasyarat paling aman adalah gambar atau model dengan revisi yang jelas, identitas material dan ketebalan, area yang boleh dijepit, permukaan acuan, target bentuk, dan cara hasil akan diukur. Bila objek menjadi bagian struktur atau instalasi, katalog SNI 1729:2020 hanya menunjukkan identitas publik standarnya, bukan memberi Anda ukuran anggota, kapasitas, sambungan, atau persetujuan desain; [NEEDS TINJAUAN: minta paket gambar terbitan dan tinjauan insinyur sebelum klaim kecukupan struktural](https://pesta.bsn.go.id/produk/detail/12882-sni17292020). Pembaca yang baru mulai dapat menguji kesiapan dengan satu pertanyaan sederhana: “Bukti apa yang membuat saya menyatakan bagian ini selesai?”

## Tetapkan batas pekerjaan: empat nama proses, empat pertanyaan berbeda

Istilah yang terdengar mirip sering membuat pembelian dan instruksi kerja melenceng. Bagian ini membedakan maksud tiap proses secara konseptual agar Anda tidak meminta satu proses melakukan pekerjaan yang lain.

Perutean (routing) biasanya dipakai untuk pemotongan atau pembentukan kontur pada lembaran atau benda kerja yang relatif ringan, dengan pahat yang mengikuti jalur dua atau tiga dimensi. Pemesinan (milling) mengikis material dengan pahat berputar untuk membuat bidang, kantong, alur, atau kontur yang membutuhkan kendali lebih atas gerak dan penjepitan. Pengukiran (engraving) menandai atau mengikis area sempit untuk teks, garis, atau detail permukaan; kedalamannya tetap harus didefinisikan, bukan disimpulkan dari nama proses. Pengeboran (drilling) membuat lubang dengan gerak masuk pahat yang dominan sepanjang sumbu lubang, lalu kualitasnya dipengaruhi oleh posisi awal, pembuangan geram, dan kondisi pahat.

Perbedaan itu bukan kelas mutu otomatis. Mesin routing dapat memiliki sumbu dan spindle yang cukup untuk pekerjaan tertentu, sedangkan mesin milling dapat gagal bila benda kerja bergetar. Yang perlu Anda tetapkan adalah geometri yang diminta, toleransi yang benar-benar diperlukan, akses pahat, material, dan cara inspeksi. Untuk contoh antarmuka proses, rujukan internal [halaman CNC milling](/cnc/milling) dapat membantu pembaca melanjutkan istilah umum tanpa menjadikannya bukti performa proyek.

Scope artikel ini berhenti pada fondasi dan pertanyaan awal. Matriks pemilihan proses, risiko, dan kecocokan kasus berada di artikel terpisah; rincian ukuran, toleransi, dan spesifikasi numerik juga membutuhkan paket data tersendiri. [NEEDS REVIEW: jangan menerbitkan rekomendasi proses atau angka parameter sebelum gambar, material, pahat, mesin, dan persetujuan teknis tersedia.]

## Komponen dan mekanisme: dari perintah menjadi geram

Bayangkan urutannya dari model ke permukaan benda kerja. Perangkat lunak membuat geometri dan jalur pahat, pengendali menerjemahkan jalur menjadi perintah sumbu, poros utama memutar pahat, lalu pemotongan menghasilkan geram yang harus keluar dari zona potong. Pencekaman benda kerja (workholding), yaitu cara benda kerja ditahan, menjaga hubungan antara benda kerja dan jalur tersebut. Jika salah satu hubungan bergeser, permukaan yang tampak rapi belum tentu berada di lokasi yang benar.

Keterlibatan pahat (tool engagement) berarti seberapa jauh sisi pahat benar-benar bersentuhan dengan material pada satu gerakan. Keterlibatan terlalu ringan dapat menyapu permukaan tanpa memotong efektif; terlalu besar dapat menambah gaya, panas, dan getaran. Laju gerak (feeds) adalah gerak relatif pahat, sedangkan kecepatan putar (speeds) merujuk pada kondisi gerak yang terkait. Keduanya bukan angka universal karena dipengaruhi material, diameter dan geometri pahat, kekakuan mesin, penjepitan, serta target permukaan. Jangan menyalin angka dari bahan lain hanya karena nama pahatnya sama.

Geram yang tidak dikeluarkan dapat kembali masuk ke zona potong, menggores permukaan atau menambah panas. Karena itu pengeluaran geram (chip evacuation), yakni pengeluaran geram dengan arah aliran, ruang alur pahat, penyedotan, atau metode lain yang sesuai, harus dipikirkan bersama jalur pahat. Penghisap debu tidak boleh dianggap sebagai pengganti pelindung mesin atau pengendalian bahaya; kewajiban keselamatan perlu mengikuti kondisi kerja dan aturan yang berlaku, termasuk [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018) dan prinsip keselamatan kerja pada [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970).

Untuk bahan pembersih, pelapis, atau bahan habis pakai, baca label serta lembar data keselamatan. [OSHA 29 CFR 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200) hanya contoh komunikasi bahaya dari Amerika Serikat, bukan hukum Indonesia atau batas paparan proyek.

Sumbu, poros utama, pemegang pahat (collet), meja, sensor atau titik referensi, dan pelindung membentuk rantai kendali. Pada perawatan atau penyetelan, energi listrik, gerak, gravitasi, dan energi tersimpan tidak boleh diperlakukan sebagai satu sakelar saja. Pengendalian energi berbahaya memerlukan prosedur spesifik mesin dan otorisasi yang jelas; [Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016) serta [pedoman pengendalian energi OSHA 1910.147](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147) dapat menjadi rujukan kerangka, bukan izin menyalin urutan kerja ke mesin Anda.

Untuk instalasi listrik, cocokkan pula lingkup [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015). Status dan tata cara pengawasan ketenagakerjaan perlu dicek pada [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026). Pekerjaan pemotongan atau pengelasan panas dapat merujuk [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252) sebagai pembanding Amerika Serikat saja, bukan hukum Indonesia.

## Jalur pahat, kantong, kontur, dan kondisi akhir: baca hasil sebelum menjalankan program

Kesalahan umum adalah mengira jalur pahat (toolpath) hanya garis di layar. Sebenarnya ia juga memuat urutan masuk, arah lintasan, area yang diambil, sisa material, dan cara pahat keluar. Kantong (pocket) adalah area yang dikosongkan di dalam batas tertentu; kontur (contour) adalah lintasan mengikuti batas luar atau dalam. Keduanya mungkin memakai geometri mirip, tetapi risiko benda terlepas, sisa material, dan akses pengukuran dapat berbeda.

Kondisi akhir (finish) berarti kondisi permukaan atau tepi yang diharapkan, bukan sekadar “sudah dipotong”. Bekas lintasan, geram tajam (burr), serat terangkat, perubahan warna karena panas, dan tepi yang tajam adalah observasi yang perlu dicatat; tidak satu pun otomatis membuktikan bahwa bagian telah memenuhi fungsi. Pemilihan pahat dan arah serat atau struktur material memengaruhi mekanismenya, sehingga sampel uji dan kriteria penerimaan harus disepakati sebelum produksi bila hasil permukaan penting.

Untuk produk yang akan dilapisi atau terpapar lingkungan, persiapan permukaan dan sistem perlindungan harus ditentukan dari proyek, bukan dari foto hasil potong. [ISO 12944-8](https://www.iso.org/standard/64838.html) membahas penyusunan spesifikasi perlindungan korosi dalam konteks yang lebih luas; halaman abstraknya tidak memberi Anda sistem lapisan, ketebalan, atau umur layanan untuk benda tertentu. Jika targetnya lubang, Anda juga perlu memeriksa diameter, posisi, sumbu, burr, dan kemampuan alat ukur. Rute internal [CNC side-hole drilling](/cnc/mesin/side-hole-drilling) berguna bila pertanyaan Anda sudah bergeser khusus ke lubang samping.

Rujukan tambahan tentang sistem pelapis [ISO 12944-5](https://www.iso.org/standard/77795.html) dan [ISO 12944-4](https://www.iso.org/standard/64835.html) tetap harus dicocokkan dengan produk serta lingkungan proyek; halaman standar tidak membuktikan ketebalan atau umur layanan aset Anda.

## Urutan kerja yang dapat diaudit, bukan resep parameter

Mulailah dengan mengunci identitas file, revisi, material, orientasi, titik nol, dan area penjepitan. Setelah itu cocokkan pahat dan toolpath dengan geometri yang hendak dibuat, lalu lakukan simulasi atau pemeriksaan lintasan yang tersedia pada sistem Anda. Periksa apakah ada gerakan yang melampaui batas, area yang tidak terjangkau, sisa material yang sengaja ditinggalkan, atau masuk pahat yang berbenturan dengan penjepit.

Sebelum mulai, pastikan benda kerja benar-benar tertahan dan pelindung, tombol berhenti, serta pengendalian akses berfungsi. Standar pengamanan mesin [OSHA 1910.212](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212) adalah rujukan asing untuk prinsip pelindung mesin, bukan aturan Indonesia yang boleh disalin mentah. Di Indonesia, penanggung jawab K3 perlu menilai bahaya aktual, tata letak, energi, debu, kebisingan, dan interaksi operator. Jangan menjalankan program hanya karena simulasi tidak menampilkan pesan kesalahan.

Mulai dengan kondisi uji yang telah disetujui untuk memastikan titik nol, arah sumbu, dan respons proses sesuai harapan. Selama pemotongan, amati perubahan bunyi, getaran, aliran geram, panas, dan pergeseran benda kerja, tetapi jangan mendekatkan tangan atau menonaktifkan pelindung untuk “melihat lebih jelas”. Bila tanda tidak sesuai, hentikan melalui cara yang ditetapkan mesin dan lakukan diagnosis oleh orang berwenang. Parameter aktual dan urutan aman harus berasal dari manual produsen asli, prosedur tertulis, dan evaluasi lokasi; [NEEDS TINJAUAN: tetapkan metode uji dan otorisasi mulai untuk mesin yang digunakan.]

## Titik berhenti dan kondisi berhenti: kapan asumsi harus diganti bukti

Titik tahan (hold point) adalah kondisi ketika pekerjaan sengaja berhenti agar bukti diperiksa sebelum langkah berikutnya. Tahan proses bila revisi gambar tidak jelas, material atau ketebalan tidak cocok, pahat tidak teridentifikasi, titik nol belum terverifikasi, penjepitan menghalangi jalur, geram menumpuk, atau hasil uji menunjukkan getaran dan panas yang tidak dijelaskan. Menunda lebih murah daripada memperbaiki kelompok produksi yang dibuat dari asumsi yang salah.

Teman Cutting.co.id, jangan menyamakan inspeksi visual dengan penerimaan teknis. Sistem inspeksi perlu menyebut metode, cakupan, teknik, personel, alat, kondisi permukaan, status verifikasi alat, laporan, dan dasar penerimaan. [ISO 17635](https://www.iso.org/standard/85705.html) menjelaskan bahwa unsur-unsur pemeriksaan perlu dipertimbangkan bersama, sedangkan [ISO 9712](https://www.iso.org/standard/75614.html) berkaitan dengan kualifikasi personel pengujian tak merusak; abstrak publiknya tidak memberi batas cacat atau angka penerimaan untuk proyek Anda.

Untuk sambungan las, [ISO 5817:2023](https://www.iso.org/standard/80209.html), [ISO 15614-1](https://www.iso.org/standard/51792.html), dan [ISO 9606-1](https://www.iso.org/standard/54936.html) memiliki lingkup mutu atau kualifikasi yang berbeda; ketiganya bukan bukti otomatis bahwa pekerjaan CNC Anda diterima.

Hentikan dan minta tinjauan bila komponen yang dikerjakan termasuk bagian penahan beban, pelindung keselamatan, sambungan kritis, atau antarmuka yang mengubah perilaku sistem. [NEEDS TINJAUAN: insinyur atau penanggung jawab berwenang harus menetapkan dasar penerimaan, toleransi, dan dampak perubahan sebelum bagian dipasang atau dilepas dari status karantina.]

## Verifikasi hasil dan serah terima: simpan jejak keputusan

Hasil yang dapat dipertanggungjawabkan bukan hanya benda yang tampak selesai, melainkan hubungan antara perintah, material, alat, pemeriksaan, dan keputusan. Simpan identitas file dan revisi, material atau kelompok produksi bila dipersyaratkan, pahat yang digunakan, kondisi penjepitan, catatan kejadian, hasil ukur, foto bila memang diperlukan, serta nama dan kewenangan orang yang menerima. Paket mutu fabrikasi yang terstruktur biasanya memerlukan dokumen pengendali, identitas sambungan atau komponen, kriteria inspeksi, hasil, ketidaksesuaian, disposisi, dan penutupan; [ISO 3834-6](https://www.iso.org/standard/83335.html) membantu membingkai kebutuhan tersebut, tetapi bukan sertifikat bahwa pekerjaan CNC tertentu otomatis memenuhi mutu.

Saat serah terima, cocokkan tiga hal: geometri terhadap gambar yang berlaku, kondisi permukaan terhadap kriteria yang disepakati, dan catatan proses terhadap identitas benda kerja. Jika ada deviasi, tulis siapa yang menilainya, apa dampaknya, dan apakah perlu pengerjaan ulang atau persetujuan penyimpangan. Jangan menghapus catatan karena hasil akhirnya terlihat baik; jejak itulah yang membantu saat bagian dirawat, diganti, atau dipersoalkan kemudian.

Serpihan, cairan, atau kain lap yang terkontaminasi perlu diklasifikasikan dan dikelola sesuai kegiatan serta izin; [PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021) adalah rujukan umum lingkungan, bukan izin untuk mencampur atau membuang limbah.

## Jalan pintas yang sering gagal: menyalin parameter dari internet

Menyalin laju gerak (feeds), kecepatan putar (speeds), atau kedalaman potong dari video dan forum memang terasa cepat. Masalahnya, angka itu lahir dari kombinasi material, pahat, kekakuan, penjepitan, pendinginan atau penyedotan, serta target kondisi akhir yang belum tentu sama. Mekanismenya sederhana: keterlibatan pahat dan pembentukan geram berubah, lalu gaya dan panas berubah; hasilnya dapat berupa getaran, patah pahat, permukaan buruk, atau ukuran meleset.

Alternatif yang lebih dapat diaudit adalah menguji asumsi satu per satu pada material yang sama, menggunakan prosedur dan pengawasan yang disetujui, lalu mencatat observasi serta hasil ukur. Jangan menjadikan artikel pengantar ini sebagai izin untuk memilih angka. Sobat Cutting.co.id, bila vendor hanya meminta “ukuran dan jumlah” tanpa bertanya material, toleransi, penjepitan, arah serat, atau hasil akhir, anggap itu sinyal untuk memperjelas paket kerja, bukan alasan menutup pertanyaan.

## Kesimpulan: fondasi CNC dimulai dari hubungan sebab-akibat

Perutean, pemesinan, pengukiran, dan pengeboran adalah cara berbeda untuk mengubah material dengan pahat yang dikendalikan; fondasinya sama-sama menuntut geometri yang jelas, sumbu dan poros utama yang dipahami, keterlibatan pahat serta laju gerak/kecepatan putar yang divalidasi, pencekaman yang kaku, pengeluaran geram, jalur pahat yang diperiksa, dan kriteria kondisi akhir yang dapat diukur. Langkah berikutnya adalah kumpulkan gambar terbitan, identitas material, target ukuran atau permukaan, rute inspeksi, dan persetujuan orang yang berwenang, kemudian minta tinjauan teknis untuk kasus Anda.

Aturan operasinya sederhana: jangan menjalankan program hanya karena namanya terdengar tepat atau simulasi tampak bersih. Jalankan setelah hubungan antara benda kerja, pahat, jalur, energi, dan bukti penerimaan benar-benar cocok; bila data penting belum ada, tinggalkan [NEEDS REVIEW: keputusan teknis menunggu bukti proyek dan kompetensi yang sesuai].
