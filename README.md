# goupwithcncf
Going Up with CNCF


```
└── cncf_landscape
    └── observability - 48
        ├── chaosmonkey - 6
        │   ├── [chaos-mesh](cncf_landscape/observability/chaosmonkey/chaos-mesh)
        │   ├── [chaosblade](cncf_landscape/observability/chaosmonkey/chaosblade)
        │   ├── chaoskube
        │   ├── chaostoolkit
        │   ├── litmus
        │   └── powerfulseal
        ├── logging - 2
        │   ├── logstash
        │   └── loki
        ├── monitoring - 20
        │   ├── NexClipper
        │   ├── OpenMetrics
        │   ├── VictoriaMetrics
        │   ├── beats
        │   ├── centreon
        │   ├── checkmk
        │   ├── cortex
        │   ├── falcon-plus
        │   ├── foniod
        │   ├── grafana
        │   ├── graphite-web
        │   ├── icinga2
        │   ├── influxdb
        │   ├── kiali
        │   ├── kuberhealthy
        │   ├── m3db
        │   ├── nagioscore
        │   ├── netdata
        │   ├── nightingale
        │   ├── opentsdb
        │   ├── opstrace
        │   ├── packet-agent
        │   ├── pixie
        │   ├── scope
        │   ├── sensu-go
        │   ├── skooner
        │   ├── sysdig
        │   ├── trickster
        │   ├── vector
        │   └── zabbix
        └── tracing - 10
            ├── apm-server
            ├── community
            ├── easeagent
            ├── opentracing-go
            ├── pinpoint
            ├── skywalking 
            ├── sofa-tracer
            ├── spring-cloud-sleuth
            ├── tempo
            └── zipkin
```

Real-time performance monitoring, done right! https://www.netdata.cloud
Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share beautiful dashboards with your team and foster a data driven culture.
Scalable datastore for metrics, events, and real-time analytics
APM, Application Performance Monitoring System
Zipkin is a distributed tracing system
Loki is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.
Logstash - transport and process your logs, events, or other data
APM, (Application Performance Management) tool for large-scale distributed systems. 
🐠 Beats - Lightweight shippers for Elasticsearch & Logstash 
A high-performance observability data pipeline.
 An open-source and enterprise-level monitoring system.
sysdig is a simple tool with deep system visibility for exploration and troubleshooting, with native support for containers.
VictoriaMetrics: fast, cost-effective monitoring solution and time series database
A highly scalable real-time graphing system
Monitoring, visualisation & management for Docker & Kubernetes
A scalable, distributed Time Series Database.
A horizontally scalable, highly available, multi-tenant, long term Prometheus.
A Chaos Engineering Platform for Kubernetes.
An easy to use and powerful chaos engineering experiment toolkit.（阿里巴巴开源的一款简单易用、功能强大的混沌实验注入工具）
An enterprise-level cloud-native monitoring system, which can be used as drop-in replacement of Prometheus for alerting and management.
M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform
OpenTracing API for Go. 🛑 This library is DEPRECATED! https://github.com/opentracing/specification/issues/163
Open source Kubernetes observability for developers
Kiali project, observability for the Istio service mesh
Litmus helps  SREs and developers practice chaos engineering in a Cloud-native way. Chaos experiments are published at the ChaosHub  (https://hub.litmuschaos.io). Community notes is at https://hackmd.io/a4Zu_sH4TZGeih-xCimi3Q
Real-time monitoring of IT components and services, such as networks, servers, VMs, applications and the cloud.
Grafana Tempo is an open source, easy-to-use and high-scale distributed tracing backend. Tempo is cost-efficient, requiring only object storage to operate, and is deeply integrated with Grafana, Prometheus, and Loki. Tempo can be used with any of the open source tracing protocols, including Jaeger, Zipkin, and OpenTelemetry.
A powerful testing tool for Kubernetes clusters.
The core of our monitoring platform with a powerful configuration language and REST API.
Evolving the Prometheus exposition format into a standard.
Open Source HTTP Reverse Proxy Cache and Time Series Dashboard Accelerator
Distributed tracing for spring cloud
chaoskube periodically kills random pods in your Kubernetes cluster.
Chaos Engineering Toolkit & Orchestration for Developers
A Kubernetes operator for running synthetic checks as pods. Works great with Prometheus!
Secure Open Source Observability Deployed in your own Network
Nagios Core
SOFATracer is a component for the distributed system call trace. And through a unified traceId logging the logs of various network calls in the invoking link. These logs can be used for quick discovery of faults, service governance, etc.
APM Server
Simple Kubernetes real-time dashboard and management.
A toolset for network packet capture in Cloud/Kubernetes and Virtualized environment.
Simple. Scalable. Multi-cloud monitoring.
Checkmk - Best-in-class infrastructure & application monitoring
Metrics Pipeline for interoperability and Enterprise Prometheus
Centreon is a network, system and application monitoring tool. Centreon is the only AIOps Platform Providing Holistic Visibility to Complex IT Workflows from Cloud to Edge.
OpenTelemetry community content
EaseAgent is a Javaagent that can be integrated with the mainstream monitoring system, providing standard data formats that are fully compatible with OpenZipkin and Prometheus. EaseAgent is also very easy to extend through the Plugin Mechanism which only a minimum of three interfaces are required to be implemented to complete a plugin development.
Data first monitoring agent using (e)BPF, built on RedBPF