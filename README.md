[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on005935-blue)](https://doi.org/10.82901/nemar.on005935)

<!-- nemar:provenance -->
## Provenance

This dataset is mirrored on NEMAR from OpenNeuro.

- Source: [ds005935](https://openneuro.org/datasets/ds005935)
- DOI: [10.18112/openneuro.ds005935.v1.0.0](https://doi.org/10.18112/openneuro.ds005935.v1.0.0)

## Data notes

- fNIRS recordings of 21 participants observing and executing easy and difficult actions (Li et al. 2020, Scientific Reports 10:10965, doi:10.1038/s41598-020-67327-5).
- Duplicated run: all 8,501 rows and 120 channels of `sub-6110/ses-01/nirs/sub-6110_ses-01_task-MirrorNeuron_run-3_nirs.snirf` are bit-identical to 0-based rows 24-8,524 of `sub-6110/ses-01/nirs/sub-6110_ses-01_task-MirrorNeuron_run-2_nirs.snirf` (1-based samples 25-8,525 of 8,550); the release assigns different run labels. Consider excluding the affected channels or recordings.
