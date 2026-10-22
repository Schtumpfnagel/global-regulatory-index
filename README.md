---
license: other
language:
  - en
pretty_name: Global Regulatory & Statutory Open Metadata Index (2024–2026)
size_categories:
  - 10K<n<100K
task_categories:
  - text-classification
  - question-answering
  - feature-extraction
tags:
  - legal
  - regulation
  - legislation
  - compliance
  - statutory-instruments
  - federal-register
  - eur-lex
  - united-nations
configs:
  - config_name: default
    data_files:
      - split: train
        path: regulatory_index_2026.jsonl
---

# Global Regulatory & Statutory Open Metadata Index (2024–2026)

**Primary Institutional Terminal:** [Global Data Index (https://www.globaldataindex.org)](https://www.globaldataindex.org)  
**Complete Authority Directory & Methodology:** [https://www.globaldataindex.org/methodology/](https://www.globaldataindex.org/methodology/)  
**Statutory Licensing Schedule:** [https://www.globaldataindex.org/terms-of-service/](https://www.globaldataindex.org/terms-of-service/)  
**Last Automated Sync:** `2026-10-22 20:34 UTC`  
**Total Indexed Public Records in Catalog:** `15,939` across `223` issuing authorities

---

## Overview

This repository provides an automated, machine-readable metadata index (`CSV` and `JSONL`) of official government regulations, statutory instruments, legislation, and multilateral resolutions indexed by **[Global Data Index](https://www.globaldataindex.org)**.

Full analytical briefings, structured HTML compliance matrices, two-stage Tables of Contents, authority RSS syndication feeds, and unabridged source PDF dossiers are available directly via each record's `canonical_url` on [globaldataindex.org](https://www.globaldataindex.org).

## Live Jurisdiction Breakdown & Canonical Archive Hubs

| Jurisdiction | Indexed Dossiers | Issuing Authorities | Governing Open-Government Framework | Canonical Archive Hub |
| :--- | :--- | :--- | :--- | :--- |
| **[United States](https://www.globaldataindex.org/united-states/)** | `8,041` | `176` | *17 U.S.C. § 105 Public Domain* | [https://www.globaldataindex.org/united-states/](https://www.globaldataindex.org/united-states/) |
| **[United Kingdom](https://www.globaldataindex.org/united-kingdom/)** | `1,602` | `13` | *Open Government Licence v3.0 (OGL v3.0)* | [https://www.globaldataindex.org/united-kingdom/](https://www.globaldataindex.org/united-kingdom/) |
| **[Canada](https://www.globaldataindex.org/canada/)** | `4,368` | `15` | *Reproduction of Federal Law Order (SI/97-5)* | [https://www.globaldataindex.org/canada/](https://www.globaldataindex.org/canada/) |
| **[European Union](https://www.globaldataindex.org/european-union/)** | `1,281` | `4` | *European Commission Reuse Decision (2011/833/EU)* | [https://www.globaldataindex.org/european-union/](https://www.globaldataindex.org/european-union/) |
| **[Australia](https://www.globaldataindex.org/australia/)** | `316` | `11` | *Creative Commons Attribution 4.0 (CC BY 4.0)* | [https://www.globaldataindex.org/australia/](https://www.globaldataindex.org/australia/) |
| **[United Nations](https://www.globaldataindex.org/united-nations/)** | `331` | `4` | *UN Administrative Instruction ST/AI/189/Add.9/Rev.2* | [https://www.globaldataindex.org/united-nations/](https://www.globaldataindex.org/united-nations/) |

*To browse all `223` individual government department, ministry, agency, and multilateral organ archives, visit the **[Indexed Jurisdictions & Issuing Authorities Directory](https://www.globaldataindex.org/methodology/)**.*

## Dataset Files & Schema

* `regulatory_index_2026.csv` — UTF-8 comma-separated index of all published regulatory dossiers.
* `regulatory_index_2026.jsonl` — Newline-delimited JSON records for programmatic ingestion and LLM/RAG citation pipelines.

| Field | Type | Description |
| :--- | :--- | :--- |
| `document_id` | `string` | Official statutory or registry identifier (e.g., `2026-06947`, `UKSI-2026-142`, `CELEX-32026R0815`, `F2026L01394`, `UN-S-RES-2728-2024`) |
| `jurisdiction` | `string` | Issuing sovereign jurisdiction or multilateral body |
| `authority` | `string` | Issuing government department, ministry, agency, or organ |
| `publication_date` | `string` | Official publication or enactment date (`YYYY-MM-DD`) |
| `page_count` | `integer` | Verified pagination of the unabridged source PDF dossier |
| `language` | `string` | Primary document language (`English`) |
| `title` | `string` | Official statutory or regulatory title |
| `canonical_url` | `string` | Direct permalink to the executive briefing and PDF dossier on [globaldataindex.org](https://www.globaldataindex.org) |

---

*Maintained autonomously by [Global Data Index](https://www.globaldataindex.org).*
