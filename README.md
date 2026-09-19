# Merismos™ Installer Distribution Vertical

*Empowering stakeholders to synergistically disaggregate airline group
booking PDFs, at scale, going forward.*

## Executive Summary

Merismos takes one (1) PDF containing twenty (20) passengers all
mysteriously named **"Tba Tba"** and transforms it into twenty (20)
individual PDFs containing their actual names. This is, we are told,
"groundbreaking."

This repository is a **pure download surface**. The source code lives in
a private repository elsewhere, because nothing says "enterprise-ready"
like an air-gapped monorepo nobody else can read. What you get here is
the compiled output — installers, and nothing but installers — leveraged
directly from our world-class two-person build pipeline (one person,
one AI, mutually accountable).

## Core Value Propositions

- **Best-in-class QR/barcode fidelity.** Pixel-perfect, so the airline
  counter doesn't look at you funny.
- **Zero-touch onboarding.** Drag PDF in. Tickets out. No workshops
  required.
- **Data sovereignty by default.** Everything runs on-device. Nothing
  phones home, mostly because nobody built that in.
- **Vertically integrated licensing.** A five-day trial, then a license
  key bound to one device, because we haven't figured out floating
  licenses and frankly may never.

## Deliverables

| Platform | Artifact | Compliance Posture |
|---|---|---|
| Windows (x64) | `Merismos_X.Y.Z_x64-setup.exe` / `Merismos_X.Y.Z_x64_en-US.msi` | Unsigned. SmartScreen will have opinions. |
| macOS (Apple Silicon) | `Merismos_X.Y.Z_aarch64.dmg` | Untested by any committee |
| macOS (Intel) | `Merismos_X.Y.Z_x64.dmg` | Same energy |

Grab the latest ones from the [Releases](../../releases) page. Version
numbers increment roughly whenever something breaks and then gets
fixed, which is to say: frequently, and with confidence.

## Governance & Assurance

- **SOC 2 Type:** None.
- **ISO Certification:** None.
- **Uptime SLA:** The repo either has a release or it doesn't.
- **Roadmap:** Yes.

## Support

Raise it with the author. There is no ticketing system for the ticket
app — that would be, at minimum, poetic malpractice.
