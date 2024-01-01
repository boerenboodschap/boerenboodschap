# boerenboodschap

Repository for development purposes, contains a docker-compose.yml file that can be used to run the development environment.

1. Clone all repositories of all the microservices in the boerenboodschap organisation.
2. Run `docker compose`
3. Enjoy!

## Configurations

### Argo

### Pulumi

### Prometheus

To install prometheus in a kubernetes cluster run the following command:

```bash
  helm install prometheus -f prometheus.yaml ./prometheus
```
