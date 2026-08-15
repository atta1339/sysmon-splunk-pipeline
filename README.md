# sysmon-splunk-pipeline
Sysmon → Splunk telemetry ingestion pipeline for security engineering, detection tuning, and DFIR.
sysmon-splunk-pipeline/
│
├── README.md
│
├── sysmon/
│   ├── sysmon-config.xml
│   ├── sysmon-install-notes.md
│   └── sysmon-event-cheatsheet.md
│
├── splunk-forwarder/
│   ├── inputs.conf
│   ├── outputs.conf
│   ├── deployment-client.conf
│   └── forwarder-install-notes.md
│
├── splunk-indexing/
│   ├── indexes.conf
│   ├── props.conf
│   ├── transforms.conf
│   └── parsing-notes.md
│
├── detections/
│   ├── detection-logic.md
│   ├── example-splunk-searches.md
│   └── false-positive-tuning.md
│
├── dashboards/
│   ├── sysmon-overview.json
│   ├── process-monitoring.json
│   └── dashboard-notes.md
│
├── troubleshooting/
│   ├── ingestion-issues.md
│   ├── connector-health.md
│   └── telemetry-gaps.md
│
└── screenshots/
    ├── sysmon-events.png
    ├── splunk-search.png
    └── dashboards.png
