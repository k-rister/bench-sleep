# Bench-sleep

## Purpose
Minimal benchmark that exercises the full crucible pipeline without adding workload. Used for CI testing, framework validation, and observing a system at its current state without introducing additional load.

## Language
Bash — all scripts

## Key Files
| File | Purpose |
|------|---------|
| `rickshaw.json` | Rickshaw integration: client script and post-processing |
| `sleep-client` | Client-side execution (runs sleep) |
| `sleep-get-runtime` | Extracts runtime from command-line options |
| `sleep-post-process` | Post-processing script |
| `workshop.json` | Engine image build requirements |

## Conventions
- Primary branch is `main`
- Standard Bash modelines and 4-space indentation
