# pronunt-helm-charts

Single source of truth for Pronunt Helm charts and Argo CD application definitions.

## Layout

- `apps/`: application Helm charts for all microservices
- `infra/`: cluster-level infrastructure charts and manifests
- `env/test`: Argo CD layer for test
- `env/prod`: Argo CD layer for prod
