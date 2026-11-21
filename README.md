# Justin Hoffman

.NET and observability engineer. I dig into production failure modes—especially metrics pipelines that look fine until cardinality takes them down—and turn them into reproducible labs you can run locally.

**Open to roles in 2027** · [LinkedIn](https://www.linkedin.com/in/justin-hoffman-78984b21)

## Featured work

### [prometheus-cardinality-repro](https://github.com/jdothoffman/prometheus-cardinality-repro)
Reproduce a real high-cardinality OOM path: **.NET OpenTelemetry → Grafana Alloy → Prometheus** on local k3d, with a load-test console, hypothesis soaks, and HTML root-cause reports.

- Shows how unbounded labels (e.g. float `response_time`) blow the series count
- Measures whether export back pressure contends with the live app
- Includes mitigations at the app and agent layers

### [scopeOS](https://github.com/jdothoffman/scopeOS)
Native **Mac** app for Celestron NexStar telescope control and capture (Swift).

## Focus

- Observability: OpenTelemetry, Prometheus, Grafana Alloy, cardinality / cost control
- Backend: .NET, HTTP services, load and failure testing
- Local Kubernetes labs (k3d) that mirror production node-pool and resource constraints

---

Profile: [github.com/jdothoffman](https://github.com/jdothoffman)
