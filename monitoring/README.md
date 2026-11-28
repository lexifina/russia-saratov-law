<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Saratov Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 06:03 UTC, Saratov Oblast: Official Internet Portal of Legal Information (region64): 11 addresses read; 6 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Saratov Oblast: Official Internet Portal of Legal Information (region64)](http://publication.pravo.gov.ru/documents/block/region64) | `zakony-<year>/` | daily | 2026-11-28 06:03 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 06:03](checks/2026-11.md#ru-pravo-saratov-20261128t060309z) | pravo-saratov | 11 | 6 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-saratov-law/compare/d783dcb9b3b7...cc50a816c76b) |
| [2026-11-27 05:52](checks/2026-11.md#ru-pravo-saratov-20261127t055234z) | pravo-saratov | 11 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:58](checks/2026-11.md#ru-pravo-saratov-20261126t055829z) | pravo-saratov | 11 | 4 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-saratov-law/compare/dfa37ecf4461...7092e09897be) |
| [2026-11-25 06:34](checks/2026-11.md#ru-pravo-saratov-20261125t063401z) | pravo-saratov | 11 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:49](checks/2026-11.md#ru-pravo-saratov-20261124t144946z) | pravo-saratov | 11 | 14 | 0 | 0 | 0 (0) | changes found | [4](https://github.com/lexifina/russia-saratov-law/compare/0a84fe56a102...018c30e4b687) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
