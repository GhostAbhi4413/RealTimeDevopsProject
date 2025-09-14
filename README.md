<!-- Header -->
<div align="center">
  <img src="https://opentelemetry.io/img/logos/opentelemetry-logo-nav.png" alt="OpenTelemetry" width="64" />
  <h1>OpenTelemetry Demo – Astronomy Shop</h1>

  <!-- Badges -->
  <p>
    <a href="https://cloud-native.slack.com/archives/C03B4CWV4DA">
      <img alt="Slack" src="https://img.shields.io/badge/slack-@cncf/otel/demo-brightgreen.svg?logo=slack">
    </a>
    <a href="https://github.com/open-telemetry/opentelemetry-demo/releases">
      <img alt="Version" src="https://img.shields.io/github/v/release/open-telemetry/opentelemetry-demo?color=blueviolet">
    </a>
    <a href="https://github.com/open-telemetry/opentelemetry-demo/graphs/commit-activity">
      <img alt="Commits since latest" src="https://img.shields.io/github/commits-since/open-telemetry/opentelemetry-demo/latest?color=ff69b4&include_prereleases">
    </a>
    <a href="https://hub.docker.com/r/otel/demo">
      <img alt="Docker pulls" src="https://img.shields.io/docker/pulls/otel/demo">
    </a>
    <a href="https://github.com/open-telemetry/opentelemetry-demo/blob/main/LICENSE">
      <img alt="License" src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=red">
    </a>
    <a href="https://github.com/open-telemetry/opentelemetry-demo/actions/workflows/run-integration-tests.yml">
      <img alt="Integration Tests" src="https://github.com/open-telemetry/opentelemetry-demo/actions/workflows/run-integration-tests.yml/badge.svg">
    </a>
    <a href="https://artifacthub.io/packages/helm/opentelemetry-helm/opentelemetry-demo">
      <img alt="Artifact Hub" src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/opentelemetry-demo">
    </a>
    <a href="https://www.bestpractices.dev/en/projects/9247">
      <img alt="OpenSSF Best Practices" src="https://www.bestpractices.dev/projects/9247/badge">
    </a>
  </p>

  <p><em>
    Note: This repository is a fork of <code>open-telemetry/opentelemetry-demo</code>.  
    Big thanks to all contributors for open-sourcing this excellent demo.
  </em></p>
</div>

---

## Overview

The **OpenTelemetry Astronomy Shop** is a microservices application designed to showcase end-to-end **OpenTelemetry** instrumentation in a near real-world system.

**Goals:**
- Provide a realistic, multi-language distributed app to demonstrate instrumentation & observability.
- Serve as a base for vendors/tooling authors to extend and integrate OTel.
- Offer a living example for contributors to test changes to the API/SDK/components.

See the ongoing progress in the project’s [CHANGELOG](https://github.com/open-telemetry/opentelemetry-demo/blob/main/CHANGELOG.md).

---

## Quick Start

Choose your preferred deployment method:

- **Docker Compose** → https://opentelemetry.io/docs/demo/docker_deployment/  
- **Kubernetes (Helm/Manifests)** → https://opentelemetry.io/docs/demo/kubernetes_deployment/

> Use the links above for the most up-to-date instructions.

---

## Documentation

For full documentation, start here: **[Demo Documentation][docs]**.  
If you’re looking for a specific feature, the docs landing page will guide you.

---

## Demos Featuring the Astronomy Shop

Vendors extending or integrating this demo:

|                           |                |                                  |
|---------------------------|----------------|----------------------------------|
| [AlibabaCloud LogService] | [Elastic]      | [OpenSearch]                     |
| [AppDynamics]             | [Google Cloud] | [Sentry]                         |
| [Aspecto]                 | [Grafana Labs] | [ServiceNow Cloud Observability] |
| [Axiom]                   | [Guance]       | [Splunk]                         |
| [Axoflow]                 | [Honeycomb.io] | [Sumo Logic]                     |
| [Azure Data Explorer]     | [Instana]      | [TelemetryHub]                   |
| [Coralogix]               | [Kloudfuse]    | [Teletrace]                      |
| [Dash0]                   | [Liatrio]      | [Tracetest]                      |
| [Datadog]                 | [Logz.io]      | [Uptrace]                        |
| [Dynatrace]               | [New Relic]    |                                  |

---

## Contributing

- Read the project’s **[CONTRIBUTING](CONTRIBUTING.md)** guide.  
- Join the **SIG calls** every other Monday at **8:30 AM PST** (details in CONTRIBUTING).

---

## Project Leadership

**Maintainers** ([@open-telemetry/demo-maintainers](https://github.com/orgs/open-telemetry/teams/demo-maintainers)):  
- [Juliano Costa](https://github.com/julianocosta89), Datadog  
- [Mikko Viitanen](https://github.com/mviitane), Dynatrace  
- [Pierre Tessier](https://github.com/puckpuck), Honeycomb

**Approvers** ([@open-telemetry/demo-approvers](https://github.com/orgs/open-telemetry/teams/demo-approvers)):  
- [Cedric Ziel](https://github.com/cedricziel), Grafana Labs  
- [Penghan Wang](https://github.com/wph95), AppDynamics  
- [Reiley Yang](https://github.com/reyang), Microsoft  
- [Roger Coll](https://github.com/rogercoll), Elastic  
- [Ziqi Zhao](https://github.com/fatsheep9146), Alibaba

**Emeritus:**  
[Austin Parker](https://github.com/austinlparker) · [Carter Socha](https://github.com/cartersocha) · [Michael Maxwell](https://github.com/mic-max) · [Morgan McLean](https://github.com/mtwo)

---

## Acknowledgements

Thanks to all contributors:  
[![contributors](https://contributors-img.web.app/image?repo=open-telemetry/opentelemetry-demo)](https://github.com/open-telemetry/opentelemetry-demo/graphs/contributors)

[docs]: https://opentelemetry.io/docs/demo/

<!-- Links for Demos featuring the Astronomy Shop section -->
[AlibabaCloud LogService]: https://github.com/aliyun-sls/opentelemetry-demo
[AppDynamics]: https://www.appdynamics.com/blog/cloud/how-to-observe-opentelemetry-demo-app-in-appdynamics-cloud/
[Aspecto]: https://github.com/aspecto-io/opentelemetry-demo
[Axiom]: https://play.axiom.co/axiom-play-qf1k/dashboards/otel.traces.otel-demo-traces
[Axoflow]: https://axoflow.com/opentelemetry-support-in-more-detail-in-axosyslog-and-syslog-ng/
[Azure Data Explorer]: https://github.com/Azure/Azure-kusto-opentelemetry-demo
[Coralogix]: https://coralogix.com/blog/configure-otel-demo-send-telemetry-data-coralogix
[Dash0]: https://github.com/dash0hq/opentelemetry-demo
[Datadog]: https://docs.datadoghq.com/opentelemetry/guide/otel_demo_to_datadog
[Dynatrace]: https://www.dynatrace.com/news/blog/opentelemetry-demo-application-with-dynatrace/
[Elastic]: https://github.com/elastic/opentelemetry-demo
[Google Cloud]: https://github.com/GoogleCloudPlatform/opentelemetry-demo
[Grafana Labs]: https://github.com/grafana/opentelemetry-demo
[Guance]: https://github.com/GuanceCloud/opentelemetry-demo
[Honeycomb.io]: https://github.com/honeycombio/opentelemetry-demo
[Instana]: https://github.com/instana/opentelemetry-demo
[Kloudfuse]: https://github.com/kloudfuse/opentelemetry-demo
[Liatrio]: https://github.com/liatrio/opentelemetry-demo
[Logz.io]: https://logz.io/learn/how-to-run-opentelemetry-demo-with-logz-io/
[New Relic]: https://github.com/newrelic/opentelemetry-demo
[OpenSearch]: https://github.com/opensearch-project/opentelemetry-demo
[Sentry]: https://github.com/getsentry/opentelemetry-demo
[ServiceNow Cloud Observability]: https://docs.lightstep.com/otel/quick-start-operator#send-data-from-the-opentelemetry-demo
[Splunk]: https://github.com/signalfx/opentelemetry-demo
[Sumo Logic]: https://www.sumologic.com/blog/common-opentelemetry-demo-application/
[TelemetryHub]: https://github.com/TelemetryHub/opentelemetry-demo/tree/telemetryhub-backend
[Teletrace]: https://github.com/teletrace/opentelemetry-demo
[Tracetest]: https://github.com/kubeshop/opentelemetry-demo
[Uptrace]: https://github.com/uptrace/uptrace/tree/master/example/opentelemetry-demo
