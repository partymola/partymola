A few projects I maintain. Mostly MCP servers that give an AI assistant read-only access to my own data - health, banking, tasks, e-bike - each caching locally rather than relaying through a third party. Plus BLE protocol work for cycling radar.

## MCP servers
- [bosch-flow-mcp](https://github.com/partymola/bosch-flow-mcp) - Bosch eBike Flow (BES3 Smart System): battery health, charge cycles, components, service history, per-ride activity.
- [fitbit-mcp](https://github.com/partymola/fitbit-mcp) - Fitbit Web API: OAuth PKCE, local SQLite cache, trend analysis.
- [monzo-mcp](https://github.com/partymola/monzo-mcp) - Monzo banking (read-only): OAuth + auto-refresh, local transaction cache, spending analysis.
- [ticktick-mcp](https://github.com/partymola/ticktick-mcp) - TickTick tasks: field-preserving updates, day-of-week validation, read-after-write verification, completion tracking.
- [withings-mcp](https://github.com/partymola/withings-mcp) - Withings health: OAuth, local cache, trend analysis (body / sleep / activity / workouts / ECG).

## Cycling
- [bike-radar-docs](https://github.com/partymola/bike-radar-docs) - BLE protocol spec and reference decoders for a rear-facing cycling radar (6a4e3200 service).
- [android-bike-radar-overlay](https://github.com/partymola/android-bike-radar-overlay) - Android companion for rear-bike-radar head units; V1/V2 BLE + optional Home Assistant integration.
