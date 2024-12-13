# fdsfsdf

fdsfds

```shell
OTEL_OPERATOR_VERSION=v0.114.0
kubectl apply -f https://github.com/open-telemetry/opentelemetry-operator/releases/download/$OTEL_OPERATOR_VERSION/opentelemetry-operator.yaml
```

dsds

```yaml
f:
  mode: "neee"
  image: "ghcr.io/dynatrace/dynatrace-otel-collector/dynatrace-otel-collector:v0.19.0"
  rblah:
```

```yaml
n:
  mode: "neee"
  image:
    repository: ghcr.io/dynatrace/dynatrace-otel-collector/dynatrace-otel-collector
    tag: v0.19.0
  rblah:
```

```bash
docker pull ghcr.io/dynatrace/dynatrace-otel-collector/dynatrace-otel-collector:v0.19.0
```

```bash
docker run -v $(pwd)/otel-collector-config.yaml:/etc/otelcol/otel-collector-config.yaml ghcr.io/dynatrace/dynatrace-otel-collector/dynatrace-otel-collector:v0.19.0 --config=/etc/otelcol/otel-collector-config.yaml
```

To install the Collector binary manually

1. Download the [dynatrace-otel-collector](https://github.com/Dynatrace/dynatrace-otel-collector/releases/v0.19.0) for your operating system from GitHub.

```sh
DT_OTEL_COLLECTOR_VERSION=v0.19.0
yum update
```

* dfs
  * `ghcr.io/dynatrace/dynatrace-otel-collector/dynatrace-otel-collector:v0.19.0`

* fdsfd
  * `public.ecr.aws/dynatrace/dynatrace-otel-collector:v0.19.0`