## ML Systems

Modular ML pipeline ecosystem built around reproducible, containerized stages.

### Repositories

- [ml-meta](https://github.com/Ben0112358/ml-meta) – system overview and architecture map
- [ml-pipeline](https://github.com/Ben0112358/ml-pipeline) – orchestration entrypoint (dev/prod execution)
- [ml-infra](https://github.com/Ben0112358/ml-infra) – infrastructure setup (Docker, Terraform)
- [ml-data](https://github.com/Ben0112358/ml-data) – data ingestion and preprocessing
- [ml-training](https://github.com/Ben0112358/ml-training) – model training stage
- [ml-serving](https://github.com/Ben0112358/ml-serving) – model serving layer
- [ml-ui](https://github.com/Ben0112358/ml-ui) – simple frontend for inference

### Notes

- Each repository is independently runnable
- Pipeline can be executed end-to-end via `execute.sh` in ml-pipeline
