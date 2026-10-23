# Paper DOI Template

[![DOI placeholder](https://img.shields.io/badge/DOI-placeholder%20pending%20release-lightgrey?style=flat-square)](https://github.com/DeontewattsV1/paper-doi-template/releases)
[![Release](https://img.shields.io/github/v/release/DeontewattsV1/paper-doi-template?include_prereleases&style=flat-square)](https://github.com/DeontewattsV1/paper-doi-template/releases)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey?style=flat-square)](LICENSE)
[![Hub](https://img.shields.io/badge/catalog-dummy%20decoy%20hub-0B3D91?style=flat-square)](https://github.com/DeontewattsV1/dummy-decoy-scientific-hub)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--8586--3650-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0005-8586-3650)

One manuscript. One repository. One Zenodo DOI family.

## Author identity and research directory

- **Author:** Deonté O'dell Watts / GoodShyt Group Inc. (GitHub: [DeontewattsV1](https://github.com/DeontewattsV1), ORCID [0009-0005-8586-3650](https://orcid.org/0009-0005-8586-3650))
- **ORCID:** https://orcid.org/0009-0005-8586-3650
- **Researcher webpage:** https://deonte-watts-ietf-identity.vercel.app/
- **IETF-compatible Linkset (RFC 9264):** https://deonte-watts-ietf-identity.vercel.app/linkset-research.json
- **Schema.org JSON-LD:** https://deonte-watts-ietf-identity.vercel.app/author.jsonld

The linked professional profiles are author-declared; they are not verified account-ownership or IETF endorsements. The public research Linkset excludes payment profiles. This template is not an Internet-Draft and publishing metadata here does not authorize an IETF submission.

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

## DOI badge

The grey badge at the top is a placeholder. It links to this repository's Releases page and stays that way until a spawned paper receives a Zenodo concept DOI.

`CONCEPT` in the examples below is a placeholder token. `https://doi.org/10.5281/zenodo.CONCEPT` returns 404, and the Zenodo badge SVG for that token has no record behind it. Keep both examples in this template. In a spawned paper, after Zenodo harvest, replace the pending badge and substitute the minted numeric concept DOI for every `CONCEPT` token.

```markdown
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.CONCEPT.svg)](https://doi.org/10.5281/zenodo.CONCEPT)
```

Colored Shields fallback, still with the `CONCEPT` placeholder:

```markdown
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.CONCEPT-blue?style=flat-square)](https://doi.org/10.5281/zenodo.CONCEPT)
```
