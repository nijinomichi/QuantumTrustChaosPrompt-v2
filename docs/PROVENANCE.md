# Provenance — QuantumTrustChaosPrompt-v2

## Why This Repository Exists

This repository (`nijinomichi/QuantumTrustChaosPrompt-v2`) is a clean successor
to `nijinomichi/QuantumTrustChaosPrompt`, which is preserved as
**archaeological evidence** and must not be force-pushed or modified.

The original repository contains an abnormal Git object whose path name encodes
an entire BananaMoon NFT caption as a nested directory structure
(Git tree SHA: `1b866408997e04d77c4d00416944d3a040346047`).
This path exceeds the Linux 255-byte filename limit and permanently blocks
`actions/checkout@v4` with:

```
error: unable to create file # 🍌🌛 BananaMoon Quantum NFT 🌛🍌 ... : File name too long
```

## Source Repository

| Item | Value |
|------|-------|
| Source repo | `nijinomichi/QuantumTrustChaosPrompt` |
| Source ref (HEAD at migration) | `a092d5755f8a6edb407040a787ec263bb940995b` |
| G2 CI commit | `f704b7dadc10f9eb4b4c43eb414699543d036ed0` |
| G2 archive commit | `7c5950d3db30734c5f8d6743f13e570f2cb39d31` |
| Abnormal path tree SHA | `1b866408997e04d77c4d00416944d3a040346047` |
| Migration date | 2026-06-10 JST |

## Archaeological Preservation Policy

- The original repository is **read-only**. No force-push. No `git filter-repo`.
- G1 repair: `nijinomichi/-QACC-IYQ2025-` — `verified_completed`
- G2 status on original: `implemented_but_blocked` (permanent, by design)
- This v2 repository is where CI verification proceeds from Phase 4 onward.

## What Was Migrated (Phase 3 — Initial Commit)

| File | Source SHA | Action |
|------|-----------|--------|
| `LICENSE` | `f78ce1e9555596af29a8068cdb01b64459746e5a` | copied verbatim |
| `QRA-v1.0.yaml` | `bf00e173cb33c8ce39c36b8f620129628b80e2b4` | copied verbatim |
| `rho_Ck.json` | `94888d66fca24e39e92cd482044882b1751bae89` | copied verbatim |
| `requirements.txt` | `88f291d7362d26f9534905045212dee92532a8c6` | copied verbatim |
| `docs/archive/banana-moon-nft-caption.md` | `283c4f6700ea94fa9e81b3cbcf5428185bff180d` | copied verbatim |
| `docs/PROVENANCE.md` | *(this file)* | new — created for v2 |
| `README.md` | *(rewritten for v2)* | rewritten clean successor version |

## What Was Intentionally Excluded

| File | Reason | Deferred To |
|------|--------|-------------|
| `.github/workflows/ci.yml` | Phase separation: CI introduced in Phase 4 only | Phase 4 |
| `NFT` | Content not yet reviewed | Phase 3 extended |
| `QuantumArt_News` | Content not yet reviewed | Phase 3 extended |
| `notebooks/sandbox.ipynb` | Empty placeholder (1 B); Supabase/Colab scope | Phase 6 (G6) |
| Abnormal long-path directory | Root cause of CI blocker; never to be imported | permanent exclude |

## BananaMoon Provenance Chain

The BananaMoon NFT caption text, originally embedded as an abnormal directory
path, has been recovered and preserved at:

`docs/archive/banana-moon-nft-caption.md`
(SHA: `283c4f6700ea94fa9e81b3cbcf5428185bff180d`)

The caption evidence is preserved here for archaeological continuity.
For authoritative NFT metadata including CID and on-chain references,
refer to the G5 Closure record in the BananaMoon / QuantumTrust Space.

## Continuity

Git history is **not** carried over from the source repository.
Provenance is maintained exclusively via this document and the permanent
link to the archaeological source repository above.
