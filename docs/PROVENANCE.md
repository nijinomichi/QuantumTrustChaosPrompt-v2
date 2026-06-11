# PROVENANCE: QuantumTrustChaosPrompt-v2

## Origin

This repository is a **clean successor** to `nijinomichi/QuantumTrustChaosPrompt`.

- **Source repository:** https://github.com/nijinomichi/QuantumTrustChaosPrompt
- **Source HEAD at migration:** `a092d5755f8a6edb407040a787ec263bb940995b`
- **Migration decision date:** 2026-06-10 JST
- **Migration execution date:** pending first commit
- **Migration type:** Curated file-by-file copy (no git history transfer)

The original repository is preserved as **archaeological evidence** and must not be
edited, force-pushed, or deleted.

---

## Why a clean successor?

The original repository contains a directory whose name is the full text of a
BananaMoon NFT caption. This path exceeds the Linux 255-byte filename limit and
causes `actions/checkout@v4` to fail with:

```
fatal: cannot create directory: File name too long
```

Git tree SHA of the abnormal object:
`1b866408997e04d77c4d00416944d3a040346047`

G2 archive commit (text content preserved in normal filename):
`7c5950d3db30734c5f8d6743f13e570f2cb39d31`

---

## What was migrated (Phase 3)

| File | Source SHA | Action |
|------|-----------|--------|
| `LICENSE` | `f78ce1e9` | copy verbatim |
| `QRA-v1.0.yaml` | `bf00e173` | copy verbatim |
| `rho_Ck.json` | `94888d66` | copy verbatim |
| `requirements.txt` | `88f291d7` | copy verbatim |
| `docs/archive/banana-moon-nft-caption.md` | `283c4f67` | copy verbatim |
| `docs/PROVENANCE.md` | — | new file (this document) |
| `README.md` | `260fb029` (original) | rewritten for v2 |

---

## What was intentionally excluded

| Path | Reason | Status |
|------|--------|--------|
| Abnormal long-path directory (`# 🍌🌛 BananaMoon...`) | Root cause of checkout failure — Linux 255-byte limit exceeded | permanent exclude |
| `.github/workflows/ci.yml` | Deferred to Phase 4 (separate commit) | deferred |
| `NFT` | Content review pending | deferred |
| `QuantumArt_News` | Content review pending | deferred |
| `notebooks/sandbox.ipynb` | Empty placeholder (1 B); no migration value | excluded |

---

## BananaMoon NFT Content Preservation

The text content of the abnormal-path directory has been preserved at:
`docs/archive/banana-moon-nft-caption.md` (SHA: `283c4f6700ea94fa9e81b3cbcf5428185bff180d`)

This file carries the provenance chain of the BananaMoon NFT concept into v2
without re-introducing the path length problem.

---

## Phase roadmap

| Phase | Scope | Status |
|-------|-------|--------|
| Phase 3 | Clean repo migration (core files) | ← this commit |
| Phase 4 | CI workflow (`.github/workflows/ci.yml`) | next |
| Phase 5 | NFT / QuantumArt_News (after content review) | pending |
| Phase 6 | Supabase / Colab runtime (`notebooks/`) | future |
