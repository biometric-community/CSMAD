# CSMAD

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FCSMAD-181717?logo=github)](https://github.com/biometric-community/CSMAD)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.idiap.ch/en/scientific-research/data)

**CSMAD** — tbiom catalog packaging for `csmad` (face-pad; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/CSMAD
- **Upstream source**: https://www.idiap.ch/en/scientific-research/data
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `csmad` |
| Category | `face-pad` |
| Access | `register` |
| Upstream homepage | https://www.idiap.ch/en/scientific-research/data |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Custom Silicone Mask Attack Dataset (Idiap).

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/CSMAD.git
cd CSMAD
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_csmad.sh
```

Place licensed archives under `projects/datasets/csmad/` (gitignored).

## Dataset structure

```text
CSMAD/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.idiap.ch/en/scientific-research/data
- Packaging: https://github.com/biometric-community/CSMAD/issues
