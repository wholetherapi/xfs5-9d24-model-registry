# Northwind Analytics Model Registry

This repository holds the benchmark model registry plus the raw evaluation
exports produced by the benchmark pipelines.

- `registry/model_registry.json` - canonical registry consumed by downstream reporting.
- `data/` - raw evaluation exports. Treat these files as read-only inputs.

Only registry updates are accepted in pull requests; evaluation exports are
published by the benchmark pipeline.
