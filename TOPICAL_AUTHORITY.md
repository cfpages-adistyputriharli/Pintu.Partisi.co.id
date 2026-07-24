# Topical Authority — pintu.partisi.co.id

## Role and boundary

`pintu.partisi.co.id` is an Indonesian knowledge and commercial-support property for operable/folding/sliding partition doors used to divide rooms. The evidenced offer includes standard, semi-sound-reducing, full-sound-reducing, and custom products plus installation for classrooms, offices, meeting rooms, halls, ballrooms, studios, and multipurpose spaces.

Educational pages help owners, architects, facility teams, buyers, and installers define needs, compare systems, coordinate structure/ceiling/floor interfaces, verify claims, operate panels, and plan maintenance. They do not replace structural design, tested acoustic/fire assemblies, accessibility/code review, lifting, electrical work, manufacturer instructions, or competent installation. Existing product and `/kontak-kami/` routes own conversion. No city-swapped article is planned.

## Evidence audited

- Canonical repo `cfpages-adistyputriharli/Pintu.Partisi.co.id`, branch `main`; 351 tracked files and 125 HTML files.
- `README.md` and `sitemap-complete.xml`: 125 URLs; `post-sitemap.xml`: 103 URLs; `video-sitemap.xml`: 224 `<loc>` entries.
- 102 root `jual-pasang-partisi-{place}.html` pages are geographic sales variants.
- Meaningful routes: `/produk/`, `/standart/`, `/semi-peredam/`, `/full-peredam/`, `/custom/`, `/pasang/`, ten `/pasang/{use-case}/` pages, `/tentang-kami/`, and `/kontak-kami/`.
- Archive routes: `/berita/` and `/category/pintu-lipat/`.
- Two HTML indexes exist under WordPress upload/cache paths, including a file-manager backup path; exposure and deployment behavior require security review.
- Existing titles use unsupported `#1` language and several pages market “peredam suara”; repository copy alone does not prove rankings, acoustic performance, tested assemblies, or complete-system ratings.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/`, `/produk/` | Commercial overview/catalog | keep | Commercial navigation | Verify claims, current contacts, product evidence, and canonical metadata |
| `/standart/`, `/semi-peredam/`, `/full-peredam/`, `/custom/` | Product tiers with ambiguous performance labels | expand | Commercial product routes; PDP-01/PDP-07 own neutral taxonomy/performance education | Require construction details, hardware, dimensions, test reports, limitations, and consistent terminology |
| `/pasang/` | Installation service page | keep | Commercial installation route; PDP-11 owns educational workflow | Add verified scope, prerequisites, QA, exclusions, and handover evidence |
| `/pasang/{aula-sekolah,ballroom,direksi,diskotik,gedung-serbaguna,hall,kantor,ruang-kelas,ruang-meeting,studio-musik}/` | Use-case sales pages with overlapping room intent | manual review | PDP-04 owns selection logic; retain commercial pages only where requirements/cases differ | Compare outlines, GSC, leads, photos, and real application evidence |
| `/jual-pasang-partisi-{place}.html` | 102 location-swapped pages | manual review | Product/install hubs unless unique local proof exists | Audit GSC, backlinks, leads, canonicals, delivery/installation evidence, and similarity |
| `/berita/`, `/category/pintu-lipat/` | Thin archives | noindex | Topic hubs and useful articles | Verify internal-link dependency |
| `wp-content/uploads/**/index.html` | Upload/cache and file-manager-backup indexes | remove | None | Verify live exposure, secrets/backups, response codes, and purge/deploy behavior |

Risks: doorway geography, ambiguous “standard/semi/full” labels, unsupported `#1`, acoustic/fire claims inferred from one component, overlapping use-case pages, unsafe overhead-track advice, missing accessibility/egress checks, and exposed upload/cache artifacts.

## Coverage matrix

| Completeness lens | Topic owner(s) | Coverage decision |
|---|---|---|
| Vocabulary, taxonomy, history, variants | PDP-01 | Distinguish folding, sliding, operable wall, movable wall, accordion, and product tiers |
| Anatomy, materials, finishes | PDP-02 | Panels, frames, seals, joints, faces, edges, and finish interfaces |
| Tracks, carriers, hardware, mechanisms | PDP-03 | Top-hung/floor-supported concepts, rollers, hinges, locks, stacking, and controls |
| Users, room types, selection, scale | PDP-04 | Requirements by use rather than separate thin room articles |
| Survey, design, structure/ceiling/floor/MEP interfaces | PDP-05 | Own prerequisites and coordination |
| Accessibility, usability, safety, egress | PDP-06 | High-stakes review and stop conditions |
| Acoustic performance and evidence | PDP-07 | Separate lab rating, field result, flanking, seals, and privacy expectation |
| Fire/smoke claims and evidence | PDP-08 | Complete tested assembly and code review; no inferred rating |
| Budget, procurement, supplier evaluation | PDP-09 | Transparent scope and claim verification |
| Customization, fabrication, QA | PDP-10 | From approved submittal to released panels/hardware |
| Installation, commissioning, handover | PDP-11 | Sequence, tolerances, tests, records |
| Operation, cleaning, maintenance, troubleshooting | PDP-12 | User-facing lifecycle and safe stop conditions |
| Repair, retrofit, upgrade, replacement, end-of-life | PDP-13 | Decision pathway and reuse/waste |
| Roles, documents, warranty, evidence governance | PDP-14 | Accountability across the project lifecycle |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| PDP-01 | Partition-door taxonomy and terminology | Name systems correctly and compare like with like | folding/sliding/accordion/operable wall; movable versus fixed; manual/automatic; top-hung/floor-supported; standard/semi/full/custom; evolution | glossary; system diagrams; decision tree | Product sales stay on existing routes; performance belongs to PDP-07/PDP-08 | 6 |
| PDP-02 | Panels, frames, seals, materials, and finishes | Understand system anatomy and finish trade-offs | panel core/skin/frame; joints; top/bottom/vertical seals; edges; glazing/doors; moisture/impact; finish repair | exploded diagrams; material matrix; samples | Hardware belongs to PDP-03; acoustic/fire claims to PDP-07/PDP-08 | 6 |
| PDP-03 | Tracks, carriers, hardware, and movement | Specify operational hardware inputs and recognize hazards | tracks; rollers/trolleys; pivots/hinges; guides; locks; stacking; pass doors; manual/automatic controls; wear | mechanism diagrams; hardware schedule; inspection checklist | Structural support belongs to PDP-05; operation to PDP-12 | 6 |
| PDP-04 | Requirements and system selection by use | Select a concept from room/user/operation needs | frequency; opening size; stacking; staff/users; classrooms/offices/halls/ballrooms/studios; privacy; acoustics; aesthetics; cleaning | requirement matrix; room scenarios | Does not promise performance or replace PDP-05 survey | 6 |
| PDP-05 | Survey, design, and interface coordination | Prepare buildable inputs for structure, ceiling, floor, walls, and services | dimensions; tolerances; overhead support; deflection; floor level; pockets; MEP/sprinklers; finishes; retrofit/occupied work | survey checklist; sections; interface matrix | No structural design or installation procedure; PDP-11 owns field work | 6 |
| PDP-06 | Accessibility, usability, safety, and egress | Identify user/egress hazards and required specialist review | clear opening; forces/reach; thresholds; pinch/crush; stability; emergency route; pass doors; signage; automatic controls; children/public use | hazard map; user journey; qualified review | No universal dimensions/compliance certification | 6 |
| PDP-07 | Acoustic performance and privacy | Evaluate sound-reduction claims and diagnose weak paths | airborne sound; lab versus field; rating terminology; seals/joints; flanking; background noise; speech privacy; measurement; commissioning | acoustic diagrams; test-report anatomy; field-test plan | No guaranteed dB/privacy without tested assembly and site evidence | 6 |
| PDP-08 | Fire and smoke performance | Verify whether a complete partition-door assembly has relevant evidence | rated assembly; panels/track/seals/hardware/pass door; supporting construction; labels; penetrations; inspection; modifications; smoke versus fire | evidence checklist; assembly diagram; fire-specialist review | No rating inferred from material; code/project approval remains professional | 6 |
| PDP-09 | Cost, procurement, and supplier evaluation | Compare offers on equal verified scope | quantity/opening; product tier; hardware; finishes; support/MEP work; transport; installation; testing; warranty; exclusions; vendor evidence | bid matrix; scope template; cost tree | No universal prices or named-vendor endorsements | 6 |
| PDP-10 | Customization, fabrication, and QA | Verify custom panels/hardware against approved submittals | dimensions; module layout; finish samples; cutouts; pass doors; marks; tolerances; assembly trial; protection; traceability; NCR | submittal matrix; ITP; photo records | No fabrication procedures that override manufacturer/engineer | 6 |
| PDP-11 | Installation, commissioning, and handover | Understand the controlled field sequence and acceptance evidence | readiness; survey/set-out; supports/track; panels/hardware; alignment; seals; operation; safety; acoustic/fire interfaces; punch list; training | sequence diagram; ITP; handover checklist | No DIY overhead installation, lifting, structural, or electrical authorization | 6 |
| PDP-12 | Operation, cleaning, maintenance, and troubleshooting | Operate panels safely and isolate common symptoms | opening/closing/stacking; locks/seals; cleaning; lubrication limits; inspection; dragging/jamming/noise/gaps; automatic faults; records | SOP; symptom-action table; maintenance log | No repair while suspended/energized; PDP-13 owns repair decisions | 6 |
| PDP-13 | Repair, retrofit, upgrade, replacement, and end-of-life | Decide whether to adjust, repair, upgrade, replace, reuse, or recycle | cause/extent; parts availability; track/support; panel/finish; seals; acoustics/fire; automation; occupied retrofit; deconstruction/waste | decision tree; survey checklist; lifecycle matrix | No structural/fire repair approval from generic guidance | 6 |
| PDP-14 | Project roles, documents, warranty, and evidence | Maintain accountable decisions and usable records | brief; design responsibility; submittals; RFI/change; ITP/NCR; test reports; acceptance; as-built; O&M; training; warranty; baseline | RACI; evidence register; document index | Contracts/legal advice and technical approvals remain with qualified parties | 6 |

## Related-domain opportunities

`partisi.co.id` may cover broad fixed/movable partition systems; `cubicle.co.id`, `kubikel.co.id`, `phenolic.id`, and toilet-cubicle domains can cover wet-area cubicles. `pintu.partisi.co.id` retains the operable partition-door viewpoint. Cross-domain overlap is allowed; links must not imply shared ratings, inventory, or certification without evidence.

## Consolidation plan

1. Export GSC, backlinks, analytics, leads, canonicals, and live response evidence before changing 102 geographic URLs.
2. Freeze new city swaps; consolidate unsupported variants toward product/install hubs.
3. Reconcile ten use-case pages by unique requirements and real case evidence; merge overlapping hall/ballroom/aula intents when outlines and demand match.
4. Remove upload/cache index artifacts, security-review the file-manager backup path, and purge them from deployment.
5. Noindex thin archives and publish one clean sitemap of canonical hubs/articles.
6. Replace unsupported `#1`, “semi/full peredam,” acoustic, fire, warranty, and performance claims with precise tested-system evidence or qualified wording.

## Internal-link architecture

Central path: PDP-01 → PDP-04 → PDP-05 → PDP-06/PDP-07/PDP-08 → PDP-09 → PDP-10 → PDP-11 → PDP-12 → PDP-13. PDP-14 supports every gate. Each topic hub links to six children; comparisons link to entity guides; diagnostic pages link to operation, repair, and stop conditions. Product/service links appear only after educational intent is satisfied.

## Evidence and editorial standards

Use current primary standards, manufacturer documents, complete assembly test reports, original drawings/photos, and competent review. Never invent dimensions, loads, acoustic/fire ratings, prices, accessibility compliance, or case results. Explain lab versus field evidence and component versus assembly evidence. Structural supports, suspended work, automatic/electrical systems, fire/smoke, egress, and accessibility require qualified project review. Every article records owner, reviewer, evidence date, update trigger, and claim limitations.

## First bounded publication cluster

Publish 12 Wave-1 assets: PDP-01-01, PDP-02-01, PDP-03-01, PDP-04-01, PDP-05-01, PDP-06-01, PDP-07-01, PDP-07-02, PDP-08-01, PDP-09-01, PDP-11-01, and PDP-12-01. They form one decision-to-operation path. Monitor valid indexation, impressions by intent, checklist use, engaged product transitions, qualified/answered leads, conversion/commission, collected revenue, and cannibalization.

## Definition of done

All 14 topics have six distinct briefs; titles/slugs/intents/boundaries/IDs are unique and valid; no planned slug collides with current routes; geographic/use-case consolidation is evidence-based; security artifacts are removed; performance claims are verified; Wave 1 is reviewed, connected, measured, and maintained before expansion.
