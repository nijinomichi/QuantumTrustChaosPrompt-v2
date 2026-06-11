# QuantumTrustChaosPrompt v2

> **Clean successor** to [`nijinomichi/QuantumTrustChaosPrompt`](https://github.com/nijinomichi/QuantumTrustChaosPrompt)
> — migrated 2026-06-10 (decision) to resolve a CI-blocking long-path issue.

## What is this?

An implementation of **QRA (Quantum Resonance Architecture) v1.0** —
a Double-Slit → CoSlit³ (S/D/Y) protocol for AI-assisted creative generation.

Observation changes outcomes; failures are archived and reframed into value.

## Core files

| File | Purpose |
|------|---------|
| `QRA-v1.0.yaml` | QRA v1.0 protocol spec (S / D / Y phases) |
| `rho_Ck.json` | Scoring weights (ρ = 0.62, Cₖ = 0.38) |
| `requirements.txt` | Python dependencies |
| `docs/PROVENANCE.md` | Migration history and provenance record |
| `docs/archive/banana-moon-nft-caption.md` | BananaMoon NFT provenance text |

## Philosophy

> ⚠️ This repo is intentionally unfinished.
> Failures are not deleted — they are archived and reframed.
>
> *Beauty(α) = ∫ L_beauty(x^μ, θ^a) d⁴x dθ*

Related projects: **RadicanTrust** · **CoPhelia³** · **BananaMoon**

## Provenance

This repository was created as a clean successor because the original contained
a directory with a filename exceeding Linux's 255-byte limit (a BananaMoon NFT caption),
blocking `actions/checkout@v4`. See [`docs/PROVENANCE.md`](docs/PROVENANCE.md) for full details.

Original repo (read-only / archaeological evidence):
https://github.com/nijinomichi/QuantumTrustChaosPrompt

---

Repository license: see [`LICENSE`](LICENSE).  
Conceptual/artistic framework: Sou Hashiguchi × Ara-Philia³ × CoPhelia³.
