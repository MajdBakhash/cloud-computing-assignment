# Cloud Computing Assignment

## Secret Management with HashiCorp Vault

### Deployment with Sidecar Container
- The `deployment-with-sidecar.yaml` file defines a Kubernetes deployment that uses a sidecar container to inject secrets from HashiCorp Vault.
- Secrets are injected into the main container as environment variables.