# DOC-2-095 F0 metadata feasibility protocol

Locked F0 protocol upon publication of lock-1 commit/tag; no admission fetch permitted before server timestamp verification. Source position195: The Biological Meaning of Satellite Green.

Question: Can satellite vegetation indices be decomposed into ecological versus physiological components using public molecular/phenotype ground truth? Source validation: independent regions/seasons and ground-truth datasets. This F0 only checks admissible documentation, not predictive effectiveness, biological interpretation, or success. Zero project-success credit.

Expected: no single source or documented join meets G1-G6; the likely F0 result is STOP or UNRESOLVED for the full topic. This expectation is fixed before admission fetching and is not an observed audit outcome.

## Boundaries

No numerical satellite reflectance/VI, flux, fluorescence, phenotype or expression data downloaded or scored. No images/figures, effect-size tables or full results sections intentionally opened. No links followed from fixed routes, including file previews, manifests or later versions. Descriptive record fields, dataset-level counts, acquisition design, stated geographic/time scope, access/terms and available join identifiers are allowed; all opened fields/counts and accidental published-result exposure disclosed. A sample-level metadata manifest would require an amendment with explicit fields before opening.

Discovery is prior exposure, not registered audit evidence. Search highlights contained published molecular association claims (including vineyard 968 differentially expressed genes); no threshold or candidate ranking will use them. The OmicsDI abstract fetch was pre-lock exposure and contains this result; documented, not hidden. D published findings cannot choose, rank, tune or interpret anything; its gate verdict is documentation-only. No expression values, differential-expression results, paper figures or effect sizes are used to choose candidates or decide gates.

## Fixed candidate routes

A GROUNDED EO, exact version label v1, record14293472, published May12 2025: https://zenodo.org/records/14293472
B FluxnetEO Landsat, exact version2, DOI10.18160/2413-93GQ, publication2023: https://meta.icos-cp.eu/collections/zuQuNbNKrRPDD2_i-KiPXV0-
C Midwestern ground SIF/VI, exact Version1, DOI10.3334/ORNLDAAC/2136, publication2023-03-17: https://www.earthdata.nasa.gov/data/catalog/ornl-cloud-crops-sif-vegindices-il-ne-2136-1
D vineyard molecular study, GEO accession GSE254304. Fixed primary: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE254304 (actual href observed in discovery HTML, not guessed). Fixed fallback if primary fails admission: https://www.omicsdi.org/dataset/geo/GSE254304 (aggregator mirror, provider record dated2024/02/27). Neither route exposes a guaranteed numbered record version; exact accession pinned, version-history UNKNOWN.
E LIFT durum wheat, exact Version1.0.0, record4305673, publication2021-06-14: https://zenodo.org/records/4305673

A covers structural ground-reference/Sentinel matchup documentation. B covers satellite VI/tower geometry documentation. C covers physiological proxy/field spectroscopy documentation, NOT satellite evidence alone. D covers molecular/phenotype/spatial-design documentation, NOT necessarily satellite. E covers physiological measurements/two-season design, NOT satellite or independent regions alone. Cross-source joining is permitted only if documentary shared site/geolocation, date, footprint, organism/tissue and temporal support demonstrate it; no union of counts as proof of joins. A/B/C cannot silently be merged into a single study.

D routes registered in that order: GEO series page only, then OmicsDI if GEO fails admission. No GSM sample pages, supplementary files, SRA links or linked paper opened. Sample titles/counts and descriptive sample fields visible on the series page are disclosed exposure, not inspected manifests. The page summary may repeat the published 968-DEG claim; exposure ledger will state whether displayed. If both fail, D is UNADMITTED, no substitutions. When used, OmicsDI is labelled mirror and D terms/sample design UNKNOWN unless mirror documents them; G5/G6 conclusions based only on absent mirror fields capped at UNRESOLVED.

An admissible design is either one source or a join the records themselves document through shared site IDs/geolocation, dates, footprints and organism/tissue; no other join is evaluated. No inferred overlap or count union creates a design.

## Admission

One HTTP fetch per route, one same-route retry on failure. Preserve requested/final URL, UTC, response status, bytes and SHA256, title, expected identifier markers, admission and failure reasons. Reject challenge/login/error shells. Same exact-version browser fallback allowed on failed routes, with saved title/text/links and UTC/bytes/hash; links are captured only, not followed. No new sources/version substitution within F0. Newer-version prompts recorded, not accepted. Identifier or exact expected version-marker mismatch is not admitted; D has no claimed numbered version and this lack stays UNKNOWN. D primary and fallback each get the same bounded attempt/retry policy, in registered order.

Chronology: publish the protocol commit and lock-1 tag and verify GitHub server timestamp before the first admission fetch. Record first-fetch UTC. Discovery fetches are labelled pre-lock exposure, not audit evidence.

## Gates (all required for full-topic metadata GO)

G1 Satellite: actual satellite VI or surface-reflectance product, resolution, acquisition date and pixel/footprint support documented. Leaf/ground cart reflectance does not satisfy G1.
G2 Ecological/structural component: independently measured canopy structure/cover or composition (LAI/FCOVER/crop type etc.), spatial/temporal match documented. Satellite-retrieved structural estimates from the same reflectance are not independent ground truth.
G3 Physiological component: independent ground measurements or molecular targets with stated meaning and limitations. SIF is not a unique physiology measurement absent canopy/illumination controls; GPP is ecosystem productivity, not gene-program ground truth. Residual VI is not proof of physiology.
G4 Join: documentary shared site/date and footprint scale, including satellite overpass time-of-day versus ground measurement hour for satellite, structural and physiological targets. An alignment tolerance must be justified by measurement frequency and process timescale in a later outcome protocol; no generic monthly matching default. Spatial/date count unions are inadmissible.
G5 External validation: GO requires >=3 independent regions and >=3 distinct growing seasons within one documented design (or documented common-protocol set), with >=2 independent biological/field units per region-season cell. A 2x2 design is only UNRESOLVED/scoped, not GO. Independent regions are documented geographically distinct landscape areas, not zones within one vineyard or plots within one farm; region boundaries and site assignment must be documented, not inferred from country counts. A season means documented separate planting/growing cycle, not arbitrary calendar windows or time points within one planting. A perennial seasonal cycle requires explicit documentation of separate annual growing cycles. Enough documented region-season support must exist to hold both region and season out. Exact independent unit counts remain UNKNOWN unless documented.
G6 Identifiability/confounding/terms: documentation permits a design controlling illumination, canopy structure, phenology, species/crop composition and processing provenance; satellite-derived GPP/LAI trained on the same signals cannot be treated as independent physiological/structural truth. Data access and reuse terms established for each proposed component. Licence UNKNOWN stays UNKNOWN; raw redistribution is not inferred from article or code licence.

GO only if every gate has source-documentary support for an admissible joined design. UNKNOWN -> METADATA-UNRESOLVED; affirmative design incompatibility on required gate -> METADATA-STOP for that fixed candidate/design. Across-candidate full-topic STOP only if every admissible design has an affirmative incompatible required gate, otherwise UNRESOLVED. Narrow leads explicitly labelled partial and require a separately registered question. Annotation or accession availability is not biological evidence. No scientific success regardless of metadata verdict.

## Reporting

Dataset-level counts reported with what they count; file/plate/library/pixel counts are not independent sample/site counts. Per-source opened fields/counts, admitted routes/failures, exposure ledger, gate matrix distinguishing FAIL from UNKNOWN, raw-record hashes and current URLs. STOP applies only to this fixed set, not all public data. Public repo and Drive evidence; independent gate before closeout. A distinct locked numerical protocol needed before any value access/scoring.
