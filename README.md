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
  - germany
  - bundesrepublik-deutschland
  - gesetze-im-internet
  - robert-koch-institute
  - openagrar
  - govdata
  - world-bank
  - austria
  - ris-bka
  - bundesgesetzblatt
  - fma-austria
  - oenb
  - austrian-laws
  - switzerland
  - swiss-confederation
  - fedlex
  - opendata-swiss
  - sfao
  - finland
  - valtioneuvosto
  - finlex
  - national-audit-office-vtv
  - supreme-court-of-finland
  - supreme-administrative-court-of-finland
  - france
  - republique-francaise
  - banque-de-france
  - amf
  - cour-des-comptes
  - dila
  - norway
  - cristin
  - nva
  - state-agencies
  - international
  - oecd
  - policy-papers
  - economic-surveys
  - artificial-intelligence
  - fao
  - food-and-agriculture-organization
  - italy
  - inapp
  - cnr
  - asi
  - dati-gov-it
  - public-policy
  - poland
  - nbp
  - paih
  - dane-gov-pl
  - wipo
  - intellectual-property
  - patents
  - trademarks
  - south-africa
  - parliament-of-south-africa
  - india
  - parliament-of-india
  - digital-sansad
  - belgium
  - sciensano
  - belgian-federal-government
  - public-health
  - brazil
  - banco-central-do-brasil
  - copom
  - supremo-tribunal-federal
  - camara-dos-deputados
  - fiocruz
  - denmark
  - geus
  - diis
  - royal-danish-library
  - open-data-dk
  - greenland
  - energy
  - geology
  - japan
  - e-gov
  - maff
  - ffpri
  - naro
  - qst
  - government-of-japan
  - south-korea
  - republic-of-korea
  - kei
  - kdi
  - ministry-of-environment
  - netherlands
  - rijksoverheid
  - rivm
  - wodc
  - tweede-kamer
  - russia
  - bank-of-russia
  - central-bank-of-russia
  - sweden
  - riksdagen
  - naturvardsverket
  - trafikverket
  - sou
  - singapore
  - parliament-of-singapore
  - supreme-court-of-singapore
  - gov-sg
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
**Last Automated Sync:** `2026-10-29 02:57 UTC`  
**Total Indexed Public Records in Catalog:** `32,988` across `549` issuing authorities

---

## Overview

This repository provides an automated, machine-readable metadata index (`CSV` and `JSONL`) of official government regulations, statutory instruments, legislation, and multilateral resolutions indexed by **[Global Data Index](https://www.globaldataindex.org)**.

Full analytical briefings, structured HTML compliance matrices, semantic definition lists, two-stage Tables of Contents, authority RSS syndication feeds, and unabridged source PDF dossiers are available directly via each record's `canonical_url` on [globaldataindex.org](https://www.globaldataindex.org).

## Live Jurisdiction Breakdown & Canonical Archive Hubs

| Jurisdiction | Indexed Dossiers | Issuing Authorities | Governing Open-Government Framework | Canonical Archive Hub |
| :--- | :--- | :--- | :--- | :--- |
| **[United States](https://www.globaldataindex.org/united-states/)** | `14,641` | `205` | *17 U.S.C. § 105* | [https://www.globaldataindex.org/united-states/](https://www.globaldataindex.org/united-states/) |
| **[United Kingdom](https://www.globaldataindex.org/united-kingdom/)** | `1,965` | `17` | *Open Government Licence v3.0 (OGL v3.0)* | [https://www.globaldataindex.org/united-kingdom/](https://www.globaldataindex.org/united-kingdom/) |
| **[Canada](https://www.globaldataindex.org/canada/)** | `5,324` | `23` | *Reproduction of Federal Law Order (SI/97-5)* | [https://www.globaldataindex.org/canada/](https://www.globaldataindex.org/canada/) |
| **[European Union](https://www.globaldataindex.org/european-union/)** | `2,271` | `15` | *Commission Decision 2011/833/EU* | [https://www.globaldataindex.org/european-union/](https://www.globaldataindex.org/european-union/) |
| **[Australia](https://www.globaldataindex.org/australia/)** | `1,071` | `18` | *Creative Commons Attribution 4.0 (CC BY 4.0)* | [https://www.globaldataindex.org/australia/](https://www.globaldataindex.org/australia/) |
| **[United Nations](https://www.globaldataindex.org/united-nations/)** | `6,426` | `168` | *UN Administrative Instruction ST/AI/189/Add.9/Rev.2* | [https://www.globaldataindex.org/united-nations/](https://www.globaldataindex.org/united-nations/) |
| **[Ireland](https://www.globaldataindex.org/ireland/)** | `88` | `18` | *Oireachtas (Open Data) PSI Licence (CC BY 4.0) & S.I. No. 349/2021* | [https://www.globaldataindex.org/ireland/](https://www.globaldataindex.org/ireland/) |
| **[Germany](https://www.globaldataindex.org/germany/)** | `108` | `1` | *§ 5 UrhG (Official Works Exemption), § 12a EGovG & Data Licence Germany (dl-de/by-2-0 / CC BY 4.0)* | [https://www.globaldataindex.org/germany/](https://www.globaldataindex.org/germany/) |
| **[International](https://www.globaldataindex.org/international/)** | `252` | `5` | *World Bank Open Access Policy (CC BY 4.0)* | [https://www.globaldataindex.org/international/](https://www.globaldataindex.org/international/) |
| **[Austria](https://www.globaldataindex.org/austria/)** | `99` | `15` | *Austrian UrhG § 7 (Freie Werke) & IWG 2022 / OGD Austria CC BY 4.0* | [https://www.globaldataindex.org/austria/](https://www.globaldataindex.org/austria/) |
| **[Switzerland](https://www.globaldataindex.org/switzerland/)** | `126` | `4` | *Swiss Federal Copyright Act (CopA, SR 231.1), Art. 5 & Federal Act on OGD (EMBAG, Art. 10)* | [https://www.globaldataindex.org/switzerland/](https://www.globaldataindex.org/switzerland/) |
| **[Finland](https://www.globaldataindex.org/finland/)** | `45` | `8` | *Finnish Copyright Act (404/1961, s. 9) & CC BY 4.0 (JHS 189 / Finlex Open Data)* | [https://www.globaldataindex.org/finland/](https://www.globaldataindex.org/finland/) |
| **[France](https://www.globaldataindex.org/france/)** | `146` | `3` | *Licence Ouverte / Open Licence 2.0 (Etalab) & Code des relations entre le public et l'administration (CRPA, Art. L.321-1 & L.323-2)* | [https://www.globaldataindex.org/france/](https://www.globaldataindex.org/france/) |
| **[Norway](https://www.globaldataindex.org/norway/)** | `54` | `6` | *Norwegian Copyright Act (Åndsverkloven) § 14 & NLOD 2.0 / CC BY 4.0* | [https://www.globaldataindex.org/norway/](https://www.globaldataindex.org/norway/) |
| **[Italy](https://www.globaldataindex.org/italy/)** | `55` | `3` | *Italian Copyright Act (Law No. 633/1941, Art. 5), Legislative Decree No. 36/2006 (PSI), CAD (D.Lgs. 82/2005, Art. 52) & CC BY 4.0 / IODL 2.0* | [https://www.globaldataindex.org/italy/](https://www.globaldataindex.org/italy/) |
| **[Poland](https://www.globaldataindex.org/poland/)** | `41` | `2` | *Polish Copyright Act (Dz.U. 1994 nr 24 poz. 83, Art. 4) & Open Data Act (Dz.U. 2021 poz. 1641)* | [https://www.globaldataindex.org/poland/](https://www.globaldataindex.org/poland/) |
| **[South Africa](https://www.globaldataindex.org/south-africa/)** | `46` | `15` | *South African Copyright Act 98 of 1978, s. 12(8)(a)* | [https://www.globaldataindex.org/south-africa/](https://www.globaldataindex.org/south-africa/) |
| **[India](https://www.globaldataindex.org/india/)** | `11` | `3` | *Indian Copyright Act 1957, s. 52(1)(q) & GODL-India* | [https://www.globaldataindex.org/india/](https://www.globaldataindex.org/india/) |
| **[Belgium](https://www.globaldataindex.org/belgium/)** | `19` | `1` | *Belgian Code of Economic Law Art. XI.172 § 2, Federal PSI Reuse Law (4 May 2016) & CC BY 4.0 / CC0* | [https://www.globaldataindex.org/belgium/](https://www.globaldataindex.org/belgium/) |
| **[Brazil](https://www.globaldataindex.org/brazil/)** | `80` | `2` | *Brazilian Copyright Act (Law No. 9,610/1998, Art. 8, IV) & Access to Information Act (Law No. 12,527/2011 / Decree No. 8,777/2016)* | [https://www.globaldataindex.org/brazil/](https://www.globaldataindex.org/brazil/) |
| **[Denmark](https://www.globaldataindex.org/denmark/)** | `22` | `3` | *Danish Copyright Act (Ophavsretsloven), s. 9 & Danish PSI / Open Data Licence (CC BY 4.0 / CC0)* | [https://www.globaldataindex.org/denmark/](https://www.globaldataindex.org/denmark/) |
| **[Japan](https://www.globaldataindex.org/japan/)** | `55` | `7` | *Japanese Copyright Act (Act No. 48 of 1970), Art. 13 & Government of Japan Standard Terms of Use v2.0 (CC BY 4.0)* | [https://www.globaldataindex.org/japan/](https://www.globaldataindex.org/japan/) |
| **[South Korea](https://www.globaldataindex.org/south-korea/)** | `0` | `0` | *Korean Copyright Act, Art. 7 (Public Domain) & KOGL Type 1* | [https://www.globaldataindex.org/south-korea/](https://www.globaldataindex.org/south-korea/) |
| **[Netherlands](https://www.globaldataindex.org/netherlands/)** | `4` | `2` | *Dutch Copyright Act (Auteurswet) Art. 11 & 15b, Wet hergebruik van overheidsinformatie (Who) & CC0 1.0 / CC BY 4.0* | [https://www.globaldataindex.org/netherlands/](https://www.globaldataindex.org/netherlands/) |
| **[Russia](https://www.globaldataindex.org/russia/)** | `0` | `0` | *Civil Code of the Russian Federation, Part IV, Art. 1259(6)(1) & Federal Law No. 8-FZ* | [https://www.globaldataindex.org/russia/](https://www.globaldataindex.org/russia/) |
| **[Sweden](https://www.globaldataindex.org/sweden/)** | `26` | `3` | *Swedish Copyright Act (SFS 1960:729), s. 9 & 26a; Act on Reuse of Public Sector Documents (SFS 2022:818 / PSI & CC0/CC BY 4.0)* | [https://www.globaldataindex.org/sweden/](https://www.globaldataindex.org/sweden/) |
| **[Singapore](https://www.globaldataindex.org/singapore/)** | `13` | `2` | *Singapore Open Data Licence v1.0 & SSO Terms of Use (Clause 13)* | [https://www.globaldataindex.org/singapore/](https://www.globaldataindex.org/singapore/) |

## Primary Issuing Authority Archive Hubs (Top 35 by Dossier Volume)

| Issuing Authority | Jurisdiction | Indexed Dossiers | Canonical Authority Archive | Syndication |
| :--- | :--- | :--- | :--- | :--- |
| **[Federal Aviation Administration](https://www.globaldataindex.org/united-states/federal-aviation-administration/)** | United States | `3,420` | [https://www.globaldataindex.org/united-states/federal-aviation-administration/](https://www.globaldataindex.org/united-states/federal-aviation-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/federal-aviation-administration/feed/) |
| **[Department of Justice Canada](https://www.globaldataindex.org/canada/department-of-justice-canada/)** | Canada | `3,418` | [https://www.globaldataindex.org/canada/department-of-justice-canada/](https://www.globaldataindex.org/canada/department-of-justice-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/department-of-justice-canada/feed/) |
| **[General Assembly](https://www.globaldataindex.org/united-nations/general-assembly/)** | United Nations | `3,007` | [https://www.globaldataindex.org/united-nations/general-assembly/](https://www.globaldataindex.org/united-nations/general-assembly/) | [RSS Feed](https://www.globaldataindex.org/united-nations/general-assembly/feed/) |
| **[Environmental Protection Agency](https://www.globaldataindex.org/united-states/environmental-protection-agency/)** | United States | `1,869` | [https://www.globaldataindex.org/united-states/environmental-protection-agency/](https://www.globaldataindex.org/united-states/environmental-protection-agency/) | [RSS Feed](https://www.globaldataindex.org/united-states/environmental-protection-agency/feed/) |
| **[Coast Guard](https://www.globaldataindex.org/united-states/coast-guard/)** | United States | `1,179` | [https://www.globaldataindex.org/united-states/coast-guard/](https://www.globaldataindex.org/united-states/coast-guard/) | [RSS Feed](https://www.globaldataindex.org/united-states/coast-guard/feed/) |
| **[European Commission](https://www.globaldataindex.org/european-union/european-commission/)** | European Union | `966` | [https://www.globaldataindex.org/european-union/european-commission/](https://www.globaldataindex.org/european-union/european-commission/) | [RSS Feed](https://www.globaldataindex.org/european-union/european-commission/feed/) |
| **[National Oceanic and Atmospheric Administration](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/)** | United States | `904` | [https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/national-oceanic-and-atmospheric-administration/feed/) |
| **[European Parliament and Council of the EU](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/)** | European Union | `646` | [https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/) | [RSS Feed](https://www.globaldataindex.org/european-union/european-parliament-and-council-of-the-eu/feed/) |
| **[Transport Canada](https://www.globaldataindex.org/canada/transport-canada/)** | Canada | `639` | [https://www.globaldataindex.org/canada/transport-canada/](https://www.globaldataindex.org/canada/transport-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/transport-canada/feed/) |
| **[Council of the European Union](https://www.globaldataindex.org/european-union/council-of-the-european-union/)** | European Union | `619` | [https://www.globaldataindex.org/european-union/council-of-the-european-union/](https://www.globaldataindex.org/european-union/council-of-the-european-union/) | [RSS Feed](https://www.globaldataindex.org/european-union/council-of-the-european-union/feed/) |
| **[Economic and Social Council](https://www.globaldataindex.org/united-nations/economic-and-social-council/)** | United Nations | `526` | [https://www.globaldataindex.org/united-nations/economic-and-social-council/](https://www.globaldataindex.org/united-nations/economic-and-social-council/) | [RSS Feed](https://www.globaldataindex.org/united-nations/economic-and-social-council/feed/) |
| **[Federal Communications Commission](https://www.globaldataindex.org/united-states/federal-communications-commission/)** | United States | `521` | [https://www.globaldataindex.org/united-states/federal-communications-commission/](https://www.globaldataindex.org/united-states/federal-communications-commission/) | [RSS Feed](https://www.globaldataindex.org/united-states/federal-communications-commission/feed/) |
| **[HM Government Legislation](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/)** | United Kingdom | `501` | [https://www.globaldataindex.org/united-kingdom/hm-government-legislation/](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/hm-government-legislation/feed/) |
| **[Security Council](https://www.globaldataindex.org/united-nations/security-council/)** | United Nations | `489` | [https://www.globaldataindex.org/united-nations/security-council/](https://www.globaldataindex.org/united-nations/security-council/) | [RSS Feed](https://www.globaldataindex.org/united-nations/security-council/feed/) |
| **[Human Rights Bodies](https://www.globaldataindex.org/united-nations/human-rights-bodies/)** | United Nations | `465` | [https://www.globaldataindex.org/united-nations/human-rights-bodies/](https://www.globaldataindex.org/united-nations/human-rights-bodies/) | [RSS Feed](https://www.globaldataindex.org/united-nations/human-rights-bodies/feed/) |
| **[UN General Assembly (UNGA)](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/)** | United Nations | `462` | [https://www.globaldataindex.org/united-nations/un-general-assembly-unga/](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-general-assembly-unga/feed/) |
| **[Department of Finance Canada](https://www.globaldataindex.org/canada/department-of-finance-canada/)** | Canada | `360` | [https://www.globaldataindex.org/canada/department-of-finance-canada/](https://www.globaldataindex.org/canada/department-of-finance-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/department-of-finance-canada/feed/) |
| **[Department of the Treasury](https://www.globaldataindex.org/australia/department-of-the-treasury/)** | Australia | `352` | [https://www.globaldataindex.org/australia/department-of-the-treasury/](https://www.globaldataindex.org/australia/department-of-the-treasury/) | [RSS Feed](https://www.globaldataindex.org/australia/department-of-the-treasury/feed/) |
| **[UN Security Council (UNSC)](https://www.globaldataindex.org/united-nations/un-security-council-unsc/)** | United Nations | `348` | [https://www.globaldataindex.org/united-nations/un-security-council-unsc/](https://www.globaldataindex.org/united-nations/un-security-council-unsc/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-security-council-unsc/feed/) |
| **[Food and Drug Administration](https://www.globaldataindex.org/united-states/food-and-drug-administration/)** | United States | `305` | [https://www.globaldataindex.org/united-states/food-and-drug-administration/](https://www.globaldataindex.org/united-states/food-and-drug-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/food-and-drug-administration/feed/) |
| **[HM Treasury](https://www.globaldataindex.org/united-kingdom/hm-treasury/)** | United Kingdom | `288` | [https://www.globaldataindex.org/united-kingdom/hm-treasury/](https://www.globaldataindex.org/united-kingdom/hm-treasury/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/hm-treasury/feed/) |
| **[Fish and Wildlife Service](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/)** | United States | `277` | [https://www.globaldataindex.org/united-states/fish-and-wildlife-service/](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/fish-and-wildlife-service/feed/) |
| **[UN Human Rights Council & Treaty Bodies](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/)** | United Nations | `270` | [https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/) | [RSS Feed](https://www.globaldataindex.org/united-nations/un-human-rights-council-treaty-bodies/feed/) |
| **[Energy Department](https://www.globaldataindex.org/united-states/energy-department/)** | United States | `261` | [https://www.globaldataindex.org/united-states/energy-department/](https://www.globaldataindex.org/united-states/energy-department/) | [RSS Feed](https://www.globaldataindex.org/united-states/energy-department/feed/) |
| **[Internal Revenue Service](https://www.globaldataindex.org/united-states/internal-revenue-service/)** | United States | `258` | [https://www.globaldataindex.org/united-states/internal-revenue-service/](https://www.globaldataindex.org/united-states/internal-revenue-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/internal-revenue-service/feed/) |
| **[Nuclear Regulatory Commission](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/)** | United States | `222` | [https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/) | [RSS Feed](https://www.globaldataindex.org/united-states/nuclear-regulatory-commission/feed/) |
| **[United Nations Secretariat](https://www.globaldataindex.org/united-nations/united-nations-secretariat/)** | United Nations | `197` | [https://www.globaldataindex.org/united-nations/united-nations-secretariat/](https://www.globaldataindex.org/united-nations/united-nations-secretariat/) | [RSS Feed](https://www.globaldataindex.org/united-nations/united-nations-secretariat/feed/) |
| **[Agricultural Marketing Service](https://www.globaldataindex.org/united-states/agricultural-marketing-service/)** | United States | `190` | [https://www.globaldataindex.org/united-states/agricultural-marketing-service/](https://www.globaldataindex.org/united-states/agricultural-marketing-service/) | [RSS Feed](https://www.globaldataindex.org/united-states/agricultural-marketing-service/feed/) |
| **[Attorney-General's Department](https://www.globaldataindex.org/australia/attorney-general-s-department/)** | Australia | `184` | [https://www.globaldataindex.org/australia/attorney-general-s-department/](https://www.globaldataindex.org/australia/attorney-general-s-department/) | [RSS Feed](https://www.globaldataindex.org/australia/attorney-general-s-department/feed/) |
| **[Centers for Medicare & Medicaid Services](https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/)** | United States | `177` | [https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/](https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/) | [RSS Feed](https://www.globaldataindex.org/united-states/centers-for-medicare-medicaid-services/feed/) |
| **[Office of the Secretary](https://www.globaldataindex.org/united-states/office-of-the-secretary/)** | United States | `173` | [https://www.globaldataindex.org/united-states/office-of-the-secretary/](https://www.globaldataindex.org/united-states/office-of-the-secretary/) | [RSS Feed](https://www.globaldataindex.org/united-states/office-of-the-secretary/feed/) |
| **[Department for Transport](https://www.globaldataindex.org/united-kingdom/department-for-transport/)** | United Kingdom | `164` | [https://www.globaldataindex.org/united-kingdom/department-for-transport/](https://www.globaldataindex.org/united-kingdom/department-for-transport/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/department-for-transport/feed/) |
| **[Pipeline and Hazardous Materials Safety Administration](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/)** | United States | `163` | [https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/) | [RSS Feed](https://www.globaldataindex.org/united-states/pipeline-and-hazardous-materials-safety-administration/feed/) |
| **[Crown-Indigenous Relations and Northern Affairs Canada](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/)** | Canada | `156` | [https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/) | [RSS Feed](https://www.globaldataindex.org/canada/crown-indigenous-relations-and-northern-affairs-canada/feed/) |
| **[Ministry of Housing, Communities and Local Government](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/)** | United Kingdom | `153` | [https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/) | [RSS Feed](https://www.globaldataindex.org/united-kingdom/ministry-of-housing-communities-and-local-government/feed/) |

*To browse all `549` individual government department, ministry, agency, and multilateral organ archives, visit the **[Indexed Jurisdictions & Issuing Authorities Directory](https://www.globaldataindex.org/methodology/)**.*

## Dataset Files & Schema

- `regulatory_index_2026.csv` — UTF-8 comma-separated index of all published regulatory dossiers.
- `regulatory_index_2026.jsonl` — Newline-delimited JSON records for programmatic ingestion and LLM/RAG citation pipelines.

| Field | Type | Description |
| :--- | :--- | :--- |
| `document_id` | `string` | Official statutory or registry identifier (e.g., `2026-06947`, `UKSI-2026-142`, `SOR-2026-45`, `CELEX-32026R0815`, `F2026L01394`, `UN-S-RES-2728-2024`, `IE-ACT-2026-27`, `DE-GII-BGB`, `WB-34442292`, `AT-ERV-1991-52`, `CH-FEDLEX-1993-1798-20250101`, `FI-VTV-28851`, `FR-INFOFI-109684-20120412`, `NO-CRISTIN-2345678`, `OECD-PUB-257230EC-EN`, `FAO-I9419EN`, `IT-INAPP-5255`, `PL-PAIH-205192`, `WIPO-60683`, `ZA-BILL-B27-2026`, `IN-SANSAD-1538515`, `BE-SCIENSANO-7928`, `BR-BCB-COPOM-281`, `DK-GEUS-92135`, `JP-EGOV-910DBEE5`, `KR-KEI-2017.oak-20410`, `NL-RIVM-656735`, `RU-CBR-41665`, `SE-TRV-trafikverket-20039`, `SG-SUPCT-2026-SGHC-50`) |
| `jurisdiction` | `string` | Issuing sovereign jurisdiction or multilateral classification |
| `authority` | `string` | Issuing government department, ministry, agency, or international institution |
| `publication_date` | `string` | Official publication or enactment date (`YYYY-MM-DD`) |
| `page_count` | `integer` | Verified pagination of the unabridged source PDF dossier |
| `language` | `string` | Primary document language (`English`) |
| `title` | `string` | Official statutory or regulatory title |
| `canonical_url` | `string` | Direct permalink to the executive briefing and PDF dossier on [globaldataindex.org](https://www.globaldataindex.org) |

---

*Maintained autonomously by [Global Data Index](https://www.globaldataindex.org).*
