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

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23612006.svg)](https://doi.org/10.5281/zenodo.23612006)

**Primary Institutional Terminal:** [Global Data Index (https://www.globaldataindex.org)](https://www.globaldataindex.org)  
**Permanent Archival DOI (CERN / Zenodo):** [https://doi.org/10.5281/zenodo.23612006](https://doi.org/10.5281/zenodo.23612006)  
**Complete Authority Directory & Methodology:** [https://www.globaldataindex.org/methodology/](https://www.globaldataindex.org/methodology/)  
**AI / LLM Manifest (`llms.txt`):** [https://www.globaldataindex.org/llms.txt](https://www.globaldataindex.org/llms.txt)  
**Statutory Licensing Schedule:** [https://www.globaldataindex.org/terms-of-service/](https://www.globaldataindex.org/terms-of-service/)  
**Last Automated Sync:** `2026-10-25 10:14 UTC`  
**Total Indexed Public Records in Catalog:** `22,428` across `295` issuing authorities

---

## Overview

This repository provides an automated, machine-readable metadata index (`CSV` and `JSONL`) of official government regulations, statutory instruments, legislation, and multilateral resolutions indexed by **[Global Data Index](https://www.globaldataindex.org)**.

Full analytical briefings, structured HTML compliance matrices, semantic definition lists, two-stage Tables of Contents, authority RSS syndication feeds, and unabridged source PDF dossiers are available directly via each record's `canonical_url` on [globaldataindex.org](https://www.globaldataindex.org).

## Live Jurisdiction Breakdown & Canonical Archive Hubs

| Jurisdiction | Indexed Dossiers | Issuing Authorities | Governing Open-Government Framework | Canonical Archive Hub |
| :--- | :--- | :--- | :--- | :--- |
| **[United States](https://www.globaldataindex.org/united-states/)** | `8,922` | `181` | *17 U.S.C. § 105 Public Domain* | [https://www.globaldataindex.org/united-states/](https://www.globaldataindex.org/united-states/) |
| **[United Kingdom](https://www.globaldataindex.org/united-kingdom/)** | `1,952` | `13` | *Open Government Licence v3.0 (OGL v3.0)* | [https://www.globaldataindex.org/united-kingdom/](https://www.globaldataindex.org/united-kingdom/) |
| **[Canada](https://www.globaldataindex.org/canada/)** | `5,238` | `18` | *Reproduction of Federal Law Order (SI/97-5)* | [https://www.globaldataindex.org/canada/](https://www.globaldataindex.org/canada/) |
| **[European Union](https://www.globaldataindex.org/european-union/)** | `2,233` | `15` | *European Commission Reuse Decision (2011/833/EU)* | [https://www.globaldataindex.org/european-union/](https://www.globaldataindex.org/european-union/) |
| **[Australia](https://www.globaldataindex.org/australia/)** | `1,017` | `18` | *Creative Commons Attribution 4.0 (CC BY 4.0)* | [https://www.globaldataindex.org/australia/](https://www.globaldataindex.org/australia/) |
| **[United Nations](https://www.globaldataindex.org/united-nations/)** | `2,978` | `32` | *UN Administrative Instruction ST/AI/189/Add.9/Rev.2* | [https://www.globaldataindex.org/united-nations/](https://www.globaldataindex.org/united-nations/) |
| **[Ireland](https://www.globaldataindex.org/ireland/)** | `88` | `18` | *Oireachtas (Open Data) PSI Licence / CC BY 4.0* | [https://www.globaldataindex.org/ireland/](https://www.globaldataindex.org/ireland/) |

## Primary Issuing Authority Archive Hubs (Top 35 by Dossier Volume)

| Issuing Authority | Jurisdiction | Indexed Dossiers | Canonical Authority Archive | Syndication |
| :--- | :--- | :--- | :--- | :--- |
| **[Department of Justice Canada](https://www.globaldataindex.org/canada/department-of-justice-canada/)** | Canada | `3,418` | [https://www.globaldataindex.org/canada/department-of-justice-canada/](https://www.globaldataindex.org/canada/department-of-justice-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/department-of-justice-canada/feed/) |
| **[Federal Aviation Administration](https://www.globaldataindex.org/united-states/federal-aviation-administration/)** | United States | `2,116` | [https://www.globaldataindex.org/united-states/federal-aviation-administration/](https://www.globaldataindex.org/united-states/federal-aviation-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/federal-aviation-administration/feed/) |
| **[Environmental Protection Agency](https://www.globaldataindex.org/united-states/environmental-protection-agency/)** | United States | `1,211` | [https://www.globaldataindex.org/united-states/environmental-protection-agency/](https://www.globaldataindex.org/united-states/environmental-protection-agency/) | [RSS Feed](https://www.globaldataindex.org/united-states/environmental-protection-agency/feed/) |
| **[General Assembly](https://www.globaldataindex.org/united-nations/general-assembly/)** | United Nations | `1,194` | [https://www.globaldataindex.org/united-nations/general-assembly/](https://www.globaldataindex.org/united-nations/general-assembly/) | [RSS Feed](https://www.globaldataindex.org/united-nations/general-assembly/feed/) |
| **[European Commission](https://www.globaldataindex.org/european-union/european-commission/)** | European Union | `944` | [https://www.globaldataindex.org/european-union/european-commission/](https://www.globaldataindex.org/european-union/european-commission/) | [RSS Feed](https://www.globaldataindex.org/european-union/european-commission/feed/) |
| **[Coast Guard](https://www.globaldataindex.org/united-states/coast-guard/)** | United States | `691` | [https://www.globaldataindex.org/united-states/coast-guard/](https://www.globaldataindex.org/united-states/coast-guard/) | [RSS Feed](https://www.globaldataindex.org/united-states/coast-guard/feed/) |
| **[European Parliament and Council of the EU](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/)** | European Union | `646` | [https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/) | [RSS Feed](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/feed/) |
| **[Transport Canada](https://www.globaldataindex.org/canada/transport-canada/)** | Canada | `639` | [https://www.globaldataindex.org/canada/transport-canada/](https://www.globaldataindex.org/canada/transport-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/transport-canada/feed/) |
| **[Council of the European Union](https://www.globaldataindex.org/european-union/council-of-the-european-union/)** | European Union | `603` | [https://www.globaldataindex.org/european-union/council-of-the-european-union/](https://www.globaldataindex.org/european-union/council-of-the-european-union/) | [RSS Feed](https://www.globaldataindex.org/european-union/council-of-the-european-union/feed/) |
| **[National Oceanic and Atmospheric Administration](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/)** | United States | `517` | [https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/feed/) |
| **[HM Government Legislation](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/)** | United Kingdom | `501` | [https://www.globaldataindex.org/united-kingdom/hm-government-legislation/](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/feed/) |
| **[UN General Assembly (UNGA)](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/)** | United Nations | `462` | [https://www.globaldataindex.org/united-nations/un-general-assembly-unga/](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/feed/) |
| **[Department of Finance Canada](https://www.globaldataindex.org/canada/department-of-finance-canada/)** | Canada | `360` | [https://www.globaldataindex.org/canada/department-of-finance-canada/](https://www.globaldataindex.org/canada/department-of-finance-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/department-of-finance-canada/feed/) |
| **[UN Security Council (UNSC)](https://www.globaldataindex.org/united-nations/un-security-council-unsc/)** | United Nations | `348` | [https://www.globaldataindex.org/united-nations/un-security-council-unsc/](https://www.globaldataindex.org/united-nations/un-security-council-unsc/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-security-council-unsc/feed/) |
| **[Department of the Treasury](https://www.globaldataindex.org/australia/department-of-the-treasury/)** | Australia | `341` | [https://www.globaldataindex.org/australia/department-of-the-treasury/](https://www.globaldataindex.org/australia/department-of-the-treasury/) | [RSS Feed](https://www.globaldataindex.org/australia/department-of-the-treasury/feed/) |
| **[Federal Communications Commission](https://www.globaldataindex.org/united-states/federal-communications-commission/)** | United States | `295` | [https://www.globaldataindex.org/united-states/federal-communications-commission/](https://www.globaldataindex.org/united-states/federal-communications-commission/) | [RSS Feed](https://www.globaldataindex.org/united-states/federal-communications-commission/feed/) |
| **[HM Treasury](https://www.globaldataindex.org/united-kingdom/hm-treasury/)** | United Kingdom | `287` | [https://www.globaldataindex.org/united-kingdom/hm-treasury/](https://www.globaldataindex.org/united-kingdom/hm-treasury/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/hm-treasury/feed/) |
| **[UN Human Rights Council & Treaty Bodies](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/)** | United Nations | `270` | [https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/feed/) |
| **[Food and Drug Administration](https://www.globaldataindex.org/united-states/food-and-drug-administration/)** | United States | `233` | [https://www.globaldataindex.org/united-states/food-and-drug-administration/](https://www.globaldataindex.org/united-states/food-and-drug-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/food-and-drug-administration/feed/) |
| **[Security Council](https://www.globaldataindex.org/united-nations/security-council/)** | United Nations | `213` | [https://www.globaldataindex.org/united-nations/security-council/](https://www.globaldataindex.org/united-nations/security-council/) | [RSS Feed](https://www.globaldataindex.org/united-nations/security-council/feed/) |
| **[Attorney-General's Department](https://www.globaldataindex.org/australia/attorney-general-s-department/)** | Australia | `184` | [https://www.globaldataindex.org/australia/attorney-general-s-department/](https://www.globaldataindex.org/australia/attorney-general-s-department/) | [RSS Feed](https://www.globaldataindex.org/australia/attorney-general-s-department/feed/) |
| **[Department for Transport](https://www.globaldataindex.org/united-kingdom/department-for-transport/)** | United Kingdom | `159` | [https://www.globaldataindex.org/united-kingdom/department-for-transport/](https://www.globaldataindex.org/united-kingdom/department-for-transport/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/department-for-transport/feed/) |
| **[Internal Revenue Service](https://www.globaldataindex.org/united-states/internal-revenue-service/)** | United States | `159` | [https://www.globaldataindex.org/united-states/internal-revenue-service/](https://www.globaldataindex.org/united-states/internal-revenue-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/internal-revenue-service/feed/) |
| **[Crown-Indigenous Relations and Northern Affairs Canada](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/)** | Canada | `156` | [https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/feed/) |
| **[Energy Department](https://www.globaldataindex.org/united-states/energy-department/)** | United States | `155` | [https://www.globaldataindex.org/united-states/energy-department/](https://www.globaldataindex.org/united-states/energy-department/) | [RSS Feed](https://www.globaldataindex.org/united-states/energy-department/feed/) |
| **[Ministry of Housing, Communities and Local Government](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/)** | United Kingdom | `152` | [https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/feed/) |
| **[Human Rights Bodies](https://www.globaldataindex.org/united-nations/human-rights-bodies/)** | United Nations | `149` | [https://www.globaldataindex.org/united-nations/human-rights-bodies/](https://www.globaldataindex.org/united-nations/human-rights-bodies/) | [RSS Feed](https://www.globaldataindex.org/united-nations/human-rights-bodies/feed/) |
| **[Fish and Wildlife Service](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/)** | United States | `149` | [https://www.globaldataindex.org/united-states/fish-and-wildlife-service/](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/feed/) |
| **[Pipeline and Hazardous Materials Safety Administration](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/)** | United States | `140` | [https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/feed/) |
| **[Home Office](https://www.globaldataindex.org/united-kingdom/home-office/)** | United Kingdom | `135` | [https://www.globaldataindex.org/united-kingdom/home-office/](https://www.globaldataindex.org/united-kingdom/home-office/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/home-office/feed/) |
| **[Natural Resources Canada](https://www.globaldataindex.org/canada/natural-resources-canada/)** | Canada | `131` | [https://www.globaldataindex.org/canada/natural-resources-canada/](https://www.globaldataindex.org/canada/natural-resources-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/natural-resources-canada/feed/) |
| **[Nuclear Regulatory Commission](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/)** | United States | `131` | [https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/) | [RSS Feed](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/feed/) |
| **[Department for Education](https://www.globaldataindex.org/united-kingdom/department-for-education/)** | United Kingdom | `129` | [https://www.globaldataindex.org/united-kingdom/department-for-education/](https://www.globaldataindex.org/united-kingdom/department-for-education/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/department-for-education/feed/) |
| **[Department for Energy Security and Net Zero](https://www.globaldataindex.org/united-kingdom/department-for-energy-security-and-net-zero/)** | United Kingdom | `121` | [https://www.globaldataindex.org/united-kingdom/department-for-energy-security-and-net-zero/](https://www.globaldataindex.org/united-kingdom/department-for-energy-security-and-net-zero/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/department-for-energy-security-and-net-zero/feed/) |
| **[Department for Business and Trade](https://www.globaldataindex.org/united-kingdom/department-for-business-and-trade/)** | United Kingdom | `117` | [https://www.globaldataindex.org/united-kingdom/department-for-business-and-trade/](https://www.globaldataindex.org/united-kingdom/department-for-business-and-trade/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/department-for-business-and-trade/feed/) |

*To browse all `295` individual government department, ministry, agency, and multilateral organ archives, visit the **[Indexed Jurisdictions & Issuing Authorities Directory](https://www.globaldataindex.org/methodology/)**.*

## Dataset Files & Schema

- `regulatory_index_2026.csv` — UTF-8 comma-separated index of all published regulatory dossiers.
- `regulatory_index_2026.jsonl` — Newline-delimited JSON records for programmatic ingestion and LLM/RAG citation pipelines.

| Field | Type | Description |
| :--- | :--- | :--- |
| `document_id` | `string` | Official statutory or registry identifier (e.g., `2026-06947`, `UKSI-2026-142`, `CELEX-32026R0815`, `F2026L01394`, `UN-S-RES-2728-2024`, `IE-ACT-2026-27`) |
| `jurisdiction` | `string` | Issuing sovereign jurisdiction or multilateral body |
| `authority` | `string` | Issuing government department, ministry, agency, or organ |
| `publication_date` | `string` | Official publication or enactment date (`YYYY-MM-DD`) |
| `page_count` | `integer` | Verified pagination of the unabridged source PDF dossier |
| `language` | `string` | Primary document language (`English`) |
| `title` | `string` | Official statutory or regulatory title |
| `canonical_url` | `string` | Direct permalink to the executive briefing and PDF dossier on [globaldataindex.org](https://www.globaldataindex.org) |

---

*Maintained autonomously by [Global Data Index](https://www.globaldataindex.org).*
