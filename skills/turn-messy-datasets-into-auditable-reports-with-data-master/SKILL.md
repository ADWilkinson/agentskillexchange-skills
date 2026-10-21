---
name: "Turn messy datasets into auditable reports with data-master"
slug: "turn-messy-datasets-into-auditable-reports-with-data-master"
description: "Use data-master to preserve raw tabular data, hold ambiguous cleaning decisions for review, run unit-aware statistics and sensitivity checks, and produce Markdown, HTML and PDF reports with machine-verifiable audit evidence."
verification: "listed"
source: "https://github.com/MAGA2010/data-master"
author: "MAGA2010"
publisher_type: "individual"
category: "Data Extraction & Transformation"
framework: "Codex"
tool_ecosystem:
  github_repo: "maga2010/data-master"
---

# Turn messy datasets into auditable reports with data-master

Use data-master when a CSV, TSV, Excel, JSON, JSONL or Parquet analysis must be
reproducible and reviewable rather than a one-off notebook. The tool reads
potentially destructive fields as text first, records every cleaning decision,
and refuses to guess when values could have more than one valid meaning, such as
zero-padded identifiers or compact values that could be dates or integers. It
supports declared independent units, repeated measures, paired comparisons,
covariate-adjusted comparisons, sensitivity analysis and descriptive time-series
work. A completed run includes cleaned data, a replayable cleaning program,
machine-readable statistics, charts, Markdown, self-contained HTML, PDF and a
separate audit verdict. Use the saved verification command before relying on a
delivered report. Treat unresolved holds and failed audit gates as questions for
the dataset owner; do not silently replace them with weaker assumptions.

## Installation

No source-backed install or usage instructions could be extracted automatically. Review the upstream project before running this skill in a sensitive workflow.

- Source: https://github.com/MAGA2010/data-master

## Documentation

Reviewed release: `v0.3.0`, commit
[`9d22e2505071424d7e41dc2ee5b875b45a1ed574`](https://github.com/MAGA2010/data-master/tree/9d22e2505071424d7e41dc2ee5b875b45a1ed574).

- [Source and quick start](https://github.com/MAGA2010/data-master)
- [Evaluation evidence](https://github.com/MAGA2010/data-master/blob/9d22e2505071424d7e41dc2ee5b875b45a1ed574/EVALUATION.md)
- [Validation matrix](https://github.com/MAGA2010/data-master/blob/9d22e2505071424d7e41dc2ee5b875b45a1ed574/docs/VALIDATION.md)
- [Agent Skill Exchange](https://agentskillexchange.com/skills/turn-messy-datasets-into-auditable-reports-with-data-master/)
