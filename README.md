# swe

Results of [cap-evolve](https://github.com/skillberry-ai/cap-evolve) runs on **SWE-bench**: SWE-bench and its variants (Verified, the Red Hat rh-swebench set).
One of the per-benchmark result repos in the [skillberry-runs](https://github.com/skillberry-runs) org.

**On the dashboard:** <https://skillberry-runs.github.io/dashboard/swe/>. The run rows (reward,
cost, models per run) are on the [main table](https://skillberry-runs.github.io/dashboard/) (filter
*Benchmark*); each row's **Open UI** opens that run's CapEvolve dashboard from this repo's `ci_ui/`.

## What is here

- `ci_ui/<run_id>__<tier>-<bench>/`: per-run "Open UI" data (23 runs, 2026-07-24 to 2026-10-06), moved on
  2026-11-17 from cap-evolve's `benchmark-history` branch. See [`ci_ui/README.md`](ci_ui/README.md).
- Write-ups (`*.md`) and report pages (`ui/*.html`) added here are published on the dashboard too.

| `bench` value in the run records | runs |
|---|---|
| `swebench` | 24 |
| `swebench-verified` | 3 |
| `rh-swebench` | 1 |

## Adding to it

See the dashboard's [PUBLISHING.md](https://github.com/skillberry-runs/dashboard/blob/main/PUBLISHING.md):
section B for write-ups, F for "Open UI" data.
