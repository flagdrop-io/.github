## FlagDrop

**Feature flags that run where your code runs.**

FlagDrop is a feature flag platform where evaluations happen entirely inside your cloud. We push config to your bucket (S3, GCS, or Azure Blob Storage) and your applications read flags locally with zero-latency evaluations. Your data never leaves your infrastructure.

### How it works

```
FlagDrop (Control Plane)  -->  Config Push  -->  Your Cloud (S3 / GCS / Azure)  -->  Local Read  -->  Your App
```

### SDKs

| SDK | Description |
|-----|-------------|
| **sdk-node** | Node.js/TypeScript backend SDK |
| **sdk-python** | Python backend SDK |
| **sdk-browser** | Browser SDK with SSE relay |
| **openfeature-provider** | OpenFeature provider for migration from other platforms |

### Key features

- **Zero latency** — flags evaluate locally from your cloud bucket, no network round-trips
- **Multi-cloud** — AWS S3, Google Cloud Storage, Azure Blob Storage
- **Per-environment config** — production on GCP, staging on AWS, each with its own bucket and credentials
- **Targeting rules** — attribute matching, segment targeting, percentage rollouts
- **Fixed pricing** — flat per-project pricing with unlimited flags, environments, and evaluations

### Links

- [flagdrop.io](https://flagdrop.io) — Marketing site
- [Documentation](https://flagdrop.io/docs) — Quickstart and API reference
