---
article_id: CUT-07-04
title: "Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi"
slug: "cnc-router-milling-desain"
description: "Pembaca dapat memetakan input, datum, setup, workholding, urutan operasi, allowance, pemeriksaan, dan dependensi downstream CNC routing, milling, engraving, dan drilling."
status: outline
publication_date: "2025-10-04"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: CUT-07
primary_intent: "Merencanakan setup dan aliran kerja CNC routing, milling, engraving, dan drilling agar dapat diproduksi konsisten"
reader_community: "Cutting.co.id"
reader_address: "Sobat Cutting.co.id"
final_route: "/artikel/cnc-router-milling-desain.html"
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

<!-- GENERATED ARTICLE OUTLINE: expand this file; do not delete scope/evidence constraints -->

# Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi

## Assignment lock

- **Writer task:** Expand this file into one complete article answering: “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”
- **Reader and situation:** Arsitek, engineer, drafter, kontraktor, atau koordinator lapangan
- **Reader outcome:** Pembaca dapat memetakan input, datum, setup, workholding, urutan operasi, allowance, pemeriksaan, dan dependensi downstream CNC routing, milling, engraving, dan drilling.
- **Primary intent:** Merencanakan setup dan aliran kerja CNC routing, milling, engraving, dan drilling agar dapat diproduksi konsisten
- **Reader community:** `Cutting.co.id`
- **Primary friendly address:** `Sobat Cutting.co.id`
- **Natural variants:** `Kawan Cutting.co.id` and `Teman Cutting.co.id`
- **Address cadence:** use a friendly project-community address three to five times in a typical long article, only at natural conversational pivots.
- **Scope boundary:** Tidak memilih proses secara umum; pilihan dimiliki CUT-07-02. Tidak menjadi petunjuk pengoperasian mesin; pelaksanaan dimiliki CUT-07-05.
- **Final public route:** `/artikel/cnc-router-milling-desain.html`
- **Appointed CMS date:** `2025-10-04` (`editorial_backfill`; preserve exactly)
- **Target length:** normally 1,400–2,200 useful words; stop earlier if the answer is complete.
- **Do not drift:** do not turn this page into a broad category page, sales landing page, or substitute for professional/project approval.

## Opening instructions

- Open with the exact short salutation: **“Halo, Sobat Cutting.co.id!”**
- Start with the concrete decision, confusion, risk, or costly shortcut behind **Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi**.
- Give the short answer within the first two or three paragraphs.
- State what evidence or condition can change that answer.
- Later, sprinkle `Sobat Cutting.co.id`, `Kawan Cutting.co.id`, or `Teman Cutting.co.id` at useful warnings, decisions, examples, or the conclusion; do not force them into every section.
- Do not use a generic industry-history or “Di era digital” introduction.


<!-- BEGIN MANAGED IMAGE PLAN -->
## Image plan

- **Image ID:** `LOCAL-008`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi jasa CNC](/wp-content/uploads/2023/01/jasa-CNC.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `jasa CNC` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-008]` and continue drafting the prose.
<!-- END MANAGED IMAGE PLAN -->

## Evidence packet

Use the original source links below. Do not cite this outline or `GLOBAL_RESEARCH.md`.

### KR-01

- **Original sources:** [`TOPICAL_AUTHORITY.md`](TOPICAL_AUTHORITY.md), and [`ARTICLE_CATALOG.md`](ARTICLE_CATALOG.md).
- **Purpose for this article:** Freeze the verified editorial scope for `cutting.co.id` and prevent family research from overriding this project's actual catalog boundaries.
- **Safe grounded facts:** The frozen catalog has 20 parent topics and 120 briefs. Intended readers include homeowners, facility and maintenance teams, small manufacturers, procurement staff, project supervisors, and workshop operators. Repository plans are editorial inputs, not proof of a real workshop, staff, equipment, qualifications, prices, locations, or services.
- **Limits:** Re-read both frozen files if the project role, catalog, URL ownership, or conversion path changes. Do not infer an automotive specialty or add unsupported neighboring trades.

### KR-11

- **Original sources:** [SNI 1729:2020 — official BSN catalog](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024 — official ISO abstract](https://www.iso.org/standard/83335.html), [ISO 12944-8:2017 — official ISO abstract](https://www.iso.org/standard/64838.html).
- **Purpose for this article:** Stop generic fabrication guidance from becoming structural design or approval.
- **Safe grounded facts:** Member size alone cannot establish adequacy. Loads, combinations, geometry, stability, connections, anchors/supports, existing condition, erection sequence, temporary stability, tolerances, fire/corrosion exposure, inspection, and maintenance all affect the complete system.
- **Limits:** No span table, member recommendation, connection detail, anchor choice, load capacity, or “SNI compliant” claim may be generated from these catalog/abstract pages.

### KR-17

- **Original sources:** [Permenaker No. 38 Tahun 2016 — BPK](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016), [OSHA 29 CFR 1910.147 — control of hazardous energy](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147), [Permenaker No. 11 Tahun 2026 — BPK](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026).
- **Purpose for this article:** Make maintenance content evidence-based without inventing universal schedules or promising uptime.
- **Safe grounded facts:** Calendar-based, runtime-based, condition-based, corrective, and statutory work answer different needs. Work order history, failure coding, inspection readings, parts identity, deferred defects, tests, and release authority support trend review and planning.
- **Limits:** Do not provide a universal interval, alarm threshold, remaining-life estimate, spares quantity, uptime saving, or restart decision. Obtain current OEM manuals, asset history, operating context, statutory requirements, and responsible-person approval.

### KR-04

- **Original sources:** [ISO 17635:2025 — official ISO abstract](https://www.iso.org/standard/85705.html), [ISO 9712:2021 — official ISO abstract](https://www.iso.org/standard/75614.html).
- **Purpose for this article:** Prevent visual symptoms or an isolated measurement from being presented as a complete diagnosis or acceptance decision.
- **Safe grounded facts:** Inspection method, coverage, technique, personnel, equipment, surface condition, calibration/verification status, reporting, and acceptance basis are separate evidence items. ISO 17635 also warns that NDT acceptance levels are not a direct one-to-one translation of ISO 5817 quality levels.
- **Limits:** The abstracts do not supply technique parameters, acceptance values, required extent, calibration intervals, or project fitness. Obtain the governing code, full standards, written procedure, and asset-specific inspection plan.

### KR-15

- **Original sources:** [ISO 5817:2023 — official ISO abstract](https://www.iso.org/standard/80209.html), [ISO 17635:2025 — official ISO abstract](https://www.iso.org/standard/85705.html), [ISO 9712:2021 — official ISO abstract](https://www.iso.org/standard/75614.html).
- **Purpose for this article:** Keep QA articles from confusing workmanship levels, NDT technique, indication evaluation, personnel certification, equipment status, and engineering acceptance.
- **Safe grounded facts:** A quality plan needs the governing acceptance basis, joint and examination identification, method/technique and extent, written procedure where required, personnel scope, equipment identity and current calibration/verification, surface/test conditions, report traceability, result, nonconformance, disposition authority, repair cycle, and closeout.
- **Limits:** Do not publish imperfection limits, acceptance tables, technique settings, calibration intervals, or certification equivalence from abstracts. Obtain full current standards and project procedures.

### KR-09

- **Original sources:** [ISO 15614-1:2017 — official ISO abstract](https://www.iso.org/standard/51792.html), [ISO 9606-1:2012 — official ISO abstract](https://www.iso.org/standard/54936.html), [ISO 3834-6:2024 — official ISO abstract](https://www.iso.org/standard/83335.html).
- **Purpose for this article:** Prevent an article from treating a welder card, a WPS, a procedure test, workmanship, and the finished joint's acceptance as interchangeable.
- **Safe grounded facts:** Procedure qualification, production WPS, welder/operator qualification, material/process/position/thickness/diameter range, continuity/validity, equipment condition, consumable control, preheat/interpass control, inspection, and final acceptance are distinct records.
- **Limits:** Both welding-qualification standards are current at verification but under revision. The public abstracts do not provide qualification ranges or test requirements; recheck editions and use licensed text plus the project specification.

### KR-14

- **Original sources:** [UU No. 1 Tahun 1970 — BPK](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018 — official Kemnaker JDIH](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [OSHA 29 CFR 1910.252 — welding, cutting, and brazing](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252), [Permenaker No. 11 Tahun 2026 — BPK](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026).
- **Purpose for this article:** Help readers compare controlled shop fabrication with field work where the environment, interfaces, access, occupants, combustibles, weather, and permits can change the method and risk.
- **Safe grounded facts:** Moving work on site can change fit-up control, position, access, lifting, weather, electrical supply, fume dispersion, fire exposure, nearby operations, traffic/public interface, coating conditions, inspection access, and restoration. A field weld is not justified merely because transport is inconvenient.
- **Limits:** Do not import US distances, permits, or prescriptions. The responsible Indonesian site/K3 authority must approve the current task-specific controls.

### KR-07

- **Original sources:** [ISO 3834-6:2024 — official ISO abstract](https://www.iso.org/standard/83335.html), [ISO 12944-5:2019 — official ISO abstract](https://www.iso.org/standard/77795.html), [OSHA 29 CFR 1910.1200 — hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200).
- **Purpose for this article:** Make material and consumable records usable for fabrication, compatibility, safety, inspection, maintenance, and later failure investigation.
- **Safe grounded facts:** Useful traceability can include material designation, dimensions/heat or batch where required, certificate/report linkage, filler/consumable classification and batch, storage/conditioning, coating product and batch, mixing/application records, replacement-part identity, and approved substitution. The US hazard-communication rule illustrates label and safety-data-sheet concepts but is not Indonesian law.
- **Limits:** Do not infer composition, compatibility, shelf life, storage, mixing ratio, coverage, cure, welding parameter, exposure limit, or disposal route from generic labels. Verify exact product, batch, substrate, environment, and current Indonesian rules.

### KR-08

- **Original sources:** [SNI 1729:2020 — official BSN catalog](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 3834-6:2024 — official ISO abstract](https://www.iso.org/standard/83335.html).
- **Purpose for this article:** Ground fabrication planning in defined requirements rather than verbal descriptions, copied details, or unverified workshop habit.
- **Safe grounded facts:** A controlled fabrication package can need governing documents and revision, function, dimensions/datums, material and joint identity, loads/interfaces, tolerances, fabrication sequence, weld/fastener/coating requirements, inspection and hold points, acceptance basis, handling, installation, and approved deviations.
- **Limits:** The BSN page does not reveal clauses, tolerances, combinations, connection design, execution rules, or acceptance values. Obtain the licensed governing standards and issued-for-work project documents.

### KR-16

- **Original sources:** [UU No. 1 Tahun 1970 — BPK](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 12 Tahun 2015 — official Kemnaker JDIH](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015), [Permenaker No. 5 Tahun 2018 — official Kemnaker JDIH](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [OSHA 29 CFR 1910.1200 — hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200), [Permenaker No. 11 Tahun 2026 — BPK](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026).
- **Purpose for this article:** Provide a systems view of workshop K3 instead of reducing safety to personal protective equipment.
- **Safe grounded facts:** A controlled task starts with elimination/substitution and engineering/administrative controls, then suitable PPE; product identity and current safety data matter for chemicals. Emergency planning must reflect the actual energy, fire, exposure, first-aid, evacuation, communication, and rescue scenario.
- **Limits:** This file supplies no exposure limit, PPE selection, ventilation rate, electrical protection setting, cylinder separation, fire-watch duration, or emergency procedure. Resolve them from current Indonesian rules, site conditions, exact products, and competent K3 review.

### KR-20

- **Original sources:** [PP No. 22 Tahun 2021 — BPK](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021), [Permenaker No. 5 Tahun 2018 — official Kemnaker JDIH](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [OSHA 29 CFR 1910.1200 — hazard communication](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200).
- **Purpose for this article:** Connect source reduction, controlled use, segregation, reuse/recycling, worker exposure, and legal waste disposition without assuming every metal offcut is harmless or recyclable.
- **Safe grounded facts:** Waste identity, contamination, generator/site context, storage, labeling, transport, receiver authorization, records, and current local rules determine the route. Reuse and repair may avoid new material but do not automatically reduce total environmental or safety impact.
- **Limits:** Do not classify a waste, recommend mixing, state a storage limit, name a legal carrier/receiver, or claim a quantified environmental benefit without current Indonesian/local requirements, characterization, mass/energy data, and authorized-party evidence.

### KR-13

- **Original sources:** [SNI 1729:2020 — official BSN catalog](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [ISO 12944-3:2017 — official ISO abstract](https://www.iso.org/standard/64835.html), [ISO 12944-8:2017 — official ISO abstract](https://www.iso.org/standard/64838.html).
- **Purpose for this article:** Treat gates, railings, stairs, canopies, grilles, frames, furniture, and similar products as installed systems rather than decorative workshop objects.
- **Safe grounded facts:** Function and risk can depend on use, users, geometry, edges and entrapment, load and impact, support/anchor substrate, drainage and water traps, dissimilar materials, exposure, access, operation/hardware, coating repair, erection, and future maintenance.
- **Limits:** The cited sources do not provide application-specific dimensions, loads, anchors, child-safety rules, accessibility requirements, or local approvals. Resolve those from the actual project and current governing rules.

### KR-10

- **Original sources:** [Permenaker No. 38 Tahun 2016 — BPK](https://peraturan.bpk.go.id/Details/146207/permenaker-no-38-tahun-2016), [Permenaker No. 11 Tahun 2026 — BPK](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026), [OSHA 29 CFR 1910.147 — control of hazardous energy](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.147), [OSHA 29 CFR 1910.212 — general machine guarding](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.212).
- **Purpose for this article:** Ensure a component-repair article considers the complete machine, energy sources, operating envelope, safeguarding, commissioning, and records.
- **Safe grounded facts:** A repaired shaft, frame, coupling, guard, base, or attachment can alter alignment, balance, clearance, strength, vibration, containment, access, interlocks, or operating hazards. Safe servicing and safe production are related but distinct states.
- **Limits:** Do not publish an isolation sequence, guard dimension, balance tolerance, restart authorization, or fitness claim generically. Verify current Indonesian provisions and exact OEM/site requirements.

## Evidence gates

- **GATE-01:** Resolve the gate from current project evidence and competent review.
- **GATE-02:** Resolve the gate from current project evidence and competent review.
- **GATE-03:** Resolve the gate from current project evidence and competent review.
- **GATE-04:** Resolve the gate from current project evidence and competent review.
- **GATE-05:** Resolve the gate from current project evidence and competent review.
- **GATE-06:** Resolve the gate from current project evidence and competent review.
- **GATE-07:** Resolve the gate from current project evidence and competent review.
- **GATE-08:** Resolve the gate from current project evidence and competent review.
- **GATE-09:** Resolve the gate from current project evidence and competent review.
- **GATE-10:** Resolve the gate from current project evidence and competent review.
- **GATE-11:** Resolve the gate from current project evidence and competent review.
- **GATE-12:** Resolve the gate from current project evidence and competent review.
- **GATE-13:** Resolve the gate from current project evidence and competent review.

If a gate affects the article's main conclusion, keep a visible `[NEEDS ...]` marker for coordinator review. Do not guess.

## Internal-link plan

### Existing local routes

- `/cnc/milling` — use only if it helps the reader's next step; verify the anchor describes the destination.
- `/cnc/milling/` — use only if it helps the reader's next step; verify the anchor describes the destination.
- `/cnc/mesin/side-hole-drilling` — use only if it helps the reader's next step; verify the anchor describes the destination.
- `/cnc/mesin/lathe-router` — use only if it helps the reader's next step; verify the anchor describes the destination.
- `/cnc/mesin/jade-router` — use only if it helps the reader's next step; verify the anchor describes the destination.
- `/cnc/mesin/cnc-router-cylinder` — use only if it helps the reader's next step; verify the anchor describes the destination.

### Planned sibling articles

These are future routes. Do not link them as live until their HTML exists.

- `CUT-07-02` → `/artikel/cnc-router-milling-pilih.html` — Cara memilih CNC routing, milling, engraving, dan drilling: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-07-03` → `/artikel/cnc-router-milling-spesifikasi.html` — Spesifikasi CNC routing, milling, engraving, dan drilling: data, ukuran, toleransi, dan pemeriksaan asumsi
- `CUT-07-05` → `/artikel/cnc-router-milling-pasang.html` — Tahapan produksi CNC routing, milling, engraving, dan drilling: persiapan, first-off, QC, dan serah terima
- `CUT-07-06` → `/artikel/cnc-router-milling-masalah.html` — Masalah pada CNC routing, milling, engraving, dan drilling: gejala, akar penyebab, dan keputusan perbaikan

<!-- BEGIN PUBLIC ARTICLE SECTIONS -->

## Hasil akhir dan prasyarat

- **Purpose:** Nyatakan hasil yang ingin dicapai, siapa yang berwenang, data awal, alat/dokumen, dan kondisi yang harus tersedia.
- **Tie back to this article:** Keep the explanation specific to “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”.
- **Evidence:** Use only relevant facts from the evidence packet; add an original source near consequential claims.
- **Practical value:** Add a concrete question, conditional scenario, checklist item, or decision consequence.
- **Boundary:** Preserve the assignment lock and evidence gates; do not fill missing project facts.

## Langkah 1 — tetapkan scope

- **Purpose:** Jelaskan objek, batas pekerjaan, antarmuka, risiko, serta hal yang sengaja tidak dikerjakan.
- **Tie back to this article:** Keep the explanation specific to “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”.
- **Evidence:** Use only relevant facts from the evidence packet; add an original source near consequential claims.
- **Practical value:** Add a concrete question, conditional scenario, checklist item, or decision consequence.
- **Boundary:** Preserve the assignment lock and evidence gates; do not fill missing project facts.

## Langkah 2 — kumpulkan dan cocokkan bukti

- **Purpose:** Susun dokumen, observasi, data, produk, atau standar yang harus cocok dengan kasus.
- **Tie back to this article:** Keep the explanation specific to “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”.
- **Evidence:** Use only relevant facts from the evidence packet; add an original source near consequential claims.
- **Practical value:** Add a concrete question, conditional scenario, checklist item, or decision consequence.
- **Boundary:** Preserve the assignment lock and evidence gates; do not fill missing project facts.

## Langkah 3 — jalankan urutan kerja

- **Purpose:** Berikan urutan konseptual yang dapat diikuti tanpa berubah menjadi instruksi teknis berbahaya.
- **Tie back to this article:** Keep the explanation specific to “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”.
- **Evidence:** Use only relevant facts from the evidence packet; add an original source near consequential claims.
- **Practical value:** Add a concrete question, conditional scenario, checklist item, or decision consequence.
- **Boundary:** Preserve the assignment lock and evidence gates; do not fill missing project facts.

## Hold point dan kondisi berhenti

- **Purpose:** Nyatakan kapan pekerjaan tidak boleh diteruskan tanpa review, tes, atau persetujuan.
- **Tie back to this article:** Keep the explanation specific to “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”.
- **Evidence:** Use only relevant facts from the evidence packet; add an original source near consequential claims.
- **Practical value:** Add a concrete question, conditional scenario, checklist item, or decision consequence.
- **Boundary:** Preserve the assignment lock and evidence gates; do not fill missing project facts.

## Verifikasi hasil dan handover

- **Purpose:** Buat checklist penerimaan, rekaman, tindak lanjut, dan pemicu koreksi.
- **Tie back to this article:** Keep the explanation specific to “Perencanaan proses CNC routing, milling, engraving, dan drilling: setup, workholding, urutan, dan dependensi”.
- **Evidence:** Use only relevant facts from the evidence packet; add an original source near consequential claims.
- **Practical value:** Add a concrete question, conditional scenario, checklist item, or decision consequence.
- **Boundary:** Preserve the assignment lock and evidence gates; do not fill missing project facts.

## Objection or shortcut to address

- Identify one realistic shortcut a reader may prefer.
- Explain why it can fail in this exact context, using mechanism and evidence rather than scolding.
- Give the safer or more reliable alternative.

## Required conclusion

- Answer the title again in one compact, non-repetitive form.
- Give the reader the next action, document, question, inspection, or professional review to obtain.
- End with an operating rule or honest boundary. Do not end with a generic summary.

## Draft completion checklist

- [ ] Opening answers the main question within two or three paragraphs.
- [ ] The article opens with `Halo, Sobat Cutting.co.id!` and uses friendly `Cutting.co.id` community address naturally three to five times total.
- [ ] Every H2 above has been replaced with finished, non-repetitive prose.
- [ ] Facts, project facts, inferences, assumptions, and judgments are not blurred together.
- [ ] Every consequential claim has an original source or `[NEEDS ...]` marker.
- [ ] No exact standard clause, number, price, test result, capacity, warranty, or personal experience was invented.
- [ ] Internal links use exact listed routes and helpful natural anchors.
- [ ] Future sibling routes are not presented as live.
- [ ] The public prose does not mention prompts, outlines, SEO, AI, or evidence gates.
- [ ] Front matter is preserved; `status` changed from `outline` to `draft` only after completion.
- [ ] Conclusion gives a concrete next action and an honest limit.
