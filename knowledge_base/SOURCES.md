# Knowledge base sources

The documents below were loaded into the RAG vector store. They are not redistributed in this repository. Download them from the official sources.

## 3GPP / ETSI

Available free of charge from the [3GPP portal](https://www.3gpp.org/specifications-technologies) or [ETSI](https://www.etsi.org/standards-search).

| Spec | Version | Title |
|---|---|---|
| TS 33.501 | 18.9.0 | Security architecture and procedures for 5G system |
| TS 33.511 | 17.1.0 | SCAS for the gNodeB (gNB) network product class |
| TS 33.523 | 18.2.0 | SCAS; Split gNB product classes |
| TR 33.926 | 17.4.0 | SCAS threats and critical assets in 3GPP network product classes |
| TS 38.300 | 17.0.0 | NR; Overall description; Stage-2 |
| TS 38.401 | 16.3.0 | NG-RAN; Architecture description |
| TS 38.470 | 18.4.0 | NG-RAN; F1 general aspects and principles |
| TS 38.472 | 18.1.0 | NG-RAN; F1 signalling transport |

## O-RAN Alliance (WG11 Security)

Available after accepting the O-RAN Adopter License at [specifications.o-ran.org](https://specifications.o-ran.org/specifications).

| Document | Version |
|---|---|
| O-RAN.WG11.TS.SecProtSpec (Security Protocols Specification) | R004-v11.00, R004-v13.00 |
| O-RAN.WG11.TS.SRCS (Security Requirements and Controls) | R004-v13.00 |
| O-RAN.WG11.TS.STS (Security Test Specifications) | R004-v11.00 |
| O-RAN.WG11.TR.Threat-Modeling | R004-v05.00, R004-v07.00 |
| O-RAN.WG11.TR.AIML-Security-Analysis | R004-v04.00 |
| O-RAN.WG11.TR.Certificate-Management-Framework | R004-v05.00 |
| O-RAN.WG11.TR.O-CLOUD-Security | R004-v08.00 |
| O-RAN.WG11.TR.OAuth2.0-Security | R004-v06.00 |
| O-RAN.WG11.TR.Open-FH-Security | R004-v05.00 |
| O-RAN.WG11.TR.PQC-Security | R004-v01.00 |
| O-RAN.WG11.TR.SCM | R004-v01.00 |
| O-RAN.WG11.TR.SMO-Security-Analysis | R004-v06.00, R004-v07.00 |
| O-RAN.WG11.TR.Security-Near-RT-RIC-xApps | R004-v06.00 |
| O-RAN.WG11.TR.ZTA | R004-v04.00 |
| O-RAN.WG11.TR.AppLCM-Security | R004-v04.00 |
| O-RAN.WG11.TR.CSM-Security | R004-v01.00 |
| O-RAN.WG11.TR.O-RUCUM | R004-v04.00 |
| O-RAN.WG11.Security-Log-Management-TR | R004-v05.00 |
| O-RAN.WG11.SharedORU-Security-Analysis-TR | R004-v06.00 |
| O-RAN.SFG.Non-RT-RIC-Security-TR | v01.00 |

## Open-source RAN code

| Project | Part used | License |
|---|---|---|
| [OpenAirInterface](https://gitlab.eurecom.fr/oai/openairinterface5g) | `openair2/` (RRC, E1AP, F1/X2/XN AP, GNB_APP, LAYER2, ...) and example configs (`targets/PROJECTS/GENERIC-NR-5GC/CONF`, `ci-scripts/conf_files`) | OAI Public License v1.1 |
| [srsRAN Project](https://github.com/srsran/srsRAN_Project) | Security-related files under `apps/`, `include/`, `lib/`, `tests/` | AGPL-3.0 |
