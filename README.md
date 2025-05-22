# OpenTelemetry Collector Demo

This sets up a simple OpenTelementry setup with all the necessary components to collect and view OTEL data.

Boot up the stack:

```shell
docker compose up -d
```

That will expose the following backends:

- Jaeger at http://0.0.0.0:16686
- Grafana at http://0.0.0.0:3111
  - Credentials: `admin`/`admin`

In case you don't want to use Grafana, you can access Prometheus directly:

- Prometheus at http://0.0.0.0:9090
