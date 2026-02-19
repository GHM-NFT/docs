# Web Functionality Handover (Codex) — v1

## Two-site model
### Story Hub (public, SEO)
Lore, galleries, email capture, drop calendar. Token metadata external_url points here.

### Collector Portal (gated)
Wallet actions: connect, mint/claim, stamps, airdrops, ownership UI, admin.

Rule: **external_url -> Story Hub**. Story Hub links into Portal for actions.

## URL conventions (Story Hub)
- Achilles: /achilles-war-of-troy (#ch01..#ch14, #box-set)
- Atlas: /atlas, /atlas/<teaser-slug>
- Passport: /passport (info + deep link to Portal claim)

## Core flows
A) Discover -> Mint chapter
B) Saga Pass -> Claim chapters
C) Atlas teaser -> Claim stamp

## UI states
Chapters: LOCKED / LIVE / COLLECTED / SOLD OUT / CLAIMABLE
Atlas: PREVIEW / OFFER ONLY / LIVE AUCTION
Stamps: AVAILABLE / CLAIMED / INELIGIBLE

## Admin (MVP)
- Toggle chapter status
- Set price/edition size (pre-release)
- Export holder snapshot for airdrops
- Update schedule windows
