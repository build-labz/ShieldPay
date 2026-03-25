# ShieldPay – Confidential Enterprise Payroll & Stablecoin Payment Platform

**Privacy-by-design white-label solution for confidential USDC payroll and treasury payments on Fhenix.**

## Overview

ShieldPay enables enterprises to deploy their own **dedicated, fully branded** confidential payroll system where **all sensitive data** (salaries, bonuses, recipient lists, and payment schedules) remains encrypted on-chain at all times using **Fully Homomorphic Encryption (FHE)**.

No more exposing employee salaries on public block explorers.  
No more reliance on trusted intermediaries or off-chain databases for privacy.  
Just true end-to-end confidentiality combined with seamless usability.

## Core Features

- **Dedicated White-Label Deployment** — Each company gets its own isolated, fully branded instance (custom logo, colors, domain, and UI)
- **Encrypted Batch Payments** — Admin uploads employee/contractor lists + amounts securely
- **Recurring & One-time Payments** — Monthly salaries, bonuses, contractor payouts
- **Employee Portal** — Recipients see and claim only their own encrypted balance
- **Selective Unshielding** — Claim and unshield any portion of USDC when needed
- **True Privacy** — Even the company admin cannot view individual salaries without permission

## Powered By

- **Fhenix** — Encrypted compute and state (`euint256`)
- **Privara SDK + ReineiraOS** — Protocol-native confidential stablecoin rails, programmable escrows, and compliant treasury movements (newly integrated into the Fhenix ecosystem)
- **React + CoFHE.js** — Client-side encryption/decryption for a smooth, private user experience

## Why ShieldPay?

Traditional payroll tools treat privacy as an afterthought.  
ShieldPay is **privacy-native** from the protocol level and designed specifically for enterprise needs — data isolation, full branding control, and GDPR/CCPA compliance.

Perfect for:
- Mid-to-large enterprises moving treasury on-chain
- Web3 companies and DAOs making private contributor payments
- HR/fintech platforms that want to embed confidential payment rails

## Project Concept

For the full detailed concept and architecture, see **[CONCEPT.md](./CONCEPT.md)**.

## Tech Stack (Planned)

- Blockchain: Fhenix (EVM-compatible with FHE)
- Payments: Privara SDK + ReineiraOS
- Frontend: React + TypeScript + CoFHE.js
- Smart Contracts: Solidity + Hardhat

## Status

- Currently in **AKINDO Private By Design dApp Buildathon** (Wave 1 – Ideation)
- Actively building toward a production-ready enterprise solution

---

**Built with 🔥 and a strong belief that privacy should be the default in Web3.**
