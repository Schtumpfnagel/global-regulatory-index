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
  - united-states
  - united-kingdom
  - uksi
  - ukpga
  - canada
  - justice-laws
  - eur-lex
  - european-union
  - australia
  - united-nations
  - ireland
  - oireachtas
  - world-bank
  - fao
  - food-and-agriculture-organization
  - wipo
  - intellectual-property
  - patents
  - trademarks
  - south-africa
  - parliament-of-south-africa
  - india
  - parliament-of-india
  - digital-sansad
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
**Last Automated Sync:** `2026-10-27 06:56 UTC`  
**Total Indexed Public Records in Catalog:** `30,580` across `467` issuing authorities

---

## Overview

This repository provides an automated, machine-readable metadata index (`CSV` and `JSONL`) of official government regulations, statutory instruments, legislation, and multilateral resolutions indexed by **[Global Data Index](https://www.globaldataindex.org)**.

Full analytical briefings, structured HTML compliance matrices, semantic definition lists, two-stage Tables of Contents, authority RSS syndication feeds, and unabridged source PDF dossiers are available directly via each record's `canonical_url` on [globaldataindex.org](https://www.globaldataindex.org).

## Live Jurisdiction Breakdown & Canonical Archive Hubs

| Jurisdiction | Indexed Dossiers | Issuing Authorities | Governing Open-Government Framework | Canonical Archive Hub |
| :--- | :--- | :--- | :--- | :--- |
| **[United States](https://www.globaldataindex.org/united-states/)** | `13,551` | `198` | *17 U.S.C. § 105* | [https://www.globaldataindex.org/united-states/](https://www.globaldataindex.org/united-states/) |
| **[United Kingdom](https://www.globaldataindex.org/united-kingdom/)** | `1,959` | `15` | *Open Government Licence v3.0 (OGL v3.0)* | [https://www.globaldataindex.org/united-kingdom/](https://www.globaldataindex.org/united-kingdom/) |
| **[Canada](https://www.globaldataindex.org/canada/)** | `5,238` | `18` | *Reproduction of Federal Law Order (SI/97-5)* | [https://www.globaldataindex.org/canada/](https://www.globaldataindex.org/canada/) |
| **[European Union](https://www.globaldataindex.org/european-union/)** | `2,242` | `15` | *Commission Decision 2011/833/EU* | [https://www.globaldataindex.org/european-union/](https://www.globaldataindex.org/european-union/) |
| **[Australia](https://www.globaldataindex.org/australia/)** | `1,047` | `18` | *Creative Commons Attribution 4.0 (CC BY 4.0)* | [https://www.globaldataindex.org/australia/](https://www.globaldataindex.org/australia/) |
| **[United Nations](https://www.globaldataindex.org/united-nations/)** | `6,265` | `164` | *UN Administrative Instruction ST/AI/189/Add.9/Rev.2* | [https://www.globaldataindex.org/united-nations/](https://www.globaldataindex.org/united-nations/) |
| **[Ireland](https://www.globaldataindex.org/ireland/)** | `88` | `18` | *Oireachtas (Open Data) PSI Licence (CC BY 4.0) & S.I. No. 349/2021* | [https://www.globaldataindex.org/ireland/](https://www.globaldataindex.org/ireland/) |
| **[International](https://www.globaldataindex.org/international/)** | `133` | `3` | *World Bank Open Access Policy (CC BY 4.0)* | [https://www.globaldataindex.org/international/](https://www.globaldataindex.org/international/) |
| **[South Africa](https://www.globaldataindex.org/south-africa/)** | `46` | `15` | *South African Copyright Act 98 of 1978, s. 12(8)(a)* | [https://www.globaldataindex.org/south-africa/](https://www.globaldataindex.org/south-africa/) |
| **[India](https://www.globaldataindex.org/india/)** | `11` | `3` | *Indian Copyright Act 1957, s. 52(1)(q) & GODL-India* | [https://www.globaldataindex.org/india/](https://www.globaldataindex.org/india/) |

## Primary Issuing Authority Archive Hubs (Top 35 by Dossier Volume)

| Issuing Authority | Jurisdiction | Indexed Dossiers | Canonical Authority Archive | Syndication |
| :--- | :--- | :--- | :--- | :--- |
| **[Department of Justice Canada](https://www.globaldataindex.org/canada/department-of-justice-canada/)** | Canada | `3,418` | [https://www.globaldataindex.org/canada/department-of-justice-canada/](https://www.globaldataindex.org/canada/department-of-justice-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/department-of-justice-canada/feed/) |
| **[Federal Aviation Administration](https://www.globaldataindex.org/united-states/federal-aviation-administration/)** | United States | `3,181` | [https://www.globaldataindex.org/united-states/federal-aviation-administration/](https://www.globaldataindex.org/united-states/federal-aviation-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/federal-aviation-administration/feed/) |
| **[General Assembly](https://www.globaldataindex.org/united-nations/general-assembly/)** | United Nations | `2,985` | [https://www.globaldataindex.org/united-nations/general-assembly/](https://www.globaldataindex.org/united-nations/general-assembly/) | [RSS Feed](https://www.globaldataindex.org/united-nations/general-assembly/feed/) |
| **[Environmental Protection Agency](https://www.globaldataindex.org/united-states/environmental-protection-agency/)** | United States | `1,762` | [https://www.globaldataindex.org/united-states/environmental-protection-agency/](https://www.globaldataindex.org/united-states/environmental-protection-agency/) | [RSS Feed](https://www.globaldataindex.org/united-states/environmental-protection-agency/feed/) |
| **[Coast Guard](https://www.globaldataindex.org/united-states/coast-guard/)** | United States | `1,100` | [https://www.globaldataindex.org/united-states/coast-guard/](https://www.globaldataindex.org/united-states/coast-guard/) | [RSS Feed](https://www.globaldataindex.org/united-states/coast-guard/feed/) |
| **[European Commission](https://www.globaldataindex.org/european-union/european-commission/)** | European Union | `953` | [https://www.globaldataindex.org/european-union/european-commission/](https://www.globaldataindex.org/european-union/european-commission/) | [RSS Feed](https://www.globaldataindex.org/european-union/european-commission/feed/) |
| **[National Oceanic and Atmospheric Administration](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/)** | United States | `855` | [https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/feed/) |
| **[European Parliament and Council of the EU](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/)** | European Union | `646` | [https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/) | [RSS Feed](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/feed/) |
| **[Transport Canada](https://www.globaldataindex.org/canada/transport-canada/)** | Canada | `639` | [https://www.globaldataindex.org/canada/transport-canada/](https://www.globaldataindex.org/canada/transport-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/transport-canada/feed/) |
| **[Council of the European Union](https://www.globaldataindex.org/european-union/council-of-the-european-union/)** | European Union | `603` | [https://www.globaldataindex.org/european-union/council-of-the-european-union/](https://www.globaldataindex.org/european-union/council-of-the-european-union/) | [RSS Feed](https://www.globaldataindex.org/european-union/council-of-the-european-union/feed/) |
| **[HM Government Legislation](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/)** | United Kingdom | `501` | [https://www.globaldataindex.org/united-kingdom/hm-government-legislation/](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/feed/) |
| **[Federal Communications Commission](https://www.globaldataindex.org/united-states/federal-communications-commission/)** | United States | `491` | [https://www.globaldataindex.org/united-states/federal-communications-commission/](https://www.globaldataindex.org/united-states/federal-communications-commission/) | [RSS Feed](https://www.globaldataindex.org/united-states/federal-communications-commission/feed/) |
| **[Security Council](https://www.globaldataindex.org/united-nations/security-council/)** | United Nations | `484` | [https://www.globaldataindex.org/united-nations/security-council/](https://www.globaldataindex.org/united-nations/security-council/) | [RSS Feed](https://www.globaldataindex.org/united-nations/security-council/feed/) |
| **[Economic and Social Council](https://www.globaldataindex.org/united-nations/economic-and-social-council/)** | United Nations | `467` | [https://www.globaldataindex.org/united-nations/economic-and-social-council/](https://www.globaldataindex.org/united-nations/economic-and-social-council/) | [RSS Feed](https://www.globaldataindex.org/united-nations/economic-and-social-council/feed/) |
| **[Human Rights Bodies](https://www.globaldataindex.org/united-nations/human-rights-bodies/)** | United Nations | `464` | [https://www.globaldataindex.org/united-nations/human-rights-bodies/](https://www.globaldataindex.org/united-nations/human-rights-bodies/) | [RSS Feed](https://www.globaldataindex.org/united-nations/human-rights-bodies/feed/) |
| **[UN General Assembly (UNGA)](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/)** | United Nations | `462` | [https://www.globaldataindex.org/united-nations/un-general-assembly-unga/](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/feed/) |
| **[Department of Finance Canada](https://www.globaldataindex.org/canada/department-of-finance-canada/)** | Canada | `360` | [https://www.globaldataindex.org/canada/department-of-finance-canada/](https://www.globaldataindex.org/canada/department-of-finance-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/department-of-finance-canada/feed/) |
| **[UN Security Council (UNSC)](https://www.globaldataindex.org/united-nations/un-security-council-unsc/)** | United Nations | `348` | [https://www.globaldataindex.org/united-nations/un-security-council-unsc/](https://www.globaldataindex.org/united-nations/un-security-council-unsc/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-security-council-unsc/feed/) |
| **[Department of the Treasury](https://www.globaldataindex.org/australia/department-of-the-treasury/)** | Australia | `347` | [https://www.globaldataindex.org/australia/department-of-the-treasury/](https://www.globaldataindex.org/australia/department-of-the-treasury/) | [RSS Feed](https://www.globaldataindex.org/australia/department-of-the-treasury/feed/) |
| **[Food and Drug Administration](https://www.globaldataindex.org/united-states/food-and-drug-administration/)** | United States | `301` | [https://www.globaldataindex.org/united-states/food-and-drug-administration/](https://www.globaldataindex.org/united-states/food-and-drug-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/food-and-drug-administration/feed/) |
| **[HM Treasury](https://www.globaldataindex.org/united-kingdom/hm-treasury/)** | United Kingdom | `287` | [https://www.globaldataindex.org/united-kingdom/hm-treasury/](https://www.globaldataindex.org/united-kingdom/hm-treasury/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/hm-treasury/feed/) |
| **[UN Human Rights Council & Treaty Bodies](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/)** | United Nations | `270` | [https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/feed/) |
| **[Fish and Wildlife Service](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/)** | United States | `253` | [https://www.globaldataindex.org/united-states/fish-and-wildlife-service/](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/feed/) |
| **[Internal Revenue Service](https://www.globaldataindex.org/united-states/internal-revenue-service/)** | United States | `245` | [https://www.globaldataindex.org/united-states/internal-revenue-service/](https://www.globaldataindex.org/united-states/internal-revenue-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/internal-revenue-service/feed/) |
| **[Energy Department](https://www.globaldataindex.org/united-states/energy-department/)** | United States | `244` | [https://www.globaldataindex.org/united-states/energy-department/](https://www.globaldataindex.org/united-states/energy-department/) | [RSS Feed](https://www.globaldataindex.org/united-states/energy-department/feed/) |
| **[Nuclear Regulatory Commission](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/)** | United States | `208` | [https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/) | [RSS Feed](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/feed/) |
| **[United Nations Secretariat](https://www.globaldataindex.org/united-nations/united-nations-secretariat/)** | United Nations | `187` | [https://www.globaldataindex.org/united-nations/united-nations-secretariat/](https://www.globaldataindex.org/united-nations/united-nations-secretariat/) | [RSS Feed](https://www.globaldataindex.org/united-nations/united-nations-secretariat/feed/) |
| **[Attorney-General's Department](https://www.globaldataindex.org/australia/attorney-general-s-department/)** | Australia | `184` | [https://www.globaldataindex.org/australia/attorney-general-s-department/](https://www.globaldataindex.org/australia/attorney-general-s-department/) | [RSS Feed](https://www.globaldataindex.org/australia/attorney-general-s-department/feed/) |
| **[Agricultural Marketing Service](https://www.globaldataindex.org/united-states/agricultural-marketing-service/)** | United States | `180` | [https://www.globaldataindex.org/united-states/agricultural-marketing-service/](https://www.globaldataindex.org/united-states/agricultural-marketing-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/agricultural-marketing-service/feed/) |
| **[Centers for Medicare & Medicaid Services](https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/)** | United States | `168` | [https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/](https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/) | [RSS Feed](https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/feed/) |
| **[Department for Transport](https://www.globaldataindex.org/united-kingdom/department-for-transport/)** | United Kingdom | `162` | [https://www.globaldataindex.org/united-kingdom/department-for-transport/](https://www.globaldataindex.org/united-kingdom/department-for-transport/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/department-for-transport/feed/) |
| **[Office of the Secretary](https://www.globaldataindex.org/united-states/office-of-the-secretary/)** | United States | `160` | [https://www.globaldataindex.org/united-states/office-of-the-secretary/](https://www.globaldataindex.org/united-states/office-of-the-secretary/) | [RSS Feed](https://www.globaldataindex.org/united-states/office-of-the-secretary/feed/) |
| **[Pipeline and Hazardous Materials Safety Administration](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/)** | United States | `159` | [https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/feed/) |
| **[Crown-Indigenous Relations and Northern Affairs Canada](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/)** | Canada | `156` | [https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/feed/) |
| **[Ministry of Housing, Communities and Local Government](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/)** | United Kingdom | `153` | [https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/feed/) |

*To browse all `467` individual government department, ministry, agency, and multilateral organ archives, visit the **[Indexed Jurisdictions & Issuing Authorities Directory](https://www.globaldataindex.org/methodology/)**.*

## Dataset Files & Schema

- `regulatory_index_2026.csv` — UTF-8 comma-separated index of all published regulatory dossiers.
- `regulatory_index_2026.jsonl` — Newline-delimited JSON records for programmatic ingestion and LLM/RAG citation pipelines.

| Field | Type | Description |
| :--- | :--- | :--- |
| `document_id` | `string` | Official statutory or registry identifier (e.g., `2026-06947`, `UKSI-2026-142`, `SOR-2026-45`, `CELEX-32026R0815`, `F2026L01394`, `UN-S-RES-2728-2024`, `IE-ACT-2026-27`, `WB-34442292`, `FAO-I9419EN`, `WIPO-60683`, `ZA-BILL-B27-2026`, `IN-SANSAD-1538515`) |
| `jurisdiction` | `string` | Issuing sovereign jurisdiction or multilateral classification |
| `authority` | `string` | Issuing government department, ministry, agency, or international institution |
| `publication_date` | `string` | Official publication or enactment date (`YYYY-MM-DD`) |
| `page_count` | `integer` | Verified pagination of the unabridged source PDF dossier |
| `language` | `string` | Primary document language (`English`) |
| `title` | `string` | Official statutory or regulatory title |
| `canonical_url` | `string` | Direct permalink to the executive briefing and PDF dossier on [globaldataindex.org](https://www.globaldataindex.org) |

---

*Maintained autonomously by [Global Data Index](https://www.globaldataindex.org).*
