# Production Plan (v1)

## Per-token content
- myth_scene, meaning_line, caption_300
- symbols (semicolon list -> split into multiple traits)
- title_en, description_en, alt_text_en
- license_url + license_attr_value
- external_url (Story Hub)
- operator_filter=on, standard, edition_size, price

## Pipeline
Sheet -> export JSON -> IPFS (CIDs) -> deploy -> list

## QC gate (must pass before listing)
- Required fields present
- Name/slug/file lengths within budget
- external_url resolves to correct Story Hub anchor
- Media fields populated (CID/MIME/bytes) after merge

## Release mechanics
- Chapters: 1155/Base, fixed price, stable edition size per season
- Saga Pass: 1155/Base, claim one of each chapter
- Atlas Teasers: 721/ETH, minted to treasury, unlisted until season opens

## Guardrails
- Never change slugs once public
- Avoid supply changes mid-season
- Keep utility deliverable (prints/access/stamps)
