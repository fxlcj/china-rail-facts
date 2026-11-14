# Changelog

Each entry records what changed and the date the official source was re-checked.
A figure never changes without its `checked_on` date changing with it.

## 2026-11-14 — incremental sync from published articles

- 1 entries added from official-source sentences in newly published articles; 0 candidates skipped (unreachable/non-official/duplicate source).

## 2026-11-14 — DB backfill

- 32 entries appended from the site's curated `verified_facts` (source URLs already re-checked against official pages at DB ingest). Append-only, deduped by claim+source.

## 2026-11-13 — correction: change (rebooking) fee is NOT percentage-based

- **Entry #12 replaced.** The previous row quoted a "5% / 15% / 40%" change-fee ladder. That figure no longer reflects the official rule and has been withdrawn: changing a ticket carries **no percentage fee** — you pay the fare difference if the new ticket costs more, and get the difference back if it costs less. The only fee that can arise is the refund fee, and only if you later cancel.
- Source re-pointed to the China Railway ticket-purchase notice (kyfw.12306.cn/mormhweb/zxdt/202311/t20231114_40286.html), re-checked 2026-11-13. The 48-hour rule in entry #11's companion facts governs *which trains* you may move to, not a fee rate.
- README narrative section "Change fees (rebooking)" and the machine-readable row updated in the same commit. Total entries unchanged (48).

## 2026-11-13 — incremental sync from published articles

- 1 entries added from official-source sentences in newly published articles; 0 candidates skipped (unreachable/non-official/duplicate source).

## 2026-11-11 — expanded with official-source facts

- 7 entries added directly from official Chinese government sources (rail: NRA/PSB Announcement No.1 items catalogue; food: Anti-Food-Waste Law; payment: Interim Regulation on Express Delivery; festival: holiday-decision amendment). Total now 47.

## 2026-11-10 — incremental sync from published articles

- 1 entry added from an official-source sentence in a newly published article (National Railway Administration, nra.gov.cn); 1 duplicate candidate skipped. An earlier same-day run (22 entries) was reverted the same day: its filters admitted internal links, affiliate links and fragments; sync was re-enabled only after filters were tightened to official-source-deep-links-only.

## 2026-11-10 — quality revert

- The first automated sync run (22 entries) was reverted: internal-link, affiliate and fragment sentences passed filters that were too loose. Dataset returned to the 39 hand-verified entries pending a stricter sync pass.

## 2026.11 — 2026-11-08

- Initial public dataset: 39 verified entries across 10 topics — advance sale,
  refunds, changes, luggage, child fares, student fares, ID requirements,
  waitlist limits, fare caps, and recently opened lines.
- Beijing–Shanghai HSR published fares re-checked on 2026-11-08 after the
  26 May 2026 fare reform; execution-fare range and published-fare cap are
  recorded as separate entries.
- Three lines opened on 2025-12-26 added with length, design speed, station
  count, fastest journey time and initial daily train count.
