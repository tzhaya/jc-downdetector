# Threshold Analysis

## Initial Measurement

Generated from `docs/history.jsonl` after the first successful JIRCAS check on 2026-07-07 23:44:20 JST.

| Metric | Seconds |
| --- | ---: |
| p50 | 1.862 |
| p90 | 1.862 |
| p95 | 1.862 |
| p99 | 1.862 |
| max | 1.862 |

| State | Count |
| --- | ---: |
| OK | 1 |
| SLOW | 0 |
| VERY_SLOW | 0 |
| SERVER_ERROR | 0 |
| TIMEOUT | 0 |
| UNKNOWN | 0 |

## Threshold Decision

No threshold changes are made at this stage. The initial thresholds remain:

- `SLOW`: 5 seconds or more
- `VERY_SLOW`: 15 seconds or more
- `TIMEOUT`: 20 seconds

The current history contains only one successful sample, so it is not enough to tune thresholds. Revisit this after 1 to 2 weeks of scheduled measurements.
