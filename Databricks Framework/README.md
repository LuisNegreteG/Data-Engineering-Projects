# Portfolio PySpark Metrics Framework (Databricks-style)

This repository showcases a **Databricks-inspired PySpark framework** for building reusable metric pipelines using **clean architecture**:
- Notebooks for orchestration and exploration
- Reusable Python modules under `src/`
- Production-friendly entrypoints under `jobs/`
- Fictitious, non-sensitive sample datasets

> Note: All data, names, and examples are **synthetic** and created only for portfolio purposes.

---

## What this project demonstrates

- **Modular design** (configs, utils, metrics logic separated)
- **PySpark pipelines** for metric computation (summary + expand)
- **SCD-1 style ingestion pattern** with `is_current` (portfolio version)
- **Environment-aware configuration** (dev/test/prod-like)
- Optional integration of **pandas** for small metadata operations

---

## Repository structure
- notebooks/ # interactive orchestration & demos
- jobs/ # production-style entrypoints (spark-submit / Databricks Jobs)
- src/ # reusable modules (config, utils, metrics)
- data/ # synthetic sample inputs
- tests/ # unit tests for helper logic (dates, validations)
