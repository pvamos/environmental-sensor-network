# References and research outputs

This file is the project-level bibliography and research-output index for the
`environmental-sensor-network` umbrella repository.

The umbrella repository itself is currently a documentation, architecture and
research-output index and **does not have its own Zenodo DOI**. The original BSc
research should be cited via the thesis DOI below. Individual software
components should be cited via their version-specific Zenodo software DOIs.

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

The six project-owned software components were archived as independently versioned `v1.0.0` research-software artifacts.

| Repository | Role | Version DOI | All-versions DOI | Published |
|---|---|---|---|---|
| [`envsensor-kafka-smt`](https://github.com/pvamos/envsensor-kafka-smt) | Kafka Connect protobuf transformation | [`10.5281/zenodo.22883426`](https://doi.org/10.5281/zenodo.22883426) | [`10.5281/zenodo.22883425`](https://doi.org/10.5281/zenodo.22883425) | 2026-09-21 |
| [`vernemq-enrich-msg`](https://github.com/pvamos/vernemq-enrich-msg) | MQTT protobuf enrichment plugin | [`10.5281/zenodo.22883989`](https://doi.org/10.5281/zenodo.22883989) | [`10.5281/zenodo.22883988`](https://doi.org/10.5281/zenodo.22883988) | 2026-09-22 |
| [`esp32-envsensor-mqtt`](https://github.com/pvamos/esp32-envsensor-mqtt) | Environmental sensor-node firmware | [`10.5281/zenodo.22884125`](https://doi.org/10.5281/zenodo.22884125) | [`10.5281/zenodo.22884124`](https://doi.org/10.5281/zenodo.22884124) | 2026-09-22 |
| [`alpine-k3s`](https://github.com/pvamos/alpine-k3s) | k3s / Longhorn infrastructure automation | [`10.5281/zenodo.22884215`](https://doi.org/10.5281/zenodo.22884215) | [`10.5281/zenodo.22884214`](https://doi.org/10.5281/zenodo.22884214) | 2026-09-22 |
| [`kafka-connect-image`](https://github.com/pvamos/kafka-connect-image) | Reproducible Kafka Connect runtime | [`10.5281/zenodo.22884350`](https://doi.org/10.5281/zenodo.22884350) | [`10.5281/zenodo.22884349`](https://doi.org/10.5281/zenodo.22884349) | 2026-09-22 |
| [`kafka-cluster`](https://github.com/pvamos/kafka-cluster) | Environmental data platform deployment | [`10.5281/zenodo.22884473`](https://doi.org/10.5281/zenodo.22884473) | [`10.5281/zenodo.22884472`](https://doi.org/10.5281/zenodo.22884472) | 2026-09-22 |

Use the **version DOI** when citing the exact `v1.0.0` software snapshot associated with this research. The all-versions DOI identifies the software across Zenodo releases and resolves to the latest archived version.

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
