# Paper DOI Template

[![DOI pending](https://img.shields.io/badge/DOI-pending%20release-lightgrey?style=flat-square)](https://github.com/DeontewattsV1/paper-doi-template/releases)
[![Release](https://img.shields.io/github/v/release/DeontewattsV1/paper-doi-template?include_prereleases&style=flat-square)](https://github.com/DeontewattsV1/paper-doi-template/releases)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey?style=flat-square)](LICENSE)
[![Hub](https://img.shields.io/badge/catalog-dummy%20decoy%20hub-0B3D91?style=flat-square)](https://github.com/DeontewattsV1/dummy-decoy-scientific-hub)
[![ORCID](https://img.shields.io/badge/ORCID-Deonte%20Watts-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/)

One manuscript. One repository. One Zenodo DOI family.

Use this repository as the **GitHub template** for every scientific paper that should receive its own DOI. The public index lives in [dummy-decoy-scientific-hub](https://github.com/DeontewattsV1/dummy-decoy-scientific-hub) so this pattern does not store twenty manuscripts in one tree.

## Spawn

1. Click **Use this template** (enable Template repository in Settings if the button is missing).
2. Name the new repo `paper-<slug>` and keep it **public** if you want a Zenodo DOI.
3. Replace title/author/ORCID in `CITATION.cff` and `.zenodo.json`.
4. Put the manuscript in `manuscript/`, figures in `figures/`, dataset pointers in `data/`.
5. Enable the new repo at https://zenodo.org/account/settings/github/
6. Publish GitHub Release `v1.0.0`.
7. Paste the minted concept DOI into the README badge and the hub catalog.

From chat on the connected GitHub account:

> Spawn a new paper repository from paper-doi-template titled TITLE with slug paper-SLUG. Add a catalog row to dummy-decoy-scientific-hub.

After Zenodo harvest, replace the pending badge with:

```markdown
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.CONCEPT.svg)](https://doi.org/10.5281/zenodo.CONCEPT)
```

Colored Shields fallback:

```markdown
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.CONCEPT-blue?style=flat-square)](https://doi.org/10.5281/zenodo.CONCEPT)
```
