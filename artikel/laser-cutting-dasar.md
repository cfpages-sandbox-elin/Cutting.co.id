---
article_id: CUT-05-01
title: "Panduan dasar laser cutting untuk sheet, plate, tube, dan material nonlogam: istilah, komponen, dan cara kerja"
slug: "laser-cutting-dasar"
description: "Pembaca dapat menjelaskan source/material compatibility, thickness, assist gas, focus/nozzle, kerf, HAZ, piercing, reflective risk, edge quality, safety, and downstream work, istilah yang sering tertukar, komponen, mekanisme, serta pertanyaan awal yang perlu diajukan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-07-23"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-05
primary_intent: "Memahami fondasi laser cutting untuk sheet, plate, tube, dan material nonlogam sebelum mengambil keputusan teknis"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/laser-cutting-dasar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/83335.html"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015"
  - "https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016"
  - "https://peraturan.bpk.go.id/Details/146211/permenaker-no-37-tahun-2016"
  - "https://peraturan.bpk.go.id/Details/282464/permenaker-no-11-tahun-2023"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
---
# Panduan dasar laser cutting untuk sheet, plate, tube, dan material nonlogam: istilah, komponen, dan cara kerja

Halo, Sobat Cutting.co.id! Laser pemotongan bukan sekadar “laser menembus bahan”. Hasil potong ditentukan oleh kecocokan sumber laser dengan material, ketebalan, gas bantu, fokus, nozzle, jalur program, dan kondisi mesin. Karena itu, memilih berdasarkan klaim daya atau foto hasil potong saja adalah jalan pintas yang berisiko.

Secara sederhana, berkas laser difokuskan ke area kecil sampai material meleleh, menguap, atau terurai; gas bantu meniup material dari celah potong. Kepala potong bergerak mengikuti geometri digital. Lembaran dan pelat diproses sebagai bidang datar, pipa memerlukan pencekaman serta gerak putar/sumbu tambahan, sedangkan nonlogam (misalnya polimer atau kayu) harus diperiksa reaksinya terhadap panas dan asap. Nilai ketebalan, jenis lensa, gas, dan parameter yang benar tidak bisa dipastikan tanpa data material dan mesin. [NEEDS: material grade/komposisi, ketebalan, mesin, dan tujuan akhir]

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-002`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi pemotongan laser](/wp-content/uploads/2023/01/laser-pemotongan.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `pemotongan laser` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS: LOCAL-002]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi pemotongan laser](/wp-content/uploads/2023/01/laser-pemotongan.jpg)

*Aset lokal situs; gambar ini bukan dokumentasi proyek tertentu.*


## Hasil akhir dan prasyarat

Hasil yang masuk akal dari artikel ini adalah kemampuan menjelaskan alur dan mengajukan pertanyaan yang tepat, bukan menetapkan mesin atau angka parameter untuk kasus tertentu. Sebelum meminta penawaran, siapkan gambar atau DXF dengan revisi yang jelas, material dan ketebalan nominal, ukuran benda kerja, jumlah, sisi yang menjadi muka, toleransi fungsional, serta proses setelah pemotongan seperti bending, welding, coating, atau perakitan.

Catat juga lot atau heat material bila tersedia, sertifikat atau laporan yang menyertainya, dan identitas bahan habis pakai. Praktik pencatatan semacam ini membantu penelusuran fabrikasi dan pemeriksaan ulang; ISO 3834-6 menjelaskan kerangka informasi mutu, tetapi abstraknya tidak menetapkan parameter laser atau kelulusan produk tertentu ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Langkah 1 — tetapkan lingkup

Mulailah dengan membedakan objek kerja. **Lembaran** biasanya merujuk lembaran relatif tipis; **pelat** menekankan material lebih tebal dan kebutuhan penanganan berbeda; **pipa** memiliki permukaan melengkung dan dapat memerlukan chuck, penopang, serta koordinasi sumbu; **nonlogam** tidak otomatis aman dipotong karena sebagian material dapat meleleh, terbakar, atau menghasilkan asap berbahaya.

Istilah yang sering tertukar:

| Istilah | Arti kerja yang perlu dipahami |
| --- | --- |
| Sumber (Source) | Sumber energi laser (misalnya jenis dan karakter berkas), bukan nama material. |
| Kecocokan material (Material compatibility) | Kecocokan sumber, optik, gas, dan proses dengan komposisi serta permukaan material. |
| Ketebalan (Thickness) | Ketebalan aktual yang harus dipotong; bukan kapasitas maksimum yang tertulis di brosur. |
| Gas bantu (Assist gas) | Gas yang membantu membuang lelehan dan memengaruhi panas, oksidasi, serta tampilan tepi. |
| Fokus–nosel (Focus/nozzle) | Fokus menentukan posisi titik energi; nozzle mengarahkan aliran gas dan menjaga jarak kerja. |
| Lebar celah potong (Kerf) | Lebar material yang hilang akibat celah potong; memengaruhi kompensasi geometri. |
| zona terdampak panas (HAZ) | *Heat-affected zone*, zona yang berubah karena panas di sekitar potongan, walau tidak terpotong seluruhnya. |
| Penusukan awal (Piercing) | Tahap awal membuat lubang sebelum lintasan potong berlanjut. |
| Risiko pantulan (Reflective risk) | Risiko pantulan balik pada material reflektif yang dapat mengganggu optik dan keselamatan. |
| Kualitas tepi (Edge quality) | Kondisi tepi: dross, kekasaran, tegak-lurus, perubahan warna, dan burr harus didefinisikan sesuai fungsi. |

Scope juga mencakup antarmuka. Apakah komponen akan langsung dirakit, dibending, dilas, dicat, atau diberi seal? Kerf dan zona terdampak panas (HAZ) mungkin tidak bermasalah pada dekorasi, tetapi bisa mengubah fit-up atau permukaan sambungan. Jangan mengubah artikel pengantar ini menjadi keputusan “material X pasti cocok”; keputusan pilihan membutuhkan pengujian dan tinjauan proyek.

## Langkah 2 — kumpulkan dan cocokkan bukti

Minta operator atau pemasok menjawab pertanyaan berikut secara tertulis: sumber laser apa yang dipakai; rentang material yang benar-benar didukung; ketebalan dan ukuran benda kerja yang direncanakan; gas bantu dan cara pengadaannya; bagaimana fokus, nozzle, serta kebersihan lensa dikendalikan; dan bagaimana hasil pertama diperiksa. Untuk pipa, tanyakan batas diameter, panjang, pencekaman, dan akses pemuatan. Untuk nonlogam, minta identitas komposisi, lapisan, serta lembar data keselamatan produk sebelum pekerjaan dimulai.

Lembar data keselamatan (SDS) dan label membantu mengenali bahaya bahan, tetapi tidak membuktikan bahwa bahan itu kompatibel dengan proses laser. OSHA 29 CFR 1910.1200 dapat menjadi ilustrasi konsep komunikasi bahaya dan SDS, bukan pengganti aturan Indonesia ([OSHA Hazard Communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)). Cocokkan nama dagang, kelompok produksi, substrat, dan kondisi aktual; jangan menebak komposisi dari warna atau foto.

Minta sampel uji dari material yang sama, lalu sepakati cara mengukur dimensi, celah potong (kerf), tegak-lurus, kekasaran, dan perubahan warna. Standar mutu pengelasan seperti ISO 5817 atau metode uji tak merusak (NDT) ISO 17635 tidak otomatis menjadi kriteria pemotongan laser; abstrak ISO hanya menunjukkan ruang lingkup dokumen, bukan angka penerimaan ([ISO 5817](https://www.iso.org/standard/80209.html), [ISO 17635](https://www.iso.org/standard/85705.html)). Jika tepi menjadi bagian sambungan kritis, tetapkan dasar penerimaan (acceptance basis) dari gambar dan spesifikasi proyek.

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman adalah: verifikasi revisi gambar; identifikasi material dan permukaan; periksa kondisi mesin, optik, nozzle, meja, pencekam, dan ventilasi; siapkan program dengan kompensasi celah potong (kerf); lakukan penembusan awal dan lintasan pada sampel; periksa tepi serta dimensi; lalu lanjutkan produksi hanya setelah hasil disetujui. Parameter aktual harus berasal dari manual mesin, data material, uji yang terdokumentasi, dan persetujuan penanggung jawab—bukan dari angka generik di internet.

Pada sheet atau pelat, dukungan meja dan urutan nesting memengaruhi kestabilan bagian. Pada pipa, gerak putar dan pencekaman memengaruhi posisi relatif terhadap fokus. Pada nonlogam, asap, residu, dan potensi api menjadi bagian dari keputusan proses. Bila proses berikutnya welding atau coating, bersihkan dan tandai kondisi permukaan sesuai prosedur yang disetujui; identitas material dan perubahan revisi harus ikut dalam rekaman.

Sobat Cutting.co.id, perlakukan pantulan dan panas sebagai kondisi proses, bukan sekadar cacat kosmetik. Material reflektif, lapisan cermin, atau permukaan yang tidak dikenal memerlukan verifikasi kompatibilitas optik dan perlindungan mesin oleh pihak kompeten. Jangan menguji bahan misterius dengan menaikkan daya secara bertahap tanpa pengendalian.

## Titik henti dan kondisi berhenti

Hentikan pekerjaan dan minta peninjauan jika material, ketebalan, atau lapisan tidak cocok dengan catatan; fokus/nozzle tidak stabil; penembusan awal menimbulkan api atau pantulan tak terkendali; asap tidak tertangani; tepi menunjukkan cacat di luar kriteria; atau gambar berubah tanpa persetujuan. Pekerjaan juga berhenti bila pelindung mesin, interlock, ventilasi, atau kendali energi tidak dapat dipastikan berfungsi.

UU No. 1 Tahun 1970 menjadi dasar umum keselamatan kerja di Indonesia, sementara Permenaker No. 11 Tahun 2026 mengubah sebagian lanskap aturan K3. Karena status dan pencabutan parsial perlu dikonsolidasikan untuk lokasi serta tugas tertentu, jangan menyalin prosedur lama sebagai kewajiban hukum ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)). Tetapkan pengendalian mesin, api, listrik, asap, limbah, dan keadaan darurat melalui penanggung jawab K3 setempat. **[NEEDS: kontrol tugas dan lokasi aktual]**

Rujukan tambahan dibaca sesuai lingkup: [ISO 12944-5](https://www.iso.org/standard/77795.html) membahas sistem pelapisan; [ISO 15614-1](https://www.iso.org/standard/51792.html) dan [ISO 9606-1](https://www.iso.org/standard/54936.html) membahas kualifikasi pengelasan, bukan parameter laser; [ISO 9712](https://www.iso.org/standard/75614.html) membahas kompetensi personel. Regulasi [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [Permenaker No. 12 Tahun 2015](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015), [Permenaker No. 38 Tahun 2016](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016), [Permenaker No. 37 Tahun 2016](https://peraturan.bpk.go.id/Details/146211/permenaker-no-37-tahun-2016), dan [Permenaker No. 11 Tahun 2023](https://peraturan.bpk.go.id/Details/282464/permenaker-no-11-tahun-2023) berlaku sesuai materi dan lokasi; OSHA 1910.147/212/252 adalah rujukan asing. [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya halaman katalog.

## Serah terima dan verifikasi hasil

Sebelum menerima hasil, cocokkan nomor revisi gambar, material dan kelompok produksi, jumlah komponen, orientasi muka, dimensi kritis, kondisi tepi, serta pekerjaan lanjutan yang termasuk atau tidak termasuk. Simpan foto atau laporan inspeksi yang dapat ditelusuri ke lot dan program, catatan deviasi, keputusan perbaikan ulang, serta pihak yang menyetujui.

Kawan Cutting.co.id, bila Anda sedang membandingkan langkah pemesanan di daerah, gunakan [contoh halaman pemotongan laser Wonosobo](/laser-cutting-wonosobo.html) atau [contoh halaman pemotongan laser Wonogiri](/laser-cutting-wonogiri.html) hanya sebagai titik mulai pertanyaan; detail mesin, material, dan lingkup tetap harus dikonfirmasi langsung.

Harga total tidak menjelaskan apakah material, pengujian, deburring, transport, pajak, atau dokumentasi termasuk. Minta rincian lingkup dan catat setiap perubahan beserta alasan, dampak waktu/biaya, persetujuan, dan revisinya. Ini membantu perbandingan yang adil tanpa menyimpulkan hak hukum atau hasil sengketa; ketentuan konsumen tetap perlu ditinjau pada kontrak dan hukum yang berlaku.

## Jalan pintas yang perlu dihindari

Jalan pintas paling umum adalah mengirim file CAD dan hanya menanyakan “bisa potong berapa milimeter?”. Jawaban itu mengabaikan material, lapisan, celah potong (kerf), zona terdampak panas (HAZ), gas, mutu tepi, dan proses setelah pemotongan. Alternatif yang lebih andal adalah mengirim paket data minimum, meminta sampel berbahan sama, menyepakati kriteria penerimaan, lalu merekam siapa yang menyetujui hasilnya.

## Kesimpulan dan langkah berikutnya

Laser pemotongan bekerja melalui energi terfokus, gas bantu, optik, nozzle, gerak terprogram, dan pemeriksaan hasil. Lembaran, pelat, pipa, serta nonlogam memiliki antarmuka dan risiko berbeda; istilah seperti celah potong (kerf), zona terdampak panas (HAZ), penembusan awal, risiko pantulan, dan mutu tepi harus diterjemahkan ke fungsi komponen yang nyata.

Langkah Anda berikutnya: siapkan gambar ber-revisi, identitas material/ketebalan, tujuan proses lanjutan, dan pertanyaan tentang mesin, gas, fokus, keselamatan, serta bukti uji. Jika data material, dasar penerimaan (acceptance basis), atau kontrol K3 belum jelas, tahan pekerjaan dan minta tinjauan teknis yang berwenang. Artikel ini memberi fondasi pertanyaan—bukan pengganti pemilihan spesifikasi atau persetujuan proyek.

Teman Cutting.co.id, aturan operasinya sederhana: jangan mulai hanya karena file bisa dibuka; mulai setelah material, risiko, kriteria hasil, dan penanggung jawabnya jelas.
