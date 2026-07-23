# Topical Authority — cutting.co.id

## Role and boundary

The domain is the portfolio’s Indonesian process and procurement hub for cutting, machining, bending, and CNC-enabled fabrication. Its useful role is to help designers, fabricators, maintenance teams, buyers, operators, and owners translate a part need into a manufacturable file, appropriate process, controlled quality, comparable quote, and safe handover. Machine/product routes may support commercial intent, while process education remains neutral.

This map is domain-specific. Cannibalization is evaluated only among URLs on **cutting.co.id**. Syamsul-owned domains are independent editorial properties: they may answer the same query from the same or another point of view, and that cross-domain overlap is an opportunity rather than a reason to omit useful coverage here.

## Evidence audited

- Repository: static WordPress export on `main`, remote `cfpages-sandbox-elin/Cutting.co.id`; no repository-local `AGENTS.md`; working tree clean before planning.
- Primary WordPress sitemaps: `page-sitemap.xml` has 76 entries; thirteen post sitemaps have 2,416 entries but only 2,253 unique post paths, including 163 duplicate entries across sitemap files. Together they represent 2,492 entries and 2,329 unique paths.
- All 2,253 unique post paths are mass local templates: 490 `jasa-cutting-cnc-*`, 455 `laser-cutting-*`, 440 `jual-mesin-cnc-*`, 424 `bubut-*`, and 444 `bending-*` paths.
- The 76 page entries contain three utility/root pages, thirteen process/service hubs, and sixty `/cnc/mesin/` category/model routes. The machine catalog mixes laser, plasma, router, stone, styrofoam, cylinder, woodworking, automatic-feed, boring, scanner, vacuum-press, and polish equipment.
- `sitemap-complete.xml` exposes only 119 absolute URLs and omits most post templates; `video-sitemap.xml` has 2,426 entries, mostly duplicate references plus query-form WordPress URLs. Sitemap disagreement is itself a crawl/indexation risk.
- Audited evidence included homepage/navigation HTML, CNC/bubut/bending/laser and machine hierarchies, category and author archives, all 16 sitemap files, redirects, README inventory, and sitemap generator source.

Evidence counts describe repository and sitemap state audited on 2026-07-23; they do not prove indexation, traffic, quality, or current commercial availability.

## Existing coverage and risks

- **Doorway risk:** the entire 2,253-post corpus is generated from five service/product stems plus locations. Local value, capability, logistics, case evidence, and operational presence were not demonstrated by sitemap structure.
- **Sitemap integrity:** thirteen post sitemaps contain 163 duplicate entries; the 119-URL complete sitemap contradicts the 2,329 unique primary paths; video sitemap adds query-form variants.
- **Intent collision:** `/cnc/`, `/cnc/cutting/`, `/potong`, `/laser`, `/bending`, `/bubut`, category archives, machine pages, and location templates can all compete for service/process/machine intents.
- **Catalog ambiguity:** sixty machine routes mix categories and model-like pages with unclear current availability, manufacturer evidence, specifications, support, and canonical role.
- **Safety/evidence risk:** laser, plasma, rotating machines, pressure, hot work, dust/fume, heavy stock, guarding, and copied machine parameters require competent review and current primary sources.

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
| --- | --- | --- | --- | --- |
| /jasa-cutting-cnc-*.html | 490 local-template paths target the same service stem. | manual review | One national/process service route plus only verified operational locations | Use GSC, leads, links, unique content, fulfilment coverage, and location proof. |
| /laser-cutting-*.html | 455 local-template paths overlap `/laser` and laser education. | manual review | CUT-05 education; one laser quotation route; real local routes only | Compare query, title/H1, conversions, and content similarity before redirect. |
| /jual-mesin-cnc-*.html | 440 local sales templates compete with `/cnc/mesin/` hierarchy and model pages. | manual review | CUT-16 machine-selection hub and verified current catalog routes | Confirm business role, availability, specs, manufacturer authority, leads, and support. |
| /bubut-*.html | 424 local templates overlap `/bubut`, `/bubut/cnc`, and `/bubut/korter`. | manual review | CUT-08 education; retained service routes by actual capability | Separate turning, boring/korter, repair, and city intent using evidence. |
| /bending-*.html | 444 local templates overlap `/bending`. | manual review | CUT-09 education and one transactional service route | Check unique capacity/tooling/logistics/cases; avoid city swaps. |
| /cnc, /cnc/cutting, /potong | Broad process/service labels can satisfy the same query. | merge | CUT-01 hub plus one clearly transactional route | Inspect live headings, backlinks, leads, and redirects before selecting retained URL. |
| /cnc/mesin/* categories and LD model routes | Sixty machine pages have unclear current product status and overlapping category/model intent. | manual review | CUT-16 selection hub; verified category/product routes only | Confirm current availability, unique specs, evidence, support, canonical, and conversions. |
| /category/*, /author/*, /berita and pagination | Archives are navigation, not authority coverage. | noindex | Process/topic hubs and XML sitemap | Verify live canonical/robots and useful browse paths before change. |
| post-sitemap1.xml through post-sitemap13.xml | 2,416 entries include 163 duplicates; complete sitemap exposes only 119 URLs. | manual review | One generated canonical sitemap set | Reconcile deployed sitemap index, canonical URLs, query variants, and lastmod accuracy. |

## Coverage matrix

Every completeness-framework lens is mapped below. No lens was declared N/A.

| Group | Lens | Topic IDs | Gap test / editorial requirement |
| --- | --- | --- | --- |
| Core knowledge | Definition and vocabulary | CUT-01, CUT-05, CUT-06, CUT-07, CUT-08, CUT-09 | Own cutting, machining, routing, turning, boring, kerf, HAZ, feed/speed, nesting, and process distinctions without synonym pages. |
| Core knowledge | Taxonomy and variants | CUT-01, CUT-05, CUT-06, CUT-07, CUT-08, CUT-09, CUT-16 | Classify processes by mechanism, geometry, material, thickness, accuracy, edge condition, volume, and machine configuration. |
| Core knowledge | Anatomy and components | CUT-07, CUT-08, CUT-10, CUT-16 | Show machine axes, spindle/source, chuck/fixture, bed, guides, nozzle/tool, extraction, controls, sensors, and consumables. |
| Core knowledge | Materials and properties | CUT-02, CUT-05, CUT-06, CUT-07, CUT-08 | Relate hardness, toughness, reflectivity, conductivity, melting, fiber/grain, thickness, coating, and heat response to process choice. |
| Core knowledge | Mechanisms and science | CUT-05, CUT-06, CUT-07, CUT-08, CUT-09 | Explain beam/arc/jet/chip formation, heat input, tool engagement, springback, residual stress, and distortion. |
| Core knowledge | History and evolution | CUT-01, CUT-16 | Use only to explain manual-to-CNC changes, automation, controls, capability, and current procurement assumptions. |
| Core knowledge | Measurement and terminology | CUT-03, CUT-04, CUT-10, CUT-14 | Own coordinate/datum, units, tolerances, fits, roughness, kerf, bend terms, inspection uncertainty, and drawing conventions. |
| Lifecycle | Need recognition | CUT-01, CUT-02, CUT-11 | Identify geometry, material, quantity, deadline, quality, and downstream work; include when stock/manual fabrication is better. |
| Lifecycle | Survey and diagnosis | CUT-02, CUT-03, CUT-04, CUT-14 | Require material identity, drawing revision, datum, critical dimensions, flatness, surface, quantity, sample, and defect evidence. |
| Lifecycle | Requirements and design | CUT-03, CUT-04, CUT-11, CUT-15 | Translate function, assembly, tolerance stack, edge, finish, marking, batch, packaging, and traceability into requirements. |
| Lifecycle | Comparison and selection | CUT-02, CUT-05, CUT-06, CUT-07, CUT-08, CUT-09 | Compare processes only for the same geometry/material/quality/volume job and state trade-offs. |
| Lifecycle | Budget and procurement | CUT-11, CUT-13, CUT-15 | Break cost into material, programming/setup, cutting time, consumables, yield, secondary work, inspection, packing, logistics, and rework. |
| Lifecycle | Preparation | CUT-02, CUT-03, CUT-10, CUT-12 | Own material verification, file cleanup, tooling/fixture, nesting, machine condition, PPE, extraction, exclusion, and first-off plan. |
| Lifecycle | Installation/construction | CUT-05, CUT-06, CUT-07, CUT-08, CUT-09 | Describe controlled production stages and hold points, not unsafe machine-operation shortcuts. |
| Lifecycle | Commissioning/handover | CUT-04, CUT-13, CUT-14, CUT-15 | Own first article, measurement record, sample approval, batch identity, finish, quantity, packing, NCR, and certificate handover. |
| Lifecycle | Use/operation | CUT-10, CUT-12, CUT-16 | Cover setup discipline, parameter control, tool/consumable life, operator checks, alarms, and authorized operation. |
| Lifecycle | Inspection and maintenance | CUT-10, CUT-14, CUT-16 | Define calibration checks, wear indicators, cleaning/lubrication, extraction, alignment, logs, and preventive intervals. |
| Lifecycle | Troubleshooting and repair | CUT-04, CUT-05, CUT-06, CUT-07, CUT-08, CUT-09, CUT-14 | Own burr, taper, dross, HAZ, chatter, burn, delamination, drift, out-of-round, springback, and corrective isolation. |
| Lifecycle | Upgrade and replacement | CUT-11, CUT-16 | Decide repair, retrofit, automation, tooling/fixture improvement, outsourcing, machine replacement, resale, and decommissioning. |
| Decision context | User/stakeholder | CUT-03, CUT-11, CUT-13, CUT-14, CUT-16 | Create paths for designer, buyer, estimator, programmer, operator, machinist, welder, QC, maintenance, owner, and end assembler. |
| Decision context | Building/site type | CUT-02, CUT-11, CUT-15 | Interpret as fabrication contexts: construction, signage, furniture, automotive, workshop, industrial maintenance, and public projects. |
| Decision context | Geography and climate | CUT-02, CUT-10, CUT-12, CUT-15 | Address humid storage, corrosion, heat, unreliable supply, inter-island logistics, dust/fume control, and coastal service substantively. |
| Decision context | Scale and performance | CUT-04, CUT-05, CUT-07, CUT-08, CUT-11 | Connect envelope, thickness, batch size, cycle/setup, tolerance, repeatability, utilization, and throughput. |
| Decision context | New build versus retrofit | CUT-03, CUT-08, CUT-11, CUT-15 | Cover reverse engineering, worn references, scan/measure uncertainty, one-off repair, compatibility, and production redesign. |
| Decision context | DIY versus professional | CUT-05, CUT-06, CUT-07, CUT-08, CUT-09, CUT-12 | Give stop conditions for high energy, rotating equipment, pressure, fumes, heavy stock, guarding, and lifting. |
| Decision context | Quality level | CUT-04, CUT-11, CUT-13, CUT-14 | Separate fit-for-purpose economy, standard, precision, and critical work by capability evidence—not machine brand or price alone. |
| Risk/governance | Safety and health | CUT-05, CUT-06, CUT-07, CUT-08, CUT-09, CUT-12, CUT-16 | Control radiation, arc, fire, hot metal, sharp edge, rotating entanglement, ejection, pressure, noise, dust/fume, and lifting. |
| Risk/governance | Failure modes | CUT-04, CUT-10, CUT-14, CUT-16 | Map input/setup/tool/machine/process/inspection causes to defects, consequences, detection, and prevention. |
| Risk/governance | Standards and regulation | CUT-03, CUT-04, CUT-12, CUT-14 | Verify current drawing, tolerance, welding/fabrication, machine, electrical, exposure, and product requirements before exact clauses. |
| Risk/governance | Environmental impact | CUT-02, CUT-11, CUT-12, CUT-15 | Address yield/scrap, nesting, energy, gas, coolant, dust/fume, noise, consumables, recycling segregation, and transport. |
| Risk/governance | Evidence quality | CUT-03, CUT-04, CUT-13, CUT-14, CUT-16 | Demand drawings/revisions, material certs, capability data, samples, first-off reports, calibrated measurement, maintenance logs, and traceability. |
| Risk/governance | Myths and unsafe advice | CUT-01, CUT-04, CUT-11, CUT-12 | Correct myths that CNC guarantees accuracy, one process cuts everything, tighter is always better, and copied parameters are safe. |
| Editorial/search | Fundamentals | CUT-01, CUT-02, CUT-04 | Stable hubs own process, material, accuracy, and vocabulary. |
| Editorial/search | How-to | CUT-03, CUT-10, CUT-13, CUT-14 | Use prerequisites, revision control, templates, stop conditions, verification, and authorized-operator boundaries. |
| Editorial/search | Comparison | CUT-02, CUT-05, CUT-06, CUT-07, CUT-08, CUT-09, CUT-16 | Compare processes/machines only against one defined job and decision matrix. |
| Editorial/search | Diagnosis | CUT-04, CUT-05, CUT-06, CUT-07, CUT-08, CUT-09, CUT-14 | Give each defect family one owner and link causes to process prevention and acceptance. |
| Editorial/search | Calculation/tool | CUT-03, CUT-04, CUT-11, CUT-13 | Provide RFQ input, nesting/yield, tolerance stack, cost breakdown, and bid-normalization worksheets. |
| Editorial/search | Visual reference | CUT-03, CUT-04, CUT-05, CUT-10, CUT-14 | Prioritize drawing callouts, datum diagrams, edge/defect photos, fixture/tool wear, and measurement setups. |
| Editorial/search | Case study | CUT-11, CUT-14, CUT-15 | Publish only real material, revision, setup, evidence, defect/correction, yield, and outcome with permission. |
| Editorial/search | FAQ/glossary | CUT-01 | Keep short terminology questions in the process hub unless a distinct decision or diagnostic intent exists. |
| Editorial/search | Commercial support | CUT-11, CUT-13, CUT-15 | Separate neutral education from quote scope, capability proof, scheduling, QA, packaging, and handover. |
| Editorial/search | News/trends | CUT-16 | Cover durable automation, controls, safety, capability, or supply changes only when maintainable and material. |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
| --- | --- | --- | --- | --- | --- | --- |
| CUT-01 | proses cutting dan machining | Memilih keluarga proses yang layak berdasarkan part, bukan nama mesin. | Cutting versus machining/fabrication; laser/plasma/flame/waterjet concepts; saw/shear/punch; router/milling/turning; bending; manual versus CNC; 2D/2.5D/3D; batch/setup; terminology; limits; workflow. | Process map, decision tree, mechanism diagrams, expert review. | Material behavior CUT-02; process-specific depth CUT-05 to CUT-09; machine buying CUT-16. | 8 |
| CUT-02 | material dan machinability untuk proses cutting | Match material condition and geometry to a feasible cutting or machining route. | Steel/stainless/aluminium/copper; plastics/acrylic; wood/composites; stone; foam; glass adjacency; grade verification; sheet/plate/bar/tube; coating; warpage; grain; heat sensitivity; sample/cert; storage; substitutions. | Material-process matrix, certificates/data sheets, sample tests, sourced explanation. | Does not replace material engineering or define final parameters; individual process hubs CUT-05 to CUT-09 own capability. | 8 |
| CUT-03 | gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi | Send an unambiguous production package that reduces interpretation and rework. | 2D/3D formats; DXF/DWG/SVG/PDF/STEP concepts; units/scale; vectors; duplicates/open paths; fonts; splines; layers; datum; tolerances; bend lines; hole/thread notes; grain/finish; revision; IP; approval; archive. | File checklist, annotated drawing, revision template, CAM preview, expert review. | Does not teach full CAD software or machine-specific programming; tolerances CUT-04, nesting/cost CUT-11. | 8 |
| CUT-04 | toleransi, kerf, kualitas tepi, akurasi, dan acceptance | Specify only the accuracy and edge condition the part actually needs and can verify. | Accuracy/precision/repeatability; dimensional/geometric tolerances; fits; datum; kerf compensation; taper; HAZ/dross/burr; roughness; distortion; first-off; sampling; gauge; uncertainty; acceptance; NCR. | Tolerance examples, defect photo atlas, measurement diagrams, calibrated-inspection review. | Not a substitute for product-specific engineering; drawing ownership CUT-03, QC workflow CUT-14, process causes CUT-05 to CUT-09. | 8 |
| CUT-05 | laser cutting untuk sheet, plate, tube, dan material nonlogam | Decide whether laser cutting fits the material, geometry, quality, batch, and budget. | Fiber/CO2 concepts; metal/nonmetal scope; sheet/tube; thickness envelope; assist gas; piercing; small holes; reflective materials; coatings/film; edge/HAZ/dross; distortion; parameters as controlled evidence; safety; QA. | Capability matrix, cut samples, parameter-factor explanation, defect photos, specialist review. | No copied parameter table or DIY operation; alternatives CUT-06/07, machine selection CUT-16, quote route remains separate. | 8 |
| CUT-06 | plasma, oxy-fuel, dan waterjet cutting | Compare non-laser plate-cutting routes for thickness, material, edge, heat, and cost. | Plasma; oxy-fuel; waterjet concept; conductive/ferrous constraints; thick plate; piercing; bevel; taper; HAZ; dross; heat distortion; gas/abrasive/water; submerged cutting; fumes; secondary machining; safety. | Same-job comparison, edge photos, capability data, safety sources, expert review. | Laser CUT-05; router/milling CUT-07; no machine-operation recipe or claim that all processes are locally offered. | 8 |
| CUT-07 | CNC routing, milling, engraving, dan drilling | Choose a subtractive CNC route for profiled, pocketed, engraved, or drilled parts. | Router versus mill; 2D/2.5D/3D; spindle/tool; flute; chip load concept; pockets/contours/drill; wood/plastic/aluminium/composite/stone; workholding; zero/datum; toolpath; finish; chatter; delamination; dust/chips. | Toolpath diagrams, workholding visuals, sample parts, manufacturer/tool data, machinist review. | No universal feed/speed values or bypassed guarding; files CUT-03, tolerance CUT-04, machine ownership CUT-16. | 8 |
| CUT-08 | turning, bubut CNC, boring, dan korter | Specify and procure rotational-part machining or repair with correct references. | Lathe/CNC turning; facing; OD/ID; boring/korter; grooves; threads; tapers; chuck/collet/centers; runout/concentricity; stock allowance; fits; surface; shaft/bushing/cylinder repair; reverse engineering; safety; inspection. | Part diagrams, datum/runout setup, measurement plan, sample inspection, machinist review. | Milling/router CUT-07; generic tolerance CUT-04; does not authorize operating a lathe without training/guarding. | 8 |
| CUT-09 | bending, rolling, dan forming untuk sheet serta plate | Prepare bend-ready drawings and anticipate geometry, tooling, and tolerance limits. | Press brake; rolling; forming; air/bottoming concepts; radius; angle; bend allowance/deduction; K-factor concept; springback; grain; tooling; flange limits; holes near bend; sequence; tonnage inputs; markings; inspection; cracks. | Bend diagrams, sample coupon, calculation worksheet, tooling data, expert review. | No universal K-factor/tonnage answer; drawing package CUT-03, acceptance CUT-04/14, quote CUT-13. | 8 |
| CUT-10 | tooling, workholding, fixture, gas, coolant, dan consumable | Plan the supporting system that makes process output repeatable and safe. | Cutting tools/inserts; nozzles/electrodes/lenses; gases; abrasive; coolant/lubricant; chucks/clamps/vacuum/fixtures; spoilboard; tool preset; wear; contamination; storage; traceability; change intervals; disposal; substitutes. | Component diagrams, wear photos, manufacturer data, setup checklist, safety data. | Process owners CUT-05 to CUT-09 explain output; machine maintenance CUT-16; no brand endorsement. | 8 |
| CUT-11 | design for manufacture, nesting, yield, setup, dan biaya cutting | Reduce avoidable fabrication cost without silently weakening function or quality. | DFM review; geometry cleanup; standard stock; common lines caveat; part spacing; grain/finish; remnant; nesting/yield; setup/programming; batch/lot; takt versus lead time; secondary operations; scrap; revisions; make/buy; total landed cost. | Yield calculator, annotated redesign, cost-component model, real case only when documented. | No fabricated price list or guaranteed saving; process feasibility CUT-02/05-09, vendor comparison CUT-13. | 8 |
| CUT-12 | keselamatan mesin, fume, kebakaran, debu, bising, limbah, dan kendali lingkungan | Recognize stop conditions and evidence required for safe cutting/fabrication work. | Laser radiation; arc/UV; hot work/fire; oxygen/fuel gases; high pressure; rotating entanglement/ejection; sharp/hot stock; dust/fume; coolant; noise; electrical; guarding/interlock; LOTO concept; lifting; PPE hierarchy; extraction; waste; emergency. | Hazard-control matrix, SDS/primary guidance, facility diagram, qualified safety review. | Not operator certification, risk assessment sign-off, or a workaround for guards/interlocks; process pages only add context. | 8 |
| CUT-13 | RFQ, kapabilitas vendor, penawaran, jadwal, dan pengadaan cutting | Obtain comparable bids and qualified responses instead of vague price messages. | RFQ checklist; drawings/revision; material responsibility/cert; quantity/lot; process flexibility; critical features; sample/first article; capability proof; finish; inspection; schedule; transport; packaging; IP/NDA; substitutions; warranty/rework; exclusions. | RFQ template, bid-normalization sheet, capability audit questions, sample register. | Does not name a universally best vendor or publish undated prices; DFM/cost CUT-11 and acceptance CUT-14 remain owners. | 8 |
| CUT-14 | quality control, metrologi, traceability, dan diagnosis cacat cutting | Verify parts against requirements and isolate defects before assembly or shipment. | Inspection plan; critical-to-function; visual/dimensional; caliper/micrometer/height/CMM concepts; templates/gauges; calibration; first-off; sampling; MSA awareness; material/batch trace; edge defect atlas; NCR; 5-why limits; disposition; report. | Inspection form, measurement setup diagrams, defect photos, calibration evidence, QC review. | Does not redefine drawing requirements after production; requirements CUT-03/04, process correction CUT-05-10. | 8 |
| CUT-15 | deburring, finishing, joining, marking, packing, dan logistik setelah cutting | Protect part function and traceability through downstream work and delivery. | Deburr/grind/tumble; cleaning; passivation/coating/paint prep concepts; heat/warp; weld prep; tapping/countersink; assembly fit; marking/serialization; protective film; rust prevention; stacking; sharp-edge protection; crates; inter-island transport; receipt inspection. | Process route card, packaging diagrams, finish samples, delivery checklist, expert review. | Welding/coating specialist design can live on related domains; this topic owns only interfaces and post-cut flow on cutting.co.id. | 8 |
| CUT-16 | pemilihan mesin CNC, sistem operasi, perawatan, dan keputusan upgrade | Evaluate machine capability and ownership evidence without relying on model-page claims. | Make/buy; envelope; power/source/spindle; axes/ATC/feeding; bed/drive/control; accuracy versus repeatability; duty/utilization; utilities; extraction/cooling; software; training; service/spares; acceptance test; preventive/predictive logs; retrofit; resale; decommission. | URS template, capability/acceptance test, TCO model, maintenance record, independent expert review. | No endorsement of legacy LD model routes or claim of availability; process choice CUT-01/05-09 and consumables CUT-10. | 8 |

## Related-domain opportunities

- `pabrikasi.id` may publish a broader design-to-manufacture and assembly viewpoint while cutting.co.id independently covers the same cutting and DFM queries.
- `bengkel-las.co.id`, `besi.co.id`, `steel.id`, and `furnitur.co.id` can cover welding, material, or product-specific decisions; overlap is allowed across domains.
- `kaca.co.id` may cover glass cutting from a glass-system viewpoint; cutting.co.id can independently cover process selection and vendor-file preparation.
- Cross-domain links should be editorially useful, not boilerplate, and never be used as a substitute for same-domain boundaries.

These are collaboration and alternative-POV opportunities only. They do not reserve keywords away from cutting.co.id, do not require cross-domain canonicals, and are not included in same-domain cannibalization checks.

## Consolidation plan

1. Export indexation, impressions, backlinks, conversions, and current canonical status before changing any legacy URL.
2. Match each useful legacy page to the intent owner in the catalog. Preserve a historically useful URL when its intent can be expanded without confusing the owner page.
3. Merge only when the one-query and outline tests show the pages satisfy the same job. Redirect only after destination parity, link updates, and rollback records exist.
4. Noindex archives, search-like pages, or mass templates only after confirming they have no unique user value and after checking live robots/canonical behavior.
5. Build and measure Wave 1 before bulk migration. The map is a completeness plan, not authority to publish or remove hundreds of URLs at once.

## Internal-link architecture

- Each topic ID is a hub. Every child links upward to that hub; every hub links to all eight children.
- Within a topic, the sequence is fundamentals → selection → specification → detail → execution → diagnosis → maintenance → procurement.
- Selection pages link to the relevant fundamentals and specification assets; specification pages link to detail and QC assets.
- Diagnostic pages link to the installation checkpoint that prevents the defect, the maintenance page that detects it, and the procurement page when replacement is justified.
- Commercial routes receive links only from a relevant selection, specification, execution, or procurement context; they do not own neutral informational intent.
- Cross-topic links follow real dependencies documented in each hub. A fixed sitewide “related articles” list is prohibited.

## Evidence and editorial standards

- Verify exact SNI, ISO, ASTM, EN, ASME, AWS, IEC, manufacturer, or regulatory references against current primary text before publication; this plan intentionally does not invent clause numbers.
- Safety-critical sizing, load, guarding, fire, pressure, electrical, machine, and structural claims require a competent professional review and stated assumptions.
- Prices, lead times, capacities, tolerances, and warranties must be dated and sourced; use component breakdowns instead of timeless price claims.
- Never fabricate tests, projects, case studies, measurements, photographs, or firsthand experience. Label worked examples as examples.
- Indonesian conditions must be substantive: humidity, rainfall, heat, coastal corrosion, supply chain, workmanship, transport, and occupied-building constraints where relevant.
- Every published page gets a source log, author/reviewer, last-reviewed date, change trigger, unique title/slug, and a post-publication cannibalization check.

## First bounded publication cluster

Wave 1 contains 14 connected assets:

- `CUT-01-01` — Panduan dasar proses cutting dan machining: istilah, komponen, dan cara kerja
- `CUT-02-02` — Cara memilih material dan machinability untuk proses cutting: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-03-02` — Cara memilih gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-03-03` — Spesifikasi gambar kerja, file CAD/CAM, kontrol revisi, dan data produksi: data, ukuran, toleransi, dan pemeriksaan asumsi
- `CUT-04-02` — Cara memilih toleransi, kerf, kualitas tepi, akurasi, dan acceptance: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-04-03` — Spesifikasi toleransi, kerf, kualitas tepi, akurasi, dan acceptance: data, ukuran, toleransi, dan pemeriksaan asumsi
- `CUT-04-06` — Masalah pada toleransi, kerf, kualitas tepi, akurasi, dan acceptance: gejala, akar penyebab, dan keputusan perbaikan
- `CUT-05-01` — Panduan dasar laser cutting untuk sheet, plate, tube, dan material nonlogam: istilah, komponen, dan cara kerja
- `CUT-05-02` — Cara memilih laser cutting untuk sheet, plate, tube, dan material nonlogam: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-05-05` — Tahapan produksi laser cutting untuk sheet, plate, tube, dan material nonlogam: persiapan, first-off, QC, dan serah terima
- `CUT-11-02` — Cara memilih design for manufacture, nesting, yield, setup, dan biaya cutting: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-11-03` — Spesifikasi design for manufacture, nesting, yield, setup, dan biaya cutting: data, ukuran, toleransi, dan pemeriksaan asumsi
- `CUT-13-02` — Cara memilih RFQ, kapabilitas vendor, penawaran, jadwal, dan pengadaan cutting: matriks keputusan berdasarkan fungsi dan risiko
- `CUT-14-05` — Tahapan produksi quality control, metrologi, traceability, dan diagnosis cacat cutting: persiapan, first-off, QC, dan serah terima

The cluster follows one quote-to-quality journey for fabricated parts: process/material choice, revision-controlled files, datum/tolerance decisions, laser capability, nesting/cost, RFQ normalization, first-off inspection, and defect diagnosis. It can improve qualified enquiries before expanding into every machine and process.

Success signals: crawlability and indexation; impressions and clicks separated by the intended query/job; scroll or tool completion; assisted visits to legitimate commercial routes; qualified enquiries with the requested technical inputs; response, conversion, and collected-income evidence where applicable; and Search Console checks for two pages swapping on the same query. Ranking alone is insufficient.

## Definition of done

- All 16 parent topics remain represented by eight distinct briefs, totaling 128 planned assets.
- Every brief has one intent, reader, promise, named exclusion owner, evidence format, links, priority, and bounded wave.
- Proposed titles, IDs, and slugs are unique and do not collide with audited repository sitemap paths.
- All related IDs resolve, no topic is orphaned, and the same-domain overlap register is reviewed before commissioning.
- Legacy consolidation decisions are made from live indexation, traffic, links, conversions, and content review—not from slug preference alone.
- Wave 1 is published with review evidence, internal links, measurement, and a stop/continue decision before later waves.
