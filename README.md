## ML Systems

Modular ML pipeline ecosystem built around reproducible, containerized stages.

Not limited to ML models in the strict sense. Supports project-specific pipelines producing arbitrary outputs, from machine learning models to general optimization or computation results.
### Repositories

- [ml-meta](https://github.com/Ben0112358/ml-meta) – Overview, architecture, and cross-repo dev tooling.
- [ml-pipeline](https://github.com/Ben0112358/ml-pipeline) – orchestration entrypoint (dev/prod execution)
- [ml-infra](https://github.com/Ben0112358/ml-infra) – infrastructure setup
- [ml-data](https://github.com/Ben0112358/ml-data) – data ingestion and preprocessing
- [ml-training](https://github.com/Ben0112358/ml-training) – model training stage
- [ml-serving](https://github.com/Ben0112358/ml-serving) – model serving layer
- [ml-ui](https://github.com/Ben0112358/ml-ui) – simple frontend for inference

### Notes

- Each repository is independently runnable
- Pipeline can be executed end-to-end via `execute.sh` in ml-pipeline

### Implemented models (so far)
- Dummy model for end-to-end pipeline validation.
- Portfolio allocation optimizer (Bayesian optimization), demonstrating non-ML training outputs.
- Board meeting protocol: prompt pack for writing and reviewing meeting protocols.

### Other projects
- [llm-decision-spec](https://github.com/Ben0112358/llm-decision-spec) – Python library for defining event-based features as a composable AST (work in progress).
