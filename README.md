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
  - statutory-agencies
  - public-sector
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
  - finnish-environment-institute-syke
  - natural-resources-institute-finland-luke
  - sitra
  - finnish-competition-and-consumer-authority-kkv
  - digital-and-population-data-services-agency-dvv
  - nordic-welfare-centre
  - france
  - republique-francaise
  - banque-de-france
  - amf
  - cour-des-comptes
  - dila
  - south-korea
  - republic-of-korea
  - moef
  - kiep
  - kdi
  - bank-of-korea
  - kihasa
  - kict
  - mfds
  - norway
  - cristin
  - nva
  - state-agencies
  - ombudsman
  - fdk
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
  - philippines
  - government-procurement-policy-board
  - cooperative-development-authority
  - national-privacy-commission
  - commission-on-human-rights
  - department-of-agriculture
  - food-and-drug-administration
  - board-of-investments
  - employees-compensation-commission
  - national-wages-and-productivity-commission
  - maritime-industry-authority
  - philippine-carabao-center
  - bangko-sentral-ng-pilipinas
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
  - geological-survey-of-belgium
  - belgian-federal-government
  - public-health
  - brazil
  - banco-central-do-brasil
  - copom
  - supremo-tribunal-federal
  - camara-dos-deputados
  - fiocruz
  - japan
  - e-gov
  - maff
  - ffpri
  - naro
  - qst
  - government-of-japan
  - russia
  - gaidar-institute
  - imemo-ras
  - cemi-ras
  - ministry-of-health-russia
  - russian-academy-of-sciences
  - sweden
  - trafikverket
  - naturvardsverket
  - vti
  - sgu
  - scb
  - msb
  - vetenskapsradet
configs:
  - config_name: default
    data_files:
      - split: train
        path: regulatory_index_2026.jsonl
---

# Global Regulatory & Statutory Open Metadata Index (2024–2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23612006.svg)](https://doi.org/10.5281/zenodo.23612006)

**Primary Institutional Terminal:** [Index Data (https://www.indexdata.org)](https://www.indexdata.org)  
**Permanent Archival DOI (CERN / Zenodo):** [https://doi.org/10.5281/zenodo.23612006](https://doi.org/10.5281/zenodo.23612006)  
**Complete Authority Directory & Methodology:** [https://www.indexdata.org/methodology/](https://www.indexdata.org/methodology/)  
**AI / LLM Manifest (`llms.txt`):** [https://www.indexdata.org/llms.txt](https://www.indexdata.org/llms.txt)  
**Statutory Licensing Schedule:** [https://www.indexdata.org/terms-of-service/](https://www.indexdata.org/terms-of-service/)  
**Last Automated Sync:** `2026-11-06 18:37 UTC`  
**Total Indexed Public Records in Catalog:** `36,541` across `739` issuing authorities

---

## Overview

This repository provides an automated, machine-readable metadata index (`CSV` and `JSONL`) of official government regulations, statutory instruments, legislation, and multilateral resolutions indexed by **[Index Data](https://www.indexdata.org)**.

Full analytical briefings, structured HTML compliance matrices, semantic definition lists, two-stage Tables of Contents, authority RSS syndication feeds, and unabridged source PDF dossiers are available directly via each record's `canonical_url` on [indexdata.org](https://www.indexdata.org).

## Live Jurisdiction Breakdown & Canonical Archive Hubs

| Jurisdiction | Indexed Dossiers | Issuing Authorities | Governing Open-Government Framework | Canonical Archive Hub |
| :--- | :--- | :--- | :--- | :--- |
| **[United States](https://www.indexdata.org/united-states/)** | `15,087` | `217` | *17 U.S.C. § 105* | [https://www.indexdata.org/united-states/](https://www.indexdata.org/united-states/) |
| **[United Kingdom](https://www.indexdata.org/united-kingdom/)** | `2,301` | `53` | *Open Government Licence v3.0 (OGL v3.0)* | [https://www.indexdata.org/united-kingdom/](https://www.indexdata.org/united-kingdom/) |
| **[Canada](https://www.indexdata.org/canada/)** | `5,342` | `25` | *Reproduction of Federal Law Order (SI/97-5)* | [https://www.indexdata.org/canada/](https://www.indexdata.org/canada/) |
| **[European Union](https://www.indexdata.org/european-union/)** | `3,008` | `29` | *Commission Decision 2011/833/EU* | [https://www.indexdata.org/european-union/](https://www.indexdata.org/european-union/) |
| **[Australia](https://www.indexdata.org/australia/)** | `1,142` | `18` | *Creative Commons Attribution 4.0 (CC BY 4.0)* | [https://www.indexdata.org/australia/](https://www.indexdata.org/australia/) |
| **[United Nations](https://www.indexdata.org/united-nations/)** | `6,912` | `171` | *UN Administrative Instruction ST/AI/189/Add.9/Rev.2* | [https://www.indexdata.org/united-nations/](https://www.indexdata.org/united-nations/) |
| **[Ireland](https://www.indexdata.org/ireland/)** | `159` | `34` | *PSI License / CC BY 4.0 / Oireachtas Open Data PSI Licence (S.I. No. 279/2005, S.I. No. 525/2015 & S.I. No. 376/2021)* | [https://www.indexdata.org/ireland/](https://www.indexdata.org/ireland/) |
| **[International](https://www.indexdata.org/international/)** | `876` | `15` | *WB OA Policy / CC BY 3.0 IGO & CC BY 4.0* | [https://www.indexdata.org/international/](https://www.indexdata.org/international/) |
| **[Austria](https://www.indexdata.org/austria/)** | `155` | `17` | *Austrian UrhG § 7 (Freie Werke) & IWG 2022 / OGD Austria CC BY 4.0* | [https://www.indexdata.org/austria/](https://www.indexdata.org/austria/) |
| **[Switzerland](https://www.indexdata.org/switzerland/)** | `180` | `5` | *Swiss Federal Copyright Act (CopA, SR 231.1), Art. 5 & Federal Act on OGD (EMBAG, Art. 10)* | [https://www.indexdata.org/switzerland/](https://www.indexdata.org/switzerland/) |
| **[Finland](https://www.indexdata.org/finland/)** | `65` | `13` | *Copyright Act (404/1961) § 9 & Act on the Openness of Government Activities (621/1999) / CC BY 4.0* | [https://www.indexdata.org/finland/](https://www.indexdata.org/finland/) |
| **[France](https://www.indexdata.org/france/)** | `286` | `3` | *Licence Ouverte / Open Licence 2.0 (Etalab) & Code des relations entre le public et l'administration (CRPA, Art. L.321-1 & L.323-2)* | [https://www.indexdata.org/france/](https://www.indexdata.org/france/) |
| **[South Korea](https://www.indexdata.org/south-korea/)** | `66` | `7` | *Copyright Act Art. 7 & Art. 24-2 / KOGL Type 1* | [https://www.indexdata.org/south-korea/](https://www.indexdata.org/south-korea/) |
| **[Norway](https://www.indexdata.org/norway/)** | `71` | `9` | *Åndsverkloven § 14 / NLOD 2.0* | [https://www.indexdata.org/norway/](https://www.indexdata.org/norway/) |
| **[Italy](https://www.indexdata.org/italy/)** | `57` | `3` | *Italian Copyright Act (Law No. 633/1941, Art. 5), Legislative Decree No. 36/2006 (PSI), CAD (D.Lgs. 82/2005, Art. 52) & CC BY 4.0 / IODL 2.0* | [https://www.indexdata.org/italy/](https://www.indexdata.org/italy/) |
| **[Philippines](https://www.indexdata.org/philippines/)** | `10` | `8` | *R.A. 8293 § 176.1 & Open Data Philippines Policy* | [https://www.indexdata.org/philippines/](https://www.indexdata.org/philippines/) |
| **[Poland](https://www.indexdata.org/poland/)** | `42` | `2` | *Polish Copyright Act (Dz.U. 1994 nr 24 poz. 83, Art. 4) & Open Data Act (Dz.U. 2021 poz. 1641)* | [https://www.indexdata.org/poland/](https://www.indexdata.org/poland/) |
| **[South Africa](https://www.indexdata.org/south-africa/)** | `46` | `15` | *South African Copyright Act 98 of 1978, s. 12(8)(a)* | [https://www.indexdata.org/south-africa/](https://www.indexdata.org/south-africa/) |
| **[India](https://www.indexdata.org/india/)** | `11` | `3` | *Indian Copyright Act 1957, s. 52(1)(q) & GODL-India* | [https://www.indexdata.org/india/](https://www.indexdata.org/india/) |
| **[Belgium](https://www.indexdata.org/belgium/)** | `25` | `3` | *Code of Economic Law Art. XI.172 & Belgian Act of 4 May 2016 (PSI / CC0 / CC BY 4.0)* | [https://www.indexdata.org/belgium/](https://www.indexdata.org/belgium/) |
| **[Brazil](https://www.indexdata.org/brazil/)** | `83` | `2` | *Brazilian Copyright Act (Law No. 9,610/1998, Art. 8, IV) & Access to Information Act (Law No. 12,527/2011 / Decree No. 8,777/2016)* | [https://www.indexdata.org/brazil/](https://www.indexdata.org/brazil/) |
| **[Japan](https://www.indexdata.org/japan/)** | `55` | `7` | *Japanese Copyright Act (Act No. 48 of 1970), Art. 13 & Government of Japan Standard Terms of Use v2.0 (CC BY 4.0)* | [https://www.indexdata.org/japan/](https://www.indexdata.org/japan/) |
| **[Russia](https://www.indexdata.org/russia/)** | `24` | `2` | *Civil Code of the Russian Federation, Part IV, Art. 1259(6)(1) & Open Government Data Standard* | [https://www.indexdata.org/russia/](https://www.indexdata.org/russia/) |
| **[Sweden](https://www.indexdata.org/sweden/)** | `36` | `3` | *URL 9 § (1960:729) / SFS 2022:818 / CC BY 4.0* | [https://www.indexdata.org/sweden/](https://www.indexdata.org/sweden/) |
| **[China](https://www.indexdata.org/china/)** | `26` | `14` | *PRC Copyright Law Art. 5 & HKSAR Cap. 528 / DATA.GOV.HK Terms* | [https://www.indexdata.org/china/](https://www.indexdata.org/china/) |
| **[Czechia](https://www.indexdata.org/czechia/)** | `33` | `8` | *Act No. 121/2000 Coll. § 3(a) & Act No. 106/1999 Coll. (CC BY 4.0 / Public Domain)* | [https://www.indexdata.org/czechia/](https://www.indexdata.org/czechia/) |
| **[Germany](https://www.indexdata.org/germany/)** | `148` | `5` | *§ 5 UrhG / § 12a EGovG / DNG (Datenlizenz Deutschland dl-de/by-2-0 & CC BY 4.0)* | [https://www.indexdata.org/germany/](https://www.indexdata.org/germany/) |
| **[Denmark](https://www.indexdata.org/denmark/)** | `32` | `9` | *Ophavsretsloven § 9 (LBK nr 1144 af 23/10/2014) / PSI-loven (CC BY 4.0)* | [https://www.indexdata.org/denmark/](https://www.indexdata.org/denmark/) |
| **[Estonia](https://www.indexdata.org/estonia/)** | `16` | `3` | *Estonian Copyright Act § 5(3)-(4), Public Information Act § 3¹ & Riigikogu Open Data Licence* | [https://www.indexdata.org/estonia/](https://www.indexdata.org/estonia/) |
| **[Spain](https://www.indexdata.org/spain/)** | `35` | `8` | *Art. 13 TRLPI (RDL 1/1996) & Law 37/2007 on Re-use of Public Sector Information (RD 1495/2011)* | [https://www.indexdata.org/spain/](https://www.indexdata.org/spain/) |
| **[Israel](https://www.indexdata.org/israel/)** | `128` | `14` | *Copyright Act, 5768-2007, Section 6 (Official Publications) & Data.gov.il Open Government Data License* | [https://www.indexdata.org/israel/](https://www.indexdata.org/israel/) |
| **[Portugal](https://www.indexdata.org/portugal/)** | `4` | `2` | *Law No. 68/2021 (Open Data Principles), Law No. 26/2016 (LADA) & Art. 7 CDADC (Decree-Law No. 63/85)* | [https://www.indexdata.org/portugal/](https://www.indexdata.org/portugal/) |
| **[Singapore](https://www.indexdata.org/singapore/)** | `76` | `10` | *SG Open Data Licence v1.0 / Copyright Act 2021* | [https://www.indexdata.org/singapore/](https://www.indexdata.org/singapore/) |
| **[Netherlands](https://www.indexdata.org/netherlands/)** | `4` | `2` | *Open Government / Statutory Public Sector Reuse Framework* | [https://www.indexdata.org/netherlands/](https://www.indexdata.org/netherlands/) |

## Primary Issuing Authority Archive Hubs (Top 35 by Dossier Volume)

| Issuing Authority | Jurisdiction | Indexed Dossiers | Canonical Authority Archive | Syndication |
| :--- | :--- | :--- | :--- | :--- |
| **[Federal Aviation Administration](https://www.indexdata.org/united-states/federal-aviation-administration/)** | United States | `3,434` | [https://www.indexdata.org/united-states/federal-aviation-administration/](https://www.indexdata.org/united-states/federal-aviation-administration/) | [RSS Feed](https://www.indexdata.org/united-states/federal-aviation-administration/feed/) |
| **[Department of Justice Canada](https://www.indexdata.org/canada/department-of-justice-canada/)** | Canada | `3,418` | [https://www.indexdata.org/canada/department-of-justice-canada/](https://www.indexdata.org/canada/department-of-justice-canada/) | [RSS Feed](https://www.indexdata.org/canada/department-of-justice-canada/feed/) |
| **[General Assembly](https://www.indexdata.org/united-nations/general-assembly/)** | United Nations | `3,014` | [https://www.indexdata.org/united-nations/general-assembly/](https://www.indexdata.org/united-nations/general-assembly/) | [RSS Feed](https://www.indexdata.org/united-nations/general-assembly/feed/) |
| **[Environmental Protection Agency](https://www.indexdata.org/united-states/environmental-protection-agency/)** | United States | `1,877` | [https://www.indexdata.org/united-states/environmental-protection-agency/](https://www.indexdata.org/united-states/environmental-protection-agency/) | [RSS Feed](https://www.indexdata.org/united-states/environmental-protection-agency/feed/) |
| **[Coast Guard](https://www.indexdata.org/united-states/coast-guard/)** | United States | `1,184` | [https://www.indexdata.org/united-states/coast-guard/](https://www.indexdata.org/united-states/coast-guard/) | [RSS Feed](https://www.indexdata.org/united-states/coast-guard/feed/) |
| **[European Commission](https://www.indexdata.org/european-union/european-commission/)** | European Union | `1,021` | [https://www.indexdata.org/european-union/european-commission/](https://www.indexdata.org/european-union/european-commission/) | [RSS Feed](https://www.indexdata.org/european-union/european-commission/feed/) |
| **[National Oceanic and Atmospheric Administration](https://www.indexdata.org/united-states/national-oceanic-and-atmospheric-administration/)** | United States | `905` | [https://www.indexdata.org/united-states/national-oceanic-and-atmospheric-administration/](https://www.indexdata.org/united-states/national-oceanic-and-atmospheric-administration/) | [RSS Feed](https://www.indexdata.org/united-states/national-oceanic-and-atmospheric-administration/feed/) |
| **[European Parliament and Council of the EU](https://www.indexdata.org/european-union/european-parliament-and-council-of-the-eu/)** | European Union | `646` | [https://www.indexdata.org/european-union/european-parliament-and-council-of-the-eu/](https://www.indexdata.org/european-union/european-parliament-and-council-of-the-eu/) | [RSS Feed](https://www.indexdata.org/european-union/european-parliament-and-council-of-the-eu/feed/) |
| **[Transport Canada](https://www.indexdata.org/canada/transport-canada/)** | Canada | `639` | [https://www.indexdata.org/canada/transport-canada/](https://www.indexdata.org/canada/transport-canada/) | [RSS Feed](https://www.indexdata.org/canada/transport-canada/feed/) |
| **[Council of the European Union](https://www.indexdata.org/european-union/council-of-the-european-union/)** | European Union | `624` | [https://www.indexdata.org/european-union/council-of-the-european-union/](https://www.indexdata.org/european-union/council-of-the-european-union/) | [RSS Feed](https://www.indexdata.org/european-union/council-of-the-european-union/feed/) |
| **[Economic and Social Council](https://www.indexdata.org/united-nations/economic-and-social-council/)** | United Nations | `534` | [https://www.indexdata.org/united-nations/economic-and-social-council/](https://www.indexdata.org/united-nations/economic-and-social-council/) | [RSS Feed](https://www.indexdata.org/united-nations/economic-and-social-council/feed/) |
| **[Federal Communications Commission](https://www.indexdata.org/united-states/federal-communications-commission/)** | United States | `527` | [https://www.indexdata.org/united-states/federal-communications-commission/](https://www.indexdata.org/united-states/federal-communications-commission/) | [RSS Feed](https://www.indexdata.org/united-states/federal-communications-commission/feed/) |
| **[Security Council](https://www.indexdata.org/united-nations/security-council/)** | United Nations | `503` | [https://www.indexdata.org/united-nations/security-council/](https://www.indexdata.org/united-nations/security-council/) | [RSS Feed](https://www.indexdata.org/united-nations/security-council/feed/) |
| **[HM Government Legislation](https://www.indexdata.org/united-kingdom/hm-government-legislation/)** | United Kingdom | `501` | [https://www.indexdata.org/united-kingdom/hm-government-legislation/](https://www.indexdata.org/united-kingdom/hm-government-legislation/) | [RSS Feed](https://www.indexdata.org/united-kingdom/hm-government-legislation/feed/) |
| **[Human Rights Bodies](https://www.indexdata.org/united-nations/human-rights-bodies/)** | United Nations | `478` | [https://www.indexdata.org/united-nations/human-rights-bodies/](https://www.indexdata.org/united-nations/human-rights-bodies/) | [RSS Feed](https://www.indexdata.org/united-nations/human-rights-bodies/feed/) |
| **[UN General Assembly (UNGA)](https://www.indexdata.org/united-nations/un-general-assembly-unga/)** | United Nations | `462` | [https://www.indexdata.org/united-nations/un-general-assembly-unga/](https://www.indexdata.org/united-nations/un-general-assembly-unga/) | [RSS Feed](https://www.indexdata.org/united-nations/un-general-assembly-unga/feed/) |
| **[European Investment Bank (EIB)](https://www.indexdata.org/european-union/european-investment-bank-eib/)** | European Union | `418` | [https://www.indexdata.org/european-union/european-investment-bank-eib/](https://www.indexdata.org/european-union/european-investment-bank-eib/) | [RSS Feed](https://www.indexdata.org/european-union/european-investment-bank-eib/feed/) |
| **[Department of the Treasury](https://www.indexdata.org/australia/department-of-the-treasury/)** | Australia | `376` | [https://www.indexdata.org/australia/department-of-the-treasury/](https://www.indexdata.org/australia/department-of-the-treasury/) | [RSS Feed](https://www.indexdata.org/australia/department-of-the-treasury/feed/) |
| **[Department of Finance Canada](https://www.indexdata.org/canada/department-of-finance-canada/)** | Canada | `360` | [https://www.indexdata.org/canada/department-of-finance-canada/](https://www.indexdata.org/canada/department-of-finance-canada/) | [RSS Feed](https://www.indexdata.org/canada/department-of-finance-canada/feed/) |
| **[UN Security Council (UNSC)](https://www.indexdata.org/united-nations/un-security-council-unsc/)** | United Nations | `348` | [https://www.indexdata.org/united-nations/un-security-council-unsc/](https://www.indexdata.org/united-nations/un-security-council-unsc/) | [RSS Feed](https://www.indexdata.org/united-nations/un-security-council-unsc/feed/) |
| **[Food and Drug Administration](https://www.indexdata.org/united-states/food-and-drug-administration/)** | United States | `310` | [https://www.indexdata.org/united-states/food-and-drug-administration/](https://www.indexdata.org/united-states/food-and-drug-administration/) | [RSS Feed](https://www.indexdata.org/united-states/food-and-drug-administration/feed/) |
| **[HM Treasury](https://www.indexdata.org/united-kingdom/hm-treasury/)** | United Kingdom | `293` | [https://www.indexdata.org/united-kingdom/hm-treasury/](https://www.indexdata.org/united-kingdom/hm-treasury/) | [RSS Feed](https://www.indexdata.org/united-kingdom/hm-treasury/feed/) |
| **[Fish and Wildlife Service](https://www.indexdata.org/united-states/fish-and-wildlife-service/)** | United States | `278` | [https://www.indexdata.org/united-states/fish-and-wildlife-service/](https://www.indexdata.org/united-states/fish-and-wildlife-service/) | [RSS Feed](https://www.indexdata.org/united-states/fish-and-wildlife-service/feed/) |
| **[UN Human Rights Council & Treaty Bodies](https://www.indexdata.org/united-nations/un-human-rights-council-treaty-bodies/)** | United Nations | `270` | [https://www.indexdata.org/united-nations/un-human-rights-council-treaty-bodies/](https://www.indexdata.org/united-nations/un-human-rights-council-treaty-bodies/) | [RSS Feed](https://www.indexdata.org/united-nations/un-human-rights-council-treaty-bodies/feed/) |
| **[U.S. House of Representatives](https://www.indexdata.org/united-states/u-s-house-of-representatives/)** | United States | `269` | [https://www.indexdata.org/united-states/u-s-house-of-representatives/](https://www.indexdata.org/united-states/u-s-house-of-representatives/) | [RSS Feed](https://www.indexdata.org/united-states/u-s-house-of-representatives/feed/) |
| **[Energy Department](https://www.indexdata.org/united-states/energy-department/)** | United States | `261` | [https://www.indexdata.org/united-states/energy-department/](https://www.indexdata.org/united-states/energy-department/) | [RSS Feed](https://www.indexdata.org/united-states/energy-department/feed/) |
| **[Internal Revenue Service](https://www.indexdata.org/united-states/internal-revenue-service/)** | United States | `258` | [https://www.indexdata.org/united-states/internal-revenue-service/](https://www.indexdata.org/united-states/internal-revenue-service/) | [RSS Feed](https://www.indexdata.org/united-states/internal-revenue-service/feed/) |
| **[UN Development Programme (UNDP)](https://www.indexdata.org/united-nations/un-development-programme-undp/)** | United Nations | `250` | [https://www.indexdata.org/united-nations/un-development-programme-undp/](https://www.indexdata.org/united-nations/un-development-programme-undp/) | [RSS Feed](https://www.indexdata.org/united-nations/un-development-programme-undp/feed/) |
| **[Nuclear Regulatory Commission](https://www.indexdata.org/united-states/nuclear-regulatory-commission/)** | United States | `224` | [https://www.indexdata.org/united-states/nuclear-regulatory-commission/](https://www.indexdata.org/united-states/nuclear-regulatory-commission/) | [RSS Feed](https://www.indexdata.org/united-states/nuclear-regulatory-commission/feed/) |
| **[Financial Markets Authority (Autorité des marchés financiers - AMF)](https://www.indexdata.org/france/financial-markets-authority-autorit-des-march-s-financiers-amf/)** | France | `217` | [https://www.indexdata.org/france/financial-markets-authority-autorit-des-march-s-financiers-amf/](https://www.indexdata.org/france/financial-markets-authority-autorit-des-march-s-financiers-amf/) | [RSS Feed](https://www.indexdata.org/france/financial-markets-authority-autorit-des-march-s-financiers-amf/feed/) |
| **[United Nations Secretariat](https://www.indexdata.org/united-nations/united-nations-secretariat/)** | United Nations | `197` | [https://www.indexdata.org/united-nations/united-nations-secretariat/](https://www.indexdata.org/united-nations/united-nations-secretariat/) | [RSS Feed](https://www.indexdata.org/united-nations/united-nations-secretariat/feed/) |
| **[Agricultural Marketing Service](https://www.indexdata.org/united-states/agricultural-marketing-service/)** | United States | `190` | [https://www.indexdata.org/united-states/agricultural-marketing-service/](https://www.indexdata.org/united-states/agricultural-marketing-service/) | [RSS Feed](https://www.indexdata.org/united-states/agricultural-marketing-service/feed/) |
| **[Attorney-General's Department](https://www.indexdata.org/australia/attorney-general-s-department/)** | Australia | `184` | [https://www.indexdata.org/australia/attorney-general-s-department/](https://www.indexdata.org/australia/attorney-general-s-department/) | [RSS Feed](https://www.indexdata.org/australia/attorney-general-s-department/feed/) |
| **[Ministry of Housing, Communities and Local Government](https://www.indexdata.org/united-kingdom/ministry-of-housing-communities-and-local-government/)** | United Kingdom | `183` | [https://www.indexdata.org/united-kingdom/ministry-of-housing-communities-and-local-government/](https://www.indexdata.org/united-kingdom/ministry-of-housing-communities-and-local-government/) | [RSS Feed](https://www.indexdata.org/united-kingdom/ministry-of-housing-communities-and-local-government/feed/) |
| **[Centers for Medicare & Medicaid Services](https://www.indexdata.org/united-states/centers-for-medicare-medicaid-services/)** | United States | `179` | [https://www.indexdata.org/united-states/centers-for-medicare-medicaid-services/](https://www.indexdata.org/united-states/centers-for-medicare-medicaid-services/) | [RSS Feed](https://www.indexdata.org/united-states/centers-for-medicare-medicaid-services/feed/) |

*To browse all `739` individual government department, ministry, agency, and multilateral organ archives, visit the **[Indexed Jurisdictions & Issuing Authorities Directory](https://www.indexdata.org/methodology/)**.*

## Dataset Files & Schema

- `regulatory_index_2026.csv` — UTF-8 comma-separated index of all published regulatory dossiers.
- `regulatory_index_2026.jsonl` — Newline-delimited JSON records for programmatic ingestion and LLM/RAG citation pipelines.

| Field | Type | Description |
| :--- | :--- | :--- |
| `document_id` | `string` | Official statutory or registry identifier (e.g., `2026-06947`, `UKSI-2026-142`, `SOR-2026-45`, `CELEX-32026R0815`, `F2026L01394`, `UN-S-RES-2728-2024`, `IE-ACT-2026-37`, `WB-WDS-34442292`, `AT-ERV-1991-52`, `CH-FEDLEX-1993-1798-20250101`, `FI-VTV-28851`, `FR-INFOFI-109684-20120412`, `KR-KIEP-10-11644-KIEP-EAER-2025-29-4-389`, `NO-CRISTIN-2345678`, `OECD-PUB-257230EC-EN`, `FAO-CE2176EN`, `IT-INAPP-5255`, `PH-GPPB-15640`, `PL-PAIH-205192`, `WIPO-60683`, `ZA-BILL-B27-2026`, `IN-SANSAD-1538515`, `BE-SCIENSANO-12770`, `BR-BCB-COPOM-281`, `JP-EGOV-910DBEE5`, `RU-IEP-W4391234567`, `SE-TRV-1993256`, `AT-GOEG-30`, `CN-HK-DATAGOV-cf1f9135-c1c1-4aab-a950-1bd019c20bb4-spec`, `CZ-CNB-W7223661835`, `DE-UBA-123456789-12516`, `DK-DIIS-57737`, `EBA-CELLAR-834F95C1-5FBB-11F1-9AF0-01AA75ED71A1`, `ECA-CELLAR-46AB6960-D410-11F1-9458-01AA75ED71A1`, `ECDC-CELLAR-8E8ABA71-D27C-11F1-9458-01AA75ED71A1`, `EE-RK-MEDIA-261540`, `EEA-RPT-EHRF2130`, `EFSA-CELLAR-8F30D7BB-BE06-11F1-9AAE-01AA75ED71A1`, `EIB-DOC-principles-impact-management-en`, `EIOPA-CELLAR-BFF84DAF-742C-11F1-9800-01AA75ED71A1`, `EMA-DOC-scientific-guideline-investigation-chiral-active-substances`, `ES-DEFENSOR-5733`, `ESMA-PRIII-4773044`, `IL-IIA-EN-23395`, `ILO-CR-10.54394-000343494`, `PT-OA-W4415628910`, `SG-MINLAW-ANNEX-B-SUMMARY-OF-KEY-REFORMS`, `UK-PARL-OE-18207`, `UNCTAD-ASYCUDA-MEDIA-12520`, `UNDP-UNDL-4131203`, `UNHCR-NADA-1573`, `US-DOT-ROSAP-94173`) |
| `jurisdiction` | `string` | Issuing sovereign jurisdiction or multilateral classification |
| `authority` | `string` | Issuing government department, ministry, agency, or international institution |
| `publication_date` | `string` | Official publication or enactment date (`YYYY-MM-DD`) |
| `page_count` | `integer` | Verified pagination of the unabridged source PDF dossier |
| `language` | `string` | Primary document language (`English`) |
| `title` | `string` | Official statutory or regulatory title |
| `canonical_url` | `string` | Direct permalink to the executive briefing and PDF dossier on [indexdata.org](https://www.indexdata.org) |

---

*Maintained autonomously by [Index Data](https://www.indexdata.org).*
