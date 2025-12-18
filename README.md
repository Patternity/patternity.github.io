# Patternity

Official website of the **Patternity** organization.

Patternity focuses on research and design of protocol-level systems
for behavioral consensus and off-chain verification.

The first published protocol by Patternity is **Proof-of-Game (PoG)**.

---

## Website

The site is publicly available at:

https://patternity.github.io/

It is deployed via **GitHub Pages** and served as a static website.

---

## Proof-of-Game (PoG)

Proof-of-Game (PoG) is a consensus protocol for proving the
**uniqueness of behavioral processes**.

PoG does **not** prove:
- human identity
- resistance to automation
- skill, performance, or outcomes
- economic value or incentives

The canonical PoG specification is maintained in a separate repository:

https://github.com/Patternity/proof-of-game

Current status:
- **Protocol:** PoG v1.0
- **Status:** Draft (consensus-complete)
- **Implementation:** UE reference implementation not yet published

---

## Repository Scope

This repository contains:
- the source code of the Patternity public website
- static content describing Patternity and PoG
- deployment configuration for GitHub Pages

It does NOT contain:
- protocol specifications
- SDKs or UE implementations
- smart contracts
- tokenomics or incentive mechanisms

---

## Development

This website is implemented as a static React application
and deployed automatically via GitHub Actions.

Typical local workflow:

```bash
npm install
npm run dev
````

Production build:

```bash
npm run build
```

---

## License

Website source code is provided under the repository license,
unless stated otherwise.

Protocol specifications are licensed separately
in their respective repositories.

---

© Patternity
