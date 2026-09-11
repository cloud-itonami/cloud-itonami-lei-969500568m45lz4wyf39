# cloud-itonami-lei-969500568m45lz4wyf39

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Keolis SA.**

This repository archives the publicly published legal notice ("mentions
légales") of **Keolis SA**, with source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: Keolis SA
- **LEI (ISO 17442)**: [969500568M45LZ4WYF39](https://search.gleif.org/#/record/969500568M45LZ4WYF39) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: FR
- **Website**: https://www.keolis.com
- **Ticker**: unlisted (70% SNCF / 30% Caisse de dépôt et placement du Québec since 2012)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived legal notice documents.
- `facts.edn` — verified public-registry facts (GLEIF), each with the URL it was read from and the retrieval time. Generated; do not hand-edit.
- `scripts/verify-facts.cljk` — re-fetches every source `facts.edn` cites and fails if the live registry no longer agrees (`nbb scripts/verify-facts.cljk`; exit 0 = match, 1 = drift/broken citation, 3 = could not check). Vendored from `com-junkawasaki/root`.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

Keolis is one of the world's largest public-transit operators by contract count,
running urban bus, tram, metro and light-rail networks under contract to transit
authorities in many countries. This vertical's *generic, forkable* Open Business
Blueprint counterpart in the `cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921; the cross-reference exists so a reader
researching real-world urban-transit operators for market/competitive context can
find both the real company's published terms and the corresponding generic
governed-actor blueprint from one place.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
