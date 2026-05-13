# Starphire

*Your life, your context, your AI.*

---

## What this is

Three layers stacked.

**The substrate.** An encrypted, normalized, entity-aware archive of a user's full digital life across sources. Live API where it exists, export pipeline where it doesn't. Encrypted client-side — the server cannot read content.

**The generation surface.** Where the user describes what they want and the platform composes a program against their specific context that produces the requested output. Year-in-Review, Felton-style annual reports, Brief-Me, On-This-Day, persistent monitors. Every artifact is an agent; the user describes the outcome, the platform composes it.

**The personal AI credential.** The long-term form factor. Every consumer interaction with AI will eventually want to be personalized — a coffee shop's ordering system, a doctor's office, a rental car, a bookstore's recommendation engine. The only way that personalization works without becoming dystopian is through a user-controlled credential.

Three things must exist together for it to function: a persistent personal context layer (the substrate), a standard for scoped, revocable, time-bounded access to that context, and distribution across enough surfaces that authorized requests become normal. Starphire holds the first today. The second and third are the longer game.

The historical pattern is clear. Apple Pay became infrastructure for payments. Sign In With Apple became infrastructure for identity. Plaid became infrastructure for financial data. The personal AI context layer is potentially larger than all of them combined — the surface area of "places that want personalized AI experiences" is broader than payments, identity, and financial data put together.

Only a consumer product with encryption-first architecture and a clean revenue model can credibly become the trusted issuer of this credential. The labs cannot — their business models require server-side data access. Apple cannot fully — it's scoped to Apple devices and Apple-approved partners. Google will not — it conflicts with their advertising substrate.

That position is what Starphire is building toward.

---

## Milestones shipped

- **M10** — Android skeleton with email + passphrase auth, crypto parity
- **M11** — Android timeline view (live event decryption on physical device)
- **M12** — Per-event detail on Android
- **M13** — Android SMS + Calendar ingestion
- **M14** — Photos with file content (5 phases: cross-platform blob crypto, Android gallery ingestion, photo rendering, background sync, observation)
- **M15** — Generic Google Takeout pipeline (YouTube watch history as first consumer)
- **M16** — Maps Timeline via device-side Android export (pivoted from Takeout when investigation revealed Google's December 2024 cloud migration of Location History data)

Each milestone tagged on origin (`milestone-14-photos-with-file-content`, `milestone-15-google-takeout-pipeline`, etc.) in the private production repo.

---

## Strategy

Three things have rapidly commoditized in the AI stack: foundation models, tool-calling protocols, generic agents.

What has not commoditized — and structurally cannot — is the persistent, structured, encrypted, multi-year archive of a specific user's digital life. That archive is the substrate. Whoever owns the substrate owns the position everything else in the AI stack eventually integrates with.

The major AI labs cannot occupy this position. Their business models depend on server-side data access that user-controlled context forbids. The consumer Context lane is structurally open for 12–18 months before category positioning hardens.

Starphire is a play for that lane.

Full strategic framing: [The Codex Playbook](https://starphire.xyz) — available on the website.

---

## Visual identity

Considered editorial dark register. Fraunces (display + editorial moments) + IBM Plex Sans (UI) + IBM Plex Mono (data labels). Single ice-blue accent deployed as a wax-seal — once per surface. Generous margins, tabular numerals, rule-based separation, no drop shadows, no gradients.

Reference points: Linear's restraint, Anthropic's editorial discipline, Read.cv in dark mode, late-night editorial documents.

Not: warm-charcoal palettes, neon accents, glassmorphism, glow shadows, Linear-cold tech, generic AI product aesthetics.

---

## A note on naming

This repository (and the public-facing brand) is **Starphire**. The internal project name during development was **Codex** — that name persists in the private production repo's history, package names (`@codex/desktop`, `@codex/parsers`, etc.), and in some references within `ARCHITECTURE.md`. The two names refer to the same project. Starphire is the consumer-facing brand; Codex is the engineering codename.

---

## Status

Active development. Submitting to a16z Speedrun May 2026.

Production codebase is private. Reviewer access available on request.

---

## Contact

starphire.xyz
