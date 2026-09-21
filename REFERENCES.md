# References and research outputs

This file is the project-level bibliography and research-output index for the
`environmental-sensor-network` umbrella repository.

The umbrella repository itself is currently a documentation, architecture and
research-output index and **does not have its own Zenodo DOI**. The original BSc
research should be cited via the thesis DOI below. Individual software
components should be cited via their version-specific software DOIs after their
archival releases are published.

## Published research outputs

### BSc thesis

**Vámos, Péter (2026).** *Környezeti paraméterek mérése a tudomány és technológia fejlődésének tükrében – Egy skálázható szenzorhálózat megvalósításának tanulságai.*

- Type: BSc thesis
- DOI: `10.5281/zenodo.22843091`
- Zenodo concept DOI: `10.5281/zenodo.22843090`
- Role: canonical scholarly publication for the original 2026 BSc research

### Public presentation

**Vámos, Péter (2026).** *Galileitől a MEMS szenzorig – A környezeti paraméterek mérésének fejlődése.* Planetology Esték, 2026-02-23.

- Type: presentation
- DOI: `10.5281/zenodo.22869061`
- Relationship: supplement to the BSc thesis

## Research software

The following component repositories are being prepared as independently
versioned research-software artifacts.

| Repository | Role | Planned archival release | Software DOI |
|---|---|---|---|
| [`esp32-envsensor-mqtt`](https://github.com/pvamos/esp32-envsensor-mqtt) | Environmental sensor-node firmware | `v1.0.0` | pending |
| [`alpine-k3s`](https://github.com/pvamos/alpine-k3s) | k3s / Longhorn infrastructure automation | `v1.0.0` | pending |
| [`kafka-cluster`](https://github.com/pvamos/kafka-cluster) | Environmental data platform deployment | `v1.0.0` | pending |
| [`vernemq-enrich-msg`](https://github.com/pvamos/vernemq-enrich-msg) | MQTT protobuf enrichment plugin | `v1.0.0` | pending |
| [`envsensor-kafka-smt`](https://github.com/pvamos/envsensor-kafka-smt) | Kafka Connect protobuf transformation | `v1.0.0` | pending |
| [`kafka-connect-image`](https://github.com/pvamos/kafka-connect-image) | Reproducible Kafka Connect runtime | `v1.0.0` | optional DOI / pending decision |

After each Zenodo software release is created, replace `pending` with the
version-specific DOI and update the corresponding component repository,
`README.md`, `CITATION.md`, and this project-level bibliography.

## Planned dataset

**Extended environmental sensor network dataset, 2026**

- Type: dataset
- DOI: pending
- Status: planned
- Scope: continued measurements beyond the measurement subset analysed in the submitted BSc thesis
- Publication requirements: pseudonymisation, data dictionary, provenance,
  checksums, and a reproducible transformation/anonymisation script

## Planned analysis publication

A new statistical / data-science analysis based on the extended dataset is
planned as an independent research output rather than a republication of the
BSc thesis.

Potential topics include:

- sensor agreement and systematic bias;
- calibration and drift;
- anomaly detection;
- microclimate event identification;
- clustering and classification;
- time-series prediction;
- comparison of statistical and machine-learning methods.

## Update policy

Update this file whenever a new DOI-backed project output is published. Do not
create placeholder DOIs and do not assign a DOI to the umbrella repository
merely to increase the number of archived objects.

If this repository later evolves into a substantial executable research
compendium with orchestration, reproducibility scripts and stable research
artifacts of its own, its archival status can be reconsidered separately.
