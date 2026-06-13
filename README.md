# SolarEdge

SolarEdge Technologies provides a cloud-based Monitoring API that enables web services and third-party applications to access real-time and historical solar production data stored on the SolarEdge monitoring server. The REST API delivers site energy measurements, power flow data, inverter technical telemetry, battery storage status, equipment inventory, and environmental benefit metrics for SolarEdge-connected systems.

Authentication is handled via an API key generated through the SolarEdge monitoring portal, and all requests are made over HTTPS with responses returned in JSON format. The platform supports both site-level and account-level queries, with bulk call options allowing developers to retrieve data across multiple sites in a single request.

**Base URL:** `https://monitoringapi.solaredge.com`

**Authentication:** API key via `api_key` URL query parameter

**Rate Limits:** 300 requests/day per account token, 300 requests/day per site ID from same IP, max 3 concurrent requests

## Links

- **Website:** https://www.solaredge.com
- **Documentation:** https://knowledge-center.solaredge.com/sites/kc/files/se_monitoring_api.pdf
- **GitHub Org:** https://github.com/SolarEdgeTech
- **Blog:** https://www.solaredge.com/us/solaredge-blog
- **LinkedIn:** https://www.linkedin.com/company/solaredge
- **X:** https://x.com/SolarEdgePV

## APIs.json

This repository is an [APIs.json](https://apisjson.org) index for SolarEdge, maintained by [API Evangelist](https://apievangelist.com).

- **APIs.json:** [apis.yml](apis.yml)
- **Plans:** [plans/solar-edge-plans-pricing.yml](plans/solar-edge-plans-pricing.yml)
- **Rate Limits:** [rate-limits/solar-edge-rate-limits.yml](rate-limits/solar-edge-rate-limits.yml)
- **FinOps:** [finops/solar-edge-finops.yml](finops/solar-edge-finops.yml)

**Maintainer:** Kin Lane (kin@apievangelist.com)
