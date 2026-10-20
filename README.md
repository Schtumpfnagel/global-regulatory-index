---
license: other
language:
  - en
pretty_name: Global Regulatory & Statutory Open Metadata Index (2024–2026)
size_categories:
  - 1K<n<10K
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
**Last Automated Sync:** `2026-10-20 14:38 UTC`  
**Total Indexed Public Records in Catalog:** `12,105`

---

## Overview

This repository provides an automated, machine-readable metadata index (`CSV` and `JSONL`) of official government regulations, statutory instruments, legislation, and multilateral resolutions indexed by **[Global Data Index](https://www.globaldataindex.org)**.

Full analytical briefings, structured compliance matrices, and unabridged source PDF dossiers are available directly via each record's `canonical_url` on [globaldataindex.org](https://www.globaldataindex.org).

## Covered Jurisdictions & Statutory Frameworks

1. **[United States](https://www.globaldataindex.org/?gdi_country=United+States)** — Federal Register Rules & Proposed Rules (*17 U.S.C. § 105 Public Domain*)
2. **[United Kingdom](https://www.globaldataindex.org/?gdi_country=United+Kingdom)** — UK Statutory Instruments (`UKSI`) & Public General Acts (`UKPGA`) (*Open Government Licence v3.0*)
3. **[Canada](https://www.globaldataindex.org/?gdi_country=Canada)** — Statutory Orders and Regulations (`SOR`, `SI`, `CRC`) & Consolidated Acts (*Reproduction of Federal Law Order SI/97-5*)
4. **[European Union](https://www.globaldataindex.org/?gdi_country=European+Union)** — EU Regulations, Directives & Decisions (`CELEX`) (*Commission Decision 2011/833/EU*)
5. **[Commonwealth of Australia](https://www.globaldataindex.org/?gdi_country=Australia)** — Federal Register of Legislation Acts & Instruments (*Creative Commons Attribution 4.0 International / CC BY 4.0*)
6. **[United Nations](https://www.globaldataindex.org/?gdi_country=United+Nations)** — UN Security Council (`S/RES/`), General Assembly (`A/RES/`) & Official Records (*UN Administrative Instruction ST/AI/189/Add.9/Rev.2*)

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
