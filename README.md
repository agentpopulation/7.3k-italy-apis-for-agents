<p align="center"><img src="assets/banner.svg" width="100%" alt="Italy API endpoints: 7,336 API endpoints passed a keyless data call"></p>

# 🇮🇹 Italy API endpoints

**7,336 API endpoints filed under country code IT that answered a keyless GET with a data body. For agent and app builders.**

<p align="center"><a href="#files"><img src="https://img.shields.io/badge/endpoints-7%2C336-6366F1" alt="endpoints: 7,336"></a> <a href="#columns-and-tags"><img src="https://img.shields.io/badge/keyless%20JSON-7%2C336-6366F1" alt="keyless JSON: 7,336"></a> <a href="#whats-inside"><img src="https://img.shields.io/badge/services-242-0F172A" alt="services: 242"></a> <a href="#whats-inside"><img src="https://img.shields.io/badge/country-IT-EA580C" alt="country: IT"></a> <a href="LICENSE"><img src="https://img.shields.io/badge/licence-CC%20BY%204.0-0F172A" alt="licence: CC BY 4.0"></a></p>

<p align="center"><a href="#whats-in-it-for-you">What's in it</a> · <a href="#for-ai-agents">For AI agents</a> · <a href="#quick-start">Quick start</a> · <a href="#test-it-yourself">Test it yourself</a> · <a href="#files">Files</a> · <a href="#licence-and-credit">Licence</a> · <a href="#part-of-10m-api-endpoints-for-ai-agents">More packs</a></p>

This repository holds a 1,000-row sample and the services list; the full list of 7,336 endpoints is one download from the [latest release](https://github.com/agentpopulation/7.3k-italy-apis-for-agents/releases/latest).

**Endpoints filed under country code IT, for building an agent or app for Italy.** Layers of the Sardinia environment agency, Lombardy, the national geophysics and volcanology institute and municipal unions, as URLs that answered with no key on their test date.

Selection rule: rows where `country is IT`, less the rows that a leave-out rule drops (each counted under Known limits).

7,183 of these 7,336 rows match the focus rule (below); the others are in the pack by the selection rule only, and Known limits says what they are. 7,277 rows (99.2%) are map layers on ArcGIS Online, where anyone can publish.

## In plain words

**What is an API endpoint?** An API endpoint is one web address that a program can ask for data, for example the latest reading at one weather station. A single service, such as a national weather agency, can have thousands of endpoints: one per station, city or dataset. This pack counts endpoints, not separate services.

**What does "passed a data call" mean?** On the date shown in each row, AgentPopulation sent one plain request to that address, with no password or key, and got a non-empty data body back (JSON, CSV, XML or a file): not an error page and not an empty result. Some bodies describe a dataset rather than hold its values; see Known limits. It shows the address answered with data on that day. It is not a promise that it answers today, and licences and usage limits were not reviewed.

## What's in it for you

Four ways to use this pack. Each bucket gives a count, a filter you can apply to the CSV, one example that passed, and a list of recommended starting points with the rule that picked them. Buckets overlap; a row can fit more than one.

Examples, recommended lists and the preview are drawn from rows that match this pack's focus rule, so a row that the selection rule put in this pack but that is about something else is not shown as a starting point. Counts cover the whole bucket.

<details>
<summary>The focus rule</summary>

Focus rule: `NOT title matches /(?<![a-z])(test|tests|testing|draft|drafts|copy|sample|samples|demo|untitled|scratch|temp|tmp|delete|deleteme|practice|dummy|example|training)(?![a-z])|final_final|\d{7,}/i`

</details>

### 🤖 Agent tools: Keyless JSON layers and tables an agent can call (Italy)

**7,336** endpoints from 242 services · Wrap one layer query as a get_layer_features tool: pass a where clause or a bounding box, return the matching features with a timeout.

7,336 of these are map-layer queries that asked for a few records (`resultRecordCount`); add a where clause or a geometry to ask about one place, and page through for the whole layer.

Start with: `tags has agent-ready`

Example: [161miglia\_lunga\_2024](https://services3.arcgis.com/mFSogUeqpAu2uWFw/ArcGIS/rest/services/161miglia_lunga_2024/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) · ArcGIS Online layers (services3.arcgis.com, org mFSogUeqpAu2uWFw) · passed 2026-11-16

<details>
<summary>Recommended starting points: 8 services, picked by the stated criteria inside</summary>

**Recommended starting points.** Selected by stated criteria, not a ranking of quality: Services in this pack with the most endpoints that match this bucket and are tagged `agent-ready` (no key sent in the test call, JSON body, passed a data call). Ties go to the service with more country codes, then by name. Only services with at least one bucket row that matches the focus rule are listed, and the sample comes from those rows; the counts cover the whole bucket. The sample URL is the first row by URL sort after preferring, in this order: rows that match the bucket's sample preference when it has one, rows that return values rather than describe a dataset or a service (not ERDDAP /info/ pages, OGC GetCapabilities requests, bare OWS addresses, PxWeb tables, UN SDG series lists, Statistics Canada download pointers, WorldPop listings, GTFS validation reports, untitled rows or service root addresses), and agent-ready rows. Sample preference in this bucket: `url matches //query\?/i`. Services named "ArcGIS organization" hold map layers from many owners and are added only when fewer than 5 other services match.

| Service (host) | Endpoints in bucket | In pack | Country codes in bucket | Formats in bucket | Sample URL that passed |
|---|---:|---:|---|---|---|
| Agenzia ARPA Sardegna (ArcGIS Online) (services6.arcgis.com) | 334 | 334 | IT | json | [A\_RISCHIO\_NJ](https://services6.arcgis.com/VdOe78ROZ6pyB2c8/ArcGIS/rest/services/A_RISCHIO_NJ/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Esri Italia TM (ArcGIS Online) (services.arcgis.com) | 221 | 221 | IT | json | [Aree\_Archeologiche\_Lazio](https://services.arcgis.com/nIbPrXGkjlJqLKTA/ArcGIS/rest/services/Aree_Archeologiche_Lazio/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| I.D.T. della Lombardia (ArcGIS Online) (services1.arcgis.com) | 184 | 184 | IT | json | [ALBO\_OF\_ACCR\_ATECO](https://services1.arcgis.com/XannvQVnsM1hoZyv/ArcGIS/rest/services/ALBO_OF_ACCR_ATECO/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Unione Comuni Garfagnana (ArcGIS Online) (services9.arcgis.com) | 156 | 156 | IT | json | [AP](https://services9.arcgis.com/Xd9huFXwXykJWlu1/ArcGIS/rest/services/AP/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Roma Servizi per la Mobilità s.r.l. (ArcGIS Online) (services2.arcgis.com) | 142 | 142 | IT | json | [117](https://services2.arcgis.com/NZMqCJwY3kMjFOqf/ArcGIS/rest/services/117/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Istituto Nazionale di Geofisica e Vulcanologia (ArcGIS Online) (services1.arcgis.com) | 119 | 119 | IT | json | [10\_anniversario\_Emilia\_19\_5\_2012\_19\_7\_2…](https://services1.arcgis.com/z0Oh0igg7i25Y3AM/ArcGIS/rest/services/10_anniversario_Emilia_19_5_2012_19_7_2012/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Save the Children Italia (ArcGIS Online) (services3.arcgis.com) | 87 | 87 | IT | json | [Centri\_antiviolenza\_case\_rifugio\_tasso\_…](https://services3.arcgis.com/jiXW75yUEzuPStZi/ArcGIS/rest/services/Centri_antiviolenza_case_rifugio_tasso_per_100000_donne_14_anni_e_piu_Regione_e_PA/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| TeamDev (ArcGIS Online) (services.arcgis.com) | 75 | 75 | IT | json | [Buffer cromotropiche](https://services.arcgis.com/C8K37aOKTOQQvitW/ArcGIS/rest/services/Buffer%20cromotropiche/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |

</details>

### 📱 App features: Map layers to draw in an app (Italy)

**7,336** endpoints from 242 services · Add the layers to an app map: read the layer once for its fields, then ask for the features in the visible area.

Start with: `url matches //(Feature|Map)Server//i`

Example: [161miglia\_lunga\_2024](https://services3.arcgis.com/mFSogUeqpAu2uWFw/ArcGIS/rest/services/161miglia_lunga_2024/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) · ArcGIS Online layers (services3.arcgis.com, org mFSogUeqpAu2uWFw) · passed 2026-11-16

<details>
<summary>Recommended starting points: 8 services, picked by the stated criteria inside</summary>

**Recommended starting points.** Selected by stated criteria, not a ranking of quality: Services in this pack with the most endpoints that match this bucket and passed a data call. Ties go to the service with more country codes, then by name. Only services with at least one bucket row that matches the focus rule are listed, and the sample comes from those rows; the counts cover the whole bucket. The sample URL is the first row by URL sort after preferring, in this order: rows that match the bucket's sample preference when it has one, rows that return values rather than describe a dataset or a service (not ERDDAP /info/ pages, OGC GetCapabilities requests, bare OWS addresses, PxWeb tables, UN SDG series lists, Statistics Canada download pointers, WorldPop listings, GTFS validation reports, untitled rows or service root addresses), and agent-ready rows. Services named "ArcGIS organization" hold map layers from many owners and are added only when fewer than 5 other services match.

| Service (host) | Endpoints in bucket | In pack | Country codes in bucket | Formats in bucket | Sample URL that passed |
|---|---:|---:|---|---|---|
| Agenzia ARPA Sardegna (ArcGIS Online) (services6.arcgis.com) | 334 | 334 | IT | json | [A\_RISCHIO\_NJ](https://services6.arcgis.com/VdOe78ROZ6pyB2c8/ArcGIS/rest/services/A_RISCHIO_NJ/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Esri Italia TM (ArcGIS Online) (services.arcgis.com) | 221 | 221 | IT | json | [Aree\_Archeologiche\_Lazio](https://services.arcgis.com/nIbPrXGkjlJqLKTA/ArcGIS/rest/services/Aree_Archeologiche_Lazio/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| I.D.T. della Lombardia (ArcGIS Online) (services1.arcgis.com) | 184 | 184 | IT | json | [ALBO\_OF\_ACCR\_ATECO](https://services1.arcgis.com/XannvQVnsM1hoZyv/ArcGIS/rest/services/ALBO_OF_ACCR_ATECO/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Unione Comuni Garfagnana (ArcGIS Online) (services9.arcgis.com) | 156 | 156 | IT | json | [AP](https://services9.arcgis.com/Xd9huFXwXykJWlu1/ArcGIS/rest/services/AP/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Roma Servizi per la Mobilità s.r.l. (ArcGIS Online) (services2.arcgis.com) | 142 | 142 | IT | json | [117](https://services2.arcgis.com/NZMqCJwY3kMjFOqf/ArcGIS/rest/services/117/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Istituto Nazionale di Geofisica e Vulcanologia (ArcGIS Online) (services1.arcgis.com) | 119 | 119 | IT | json | [10\_anniversario\_Emilia\_19\_5\_2012\_19\_7\_2…](https://services1.arcgis.com/z0Oh0igg7i25Y3AM/ArcGIS/rest/services/10_anniversario_Emilia_19_5_2012_19_7_2012/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Save the Children Italia (ArcGIS Online) (services3.arcgis.com) | 87 | 87 | IT | json | [Centri\_antiviolenza\_case\_rifugio\_tasso\_…](https://services3.arcgis.com/jiXW75yUEzuPStZi/ArcGIS/rest/services/Centri_antiviolenza_case_rifugio_tasso_per_100000_donne_14_anni_e_piu_Regione_e_PA/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| TeamDev (ArcGIS Online) (services.arcgis.com) | 75 | 75 | IT | json | [Buffer cromotropiche](https://services.arcgis.com/C8K37aOKTOQQvitW/ArcGIS/rest/services/Buffer%20cromotropiche/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |

</details>

### 🧠 Grounding and data pipelines: Statistics, boundaries, parcels and inventories for scheduled loads (Italy)

**23** endpoints from 9 services · Load the tables and layers on a schedule into your own store, so an agent can cite a dated source.

Start with: `format in (csv, xml, geojson) OR title matches /statist|census|population|boundar|parcel|zoning|district|budget|election|crash|permit|inventory|land ?use|landuse|cadast|address/i`

Example: [Census\_Italia\_gdb - Istat\_Prov\_Sez](https://services.arcgis.com/nIbPrXGkjlJqLKTA/arcgis/rest/services/Census_Italia_gdb/FeatureServer/1/query?where=1%3D1&outFields=*&returnGeometry=false&resultRecordCount=5&f=json) · Esri Italia TM (ArcGIS Online) · passed 2026-11-16

<details>
<summary>Recommended starting points: 5 services, picked by the stated criteria inside</summary>

**Recommended starting points.** Selected by stated criteria, not a ranking of quality: Services in this pack with the most endpoints that match this bucket and passed a data call. Ties go to the service with more country codes, then by name. Only services with at least one bucket row that matches the focus rule are listed, and the sample comes from those rows; the counts cover the whole bucket. The sample URL is the first row by URL sort after preferring, in this order: rows that match the bucket's sample preference when it has one, rows that return values rather than describe a dataset or a service (not ERDDAP /info/ pages, OGC GetCapabilities requests, bare OWS addresses, PxWeb tables, UN SDG series lists, Statistics Canada download pointers, WorldPop listings, GTFS validation reports, untitled rows or service root addresses), and agent-ready rows. Services named "ArcGIS organization" hold map layers from many owners and are added only when fewer than 5 other services match.

| Service (host) | Endpoints in bucket | In pack | Country codes in bucket | Formats in bucket | Sample URL that passed |
|---|---:|---:|---|---|---|
| Esri Italia TM (ArcGIS Online) (services.arcgis.com) | 7 | 221 | IT | json | [Census\_Italia\_gdb - Istat\_Prov\_Sez](https://services.arcgis.com/nIbPrXGkjlJqLKTA/arcgis/rest/services/Census_Italia_gdb/FeatureServer/1/query?where=1%3D1&outFields=*&returnGeometry=false&resultRecordCount=5&f=json) (2026-11-16) |
| Unione Comuni Garfagnana (ArcGIS Online) (services9.arcgis.com) | 5 | 156 | IT | json | [zoning\_poi\_camporgiano\_ADD](https://services9.arcgis.com/Xd9huFXwXykJWlu1/ArcGIS/rest/services/zoning_poi_camporgiano_ADD/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| TeamDev (ArcGIS Online) (services.arcgis.com) | 4 | 75 | IT | json | [Historic boundaries - 1815 d.C.](https://services.arcgis.com/C8K37aOKTOQQvitW/arcgis/rest/services/Historic_boundaries/FeatureServer/1/query?where=1%3D1&outFields=*&returnGeometry=false&resultRecordCount=5&f=json) (2026-11-16) |
| Roma Servizi per la Mobilità s.r.l. (ArcGIS Online) (services2.arcgis.com) | 1 | 142 | IT | json | [PT\_RM\_Parcel\_Locker\_e\_Punti\_di\_ritiro\_c…](https://services2.arcgis.com/NZMqCJwY3kMjFOqf/ArcGIS/rest/services/PT_RM_Parcel_Locker_e_Punti_di_ritiro_consegna_UP/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| ArcGIS Online layers (services2.arcgis.com, org qpFFG6wHMKCXpc0N) | 2 | 260 | IT | json | [statistiche\_zonali](https://services2.arcgis.com/qpFFG6wHMKCXpc0N/ArcGIS/rest/services/statistiche_zonali/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |

</details>

### 🧪 Evals and testing: Varied responses to test tool calls and parsers

**7,336** endpoints · 242 services · country IT · 1 format · Run your tool calls against a fixed set of URLs across formats and record which answer; last_tested is the baseline for your own re-tests.

Start with: the whole pack

Example: [161miglia\_lunga\_2024](https://services3.arcgis.com/mFSogUeqpAu2uWFw/ArcGIS/rest/services/161miglia_lunga_2024/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) · ArcGIS Online layers (services3.arcgis.com, org mFSogUeqpAu2uWFw) · passed 2026-11-16

<details>
<summary>Recommended starting points: 8 services, picked by the stated criteria inside</summary>

**Recommended starting points.** Selected by stated criteria, not a ranking of quality: Services in this pack that returned the most different formats, then the most endpoints that passed a data call, then by name: a mix of response shapes to test parsers and tool calls. Here the services returned 1 format each, so the order comes down to endpoint counts. Only services with at least one bucket row that matches the focus rule are listed, and the sample comes from those rows; the counts cover the whole bucket. The sample URL is the first row by URL sort after preferring, in this order: rows that match the bucket's sample preference when it has one, rows that return values rather than describe a dataset or a service (not ERDDAP /info/ pages, OGC GetCapabilities requests, bare OWS addresses, PxWeb tables, UN SDG series lists, Statistics Canada download pointers, WorldPop listings, GTFS validation reports, untitled rows or service root addresses), and agent-ready rows. Services named "ArcGIS organization" hold map layers from many owners and are added only when fewer than 5 other services match.

| Service (host) | Endpoints in bucket | In pack | Country codes in bucket | Formats in bucket | Sample URL that passed |
|---|---:|---:|---|---|---|
| Agenzia ARPA Sardegna (ArcGIS Online) (services6.arcgis.com) | 334 | 334 | IT | json | [A\_RISCHIO\_NJ](https://services6.arcgis.com/VdOe78ROZ6pyB2c8/ArcGIS/rest/services/A_RISCHIO_NJ/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Esri Italia TM (ArcGIS Online) (services.arcgis.com) | 221 | 221 | IT | json | [Aree\_Archeologiche\_Lazio](https://services.arcgis.com/nIbPrXGkjlJqLKTA/ArcGIS/rest/services/Aree_Archeologiche_Lazio/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| I.D.T. della Lombardia (ArcGIS Online) (services1.arcgis.com) | 184 | 184 | IT | json | [ALBO\_OF\_ACCR\_ATECO](https://services1.arcgis.com/XannvQVnsM1hoZyv/ArcGIS/rest/services/ALBO_OF_ACCR_ATECO/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Unione Comuni Garfagnana (ArcGIS Online) (services9.arcgis.com) | 156 | 156 | IT | json | [AP](https://services9.arcgis.com/Xd9huFXwXykJWlu1/ArcGIS/rest/services/AP/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Roma Servizi per la Mobilità s.r.l. (ArcGIS Online) (services2.arcgis.com) | 142 | 142 | IT | json | [117](https://services2.arcgis.com/NZMqCJwY3kMjFOqf/ArcGIS/rest/services/117/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Istituto Nazionale di Geofisica e Vulcanologia (ArcGIS Online) (services1.arcgis.com) | 119 | 119 | IT | json | [10\_anniversario\_Emilia\_19\_5\_2012\_19\_7\_2…](https://services1.arcgis.com/z0Oh0igg7i25Y3AM/ArcGIS/rest/services/10_anniversario_Emilia_19_5_2012_19_7_2012/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| Save the Children Italia (ArcGIS Online) (services3.arcgis.com) | 87 | 87 | IT | json | [Centri\_antiviolenza\_case\_rifugio\_tasso\_…](https://services3.arcgis.com/jiXW75yUEzuPStZi/ArcGIS/rest/services/Centri_antiviolenza_case_rifugio_tasso_per_100000_donne_14_anni_e_piu_Regione_e_PA/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |
| TeamDev (ArcGIS Online) (services.arcgis.com) | 75 | 75 | IT | json | [Buffer cromotropiche](https://services.arcgis.com/C8K37aOKTOQQvitW/ArcGIS/rest/services/Buffer%20cromotropiche/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (2026-11-16) |

</details>

The same lists are in [recommended.json](recommended.json), ready for an agent to load.

## Questions an agent can answer with this pack

- Which environmental layers does ARPA Sardegna publish? Try [A\_RISCHIO\_NJ](https://services6.arcgis.com/VdOe78ROZ6pyB2c8/ArcGIS/rest/services/A_RISCHIO_NJ/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (Agenzia ARPA Sardegna (ArcGIS Online), passed 2026-11-16).
- Which layers does the national geophysics and volcanology institute publish? Try [10\_anniversario\_Emilia\_19\_5\_2012\_19\_7\_2012](https://services1.arcgis.com/z0Oh0igg7i25Y3AM/ArcGIS/rest/services/10_anniversario_Emilia_19_5_2012_19_7_2012/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (Istituto Nazionale di Geofisica e Vulcanologia (ArcGIS Online), passed 2026-11-16).
- Which layers does the Garfagnana union of municipalities publish? Try [AP](https://services9.arcgis.com/Xd9huFXwXykJWlu1/ArcGIS/rest/services/AP/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) (Unione Comuni Garfagnana (ArcGIS Online), passed 2026-11-16).

## What "passed a data call" means

> [!NOTE]
> On the date in `last_tested` (IST), one GET to the URL, sent with no key, returned HTTP 2xx and a non-empty data body. HTML pages and empty results did not pass. The `format` column records what came back. This is a test result for that date, not a promise that the URL answers today. Licences, terms, rate limits, accuracy and freshness were not reviewed. Endpoints are URLs, not separate APIs; many share one service. This pack was tested 16–17 Nov 2026; snapshot 16 Nov 2026.

## For AI agents

Start from keyless JSON endpoints (`agent-ready`). The code below loads `recommended.json` and calls the first recommended service in the Agent tools bucket, with a timeout (`node examples/agent-start.mjs --recommended`). With no argument, `node examples/agent-start.mjs` calls the most recently tested agent-ready row of the sample; pass a `.csv` or `.csv.gz` path to use that file instead. See [examples/agent-start.mjs](examples/agent-start.mjs).

```js
// Node 18+. Loads recommended.json (the local copy, or the raw file on GitHub) and calls one keyless JSON endpoint.
import fs from 'node:fs';

const RAW = 'https://raw.githubusercontent.com/agentpopulation/7.3k-italy-apis-for-agents/main/recommended.json';
const rec = fs.existsSync('recommended.json')
  ? JSON.parse(fs.readFileSync('recommended.json', 'utf8'))
  : await (await fetch(RAW)).json();

const pick = rec.buckets.find((b) => b.id === 'agent').services[0];
try {
  const res = await fetch(pick.sample_url, {
    headers: { 'User-Agent': 'agent-example/1.0' },
    signal: AbortSignal.timeout(15000),
  });
  console.log(pick.service, res.status, res.headers.get('content-type'));
  console.log((await res.text()).slice(0, 300));
} catch (err) {
  console.log(`did not answer now; last passed ${pick.sample_last_tested} (${err.message})`);
}
```

How an agent picks an endpoint:

1. Filter to `agent-ready` and your country or topic.
2. Prefer the newest `last_tested` and the larger services.
3. Call with a timeout and check the body before you use it.

## Quick start

The examples run against the sample in `data/` out of the box (1,000 rows). Each takes an optional path to a `.csv` or `.csv.gz` file instead.

```bash
git clone https://github.com/agentpopulation/7.3k-italy-apis-for-agents.git
cd 7.3k-italy-apis-for-agents
python examples/quickstart.py
node examples/quickstart.mjs
node examples/agent-start.mjs
```

Full list: download `Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz` (7,336 rows, 121.5 kB) from [releases/latest](https://github.com/agentpopulation/7.3k-italy-apis-for-agents/releases/latest), then gunzip it and pass its path. The scripts also read the `.csv.gz` as it is.

```bash
gunzip Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz
python examples/quickstart.py Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv
node examples/quickstart.mjs Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv
```

### curl

Quote the URL: some contain commas.

```bash
curl -sL "https://raw.githubusercontent.com/agentpopulation/7.3k-italy-apis-for-agents/main/data/Italy_API_Endpoints_AgentPopulation_Sample.csv" | head -n 4
curl -s --max-time 15 "https://services3.arcgis.com/mFSogUeqpAu2uWFw/ArcGIS/rest/services/161miglia_lunga_2024/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json" | head -c 600
```

### Python

Standard library only: [examples/quickstart.py](examples/quickstart.py) reads the sample, or the path you pass, keeps agent-ready rows and calls the most recently tested one.

<details>
<summary>The code</summary>

```python
# Python 3, standard library only. Run from a clone of this repository:
#   python examples/quickstart.py [path]
# With no path it reads the sample in data/. Pass the full list from the latest release (.csv or .csv.gz) instead.
# Keeps agent-ready rows and calls the most recently tested one.
import csv
import gzip
import os
import re
import sys
import urllib.request

HERE = os.path.dirname(os.path.abspath(__file__))
path = sys.argv[1] if len(sys.argv) > 1 else os.path.join(HERE, "..", "data", "Italy_API_Endpoints_AgentPopulation_Sample.csv")
opener = gzip.open if path.endswith(".gz") else open
with opener(path, "rt", newline="", encoding="utf-8") as f:
    rows = list(csv.DictReader(f))

agent = [r for r in rows if "agent-ready" in r["tags"].split("|")]
# Newest test date first; URLs that describe a dataset or a service rather than return values go last.
DESCRIBES = re.compile(r"/erddap/info/|action-report\.json$|[?&]request=getcapabilities|/GeoArea/[^/?]+/List|getFullTableDownloadCSV|hub\.worldpop\.org", re.I)
agent.sort(key=lambda r: r["last_tested"], reverse=True)
agent.sort(key=lambda r: 1 if DESCRIBES.search(r["url"]) else 0)
print(len(rows), "rows,", len(agent), "agent-ready")
if not agent:
    sys.exit(0)

row = agent[0]
req = urllib.request.Request(row["url"], headers={"User-Agent": "agent-example/1.0"})
try:
    with urllib.request.urlopen(req, timeout=15) as res:
        body = res.read(1_000_000).decode("utf-8", "replace")
        print(res.status, res.headers.get("Content-Type"))
        print(body[:300])
except Exception as err:
    print(f"did not answer now; last passed {row['last_tested']} ({err})")
```

</details>

### JavaScript

Reads the sample as JSON because the CSV has quoted commas.

<details>
<summary>The code</summary>

```js
// Node 18+. Reads the sample as JSON (the CSV has quoted commas), local file first.
import fs from 'node:fs';

const FILE = 'data/Italy_API_Endpoints_AgentPopulation_Sample.json';
const rows = fs.existsSync(FILE)
  ? JSON.parse(fs.readFileSync(FILE, 'utf8'))
  : await (await fetch('https://raw.githubusercontent.com/agentpopulation/7.3k-italy-apis-for-agents/main/data/Italy_API_Endpoints_AgentPopulation_Sample.json')).json();

const row = rows.find((r) => r.tags.includes('agent-ready'));
const res = await fetch(row.url, { headers: { 'User-Agent': 'agent-example/1.0' }, signal: AbortSignal.timeout(15000) });
console.log(res.status, (await res.text()).slice(0, 300));
```

</details>

### Agent tools

[examples/agent-tools.json](examples/agent-tools.json) holds two tool definitions in the shape most tool-calling APIs accept (name, description, JSON Schema); rename `parameters` if yours uses another key. [examples/quickstart.mjs](examples/quickstart.mjs) implements them:

- `find_endpoints` searches the agent-ready rows of the list by words (their format is json). When you load the tools of more than one pack, prefix the names (for example `italy_find_endpoints`) so they do not clash.
- `fetch_endpoint` calls one URL, **refuses any URL that is not in the list** and does not follow redirects. The allowlist is built from the CSV, so a URL injected into a prompt is refused.

The same two tools can sit behind an MCP server.

## Test it yourself

Re-test endpoints from the sample with the same rule: HTTP 2xx and a non-empty body that is not an HTML page. Node 18+, no packages.

```bash
node tools/test-endpoints.mjs
```

It tests the first 50 URLs and prints one line: tested, passed, did not pass. Options: a `.csv` or `.csv.gz` path (the full list from the release), `--limit 50`, `--timeout-ms 10000`, `--out results.csv`. The results file holds `url`, `status`, `passed`, `content_type`, `ms` and `checked_at`; a status of `timeout` or `error:<code>` means no HTTP answer came back. It is polite: GET only, no key sent, at most 4 requests in flight, one at a time per listed host, at least 1 second between requests to one listed host, and reading stops once 256 kB of a body is kept. Redirects are followed and may lead to another host. `results.csv` is in `.gitignore`.

## Preview

One row from each of the five largest services among rows that match the focus rule, services with rows that return values first.

| Title | Service | Country | Format | Tested | Link |
|---|---|---|---|---|---|
| 161miglia\_lunga\_2024 | ArcGIS Online layers (services3.arcgis.com, org mFSogUeqpAu2uWFw) | IT | json | 2026-11-16 | [services3.arcgis.com](https://services3.arcgis.com/mFSogUeqpAu2uWFw/ArcGIS/rest/services/161miglia_lunga_2024/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) |
| 01VIENLAK\_aoi\_from\_pro | ArcGIS Online layers (services9.arcgis.com, org rNFYfizUMWjwfBKB) | IT | json | 2026-11-16 | [services9.arcgis.com](https://services9.arcgis.com/rNFYfizUMWjwfBKB/ArcGIS/rest/services/01VIENLAK_aoi_from_pro/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) |
| 2\_Esportazioni\_nazionali\_di\_medicinali\_e\_preparati\_farmaceu… | ArcGIS Online layers (services1.arcgis.com, org P14CytrnPG76qvy4) | IT | json | 2026-11-16 | [services1.arcgis.com](https://services1.arcgis.com/P14CytrnPG76qvy4/ArcGIS/rest/services/2_Esportazioni_nazionali_di_medicinali_e_preparati_farmaceuticiweb/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) |
| A\_RISCHIO\_NJ | Agenzia ARPA Sardegna (ArcGIS Online) | IT | json | 2026-11-16 | [services6.arcgis.com](https://services6.arcgis.com/VdOe78ROZ6pyB2c8/ArcGIS/rest/services/A_RISCHIO_NJ/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) |
| 01\_Grafo\_WS | ArcGIS Online layers (services9.arcgis.com, org sLhbzMfPyJ0d1KLB) | IT | json | 2026-11-16 | [services9.arcgis.com](https://services9.arcgis.com/sLhbzMfPyJ0d1KLB/ArcGIS/rest/services/01_Grafo_WS/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) |

Browse the 1,000-row sample: [Sample CSV](data/Italy_API_Endpoints_AgentPopulation_Sample.csv) · [Sample JSON](data/Italy_API_Endpoints_AgentPopulation_Sample.json).

## What's inside

<p align="center"><img src="assets/breakdown.svg" width="100%" alt="Top categories and formats in this pack"></p>

<details>
<summary>Categories: top 8</summary>

| Category | Endpoints | |
|---|---:|---|
| Navigation & Geo/Maps | 3,664 | `████████████████████` |
| Government & Open Data | 2,859 | `███████████████▋` |
| Transport & Mobility | 296 | `█▋` |
| Weather & Climate | 190 | `█` |
| Environment | 96 | `▌` |
| Statistics & Economy | 61 | `▍` |
| Hazards | 56 | `▎` |
| Health | 45 | `▎` |

</details>

Formats: json 7,336

<details>
<summary>Largest services: top 25 of 242</summary>

| Service | Host | Endpoints | Keyless JSON | |
|---|---|---:|---:|---|
| ArcGIS Online layers (services3.arcgis.com, org mFSogUeqpAu2uWFw) | services3.arcgis.com | 1,031 | 1,031 | `████████████████████` |
| ArcGIS Online layers (services9.arcgis.com, org rNFYfizUMWjwfBKB) | services9.arcgis.com | 705 | 705 | `█████████████▋` |
| ArcGIS Online layers (services1.arcgis.com, org P14CytrnPG76qvy4) | services1.arcgis.com | 359 | 359 | `███████` |
| Agenzia ARPA Sardegna (ArcGIS Online) | services6.arcgis.com | 334 | 334 | `██████▌` |
| ArcGIS Online layers (services9.arcgis.com, org sLhbzMfPyJ0d1KLB) | services9.arcgis.com | 292 | 292 | `█████▋` |
| ArcGIS Online layers (services2.arcgis.com, org qpFFG6wHMKCXpc0N) | services2.arcgis.com | 260 | 260 | `█████` |
| Esri Italia TM (ArcGIS Online) | services.arcgis.com | 221 | 221 | `████▎` |
| ArcGIS Online layers (services-eu1.arcgis.com, org 8xuX5Sd1CVbIn9Qt) | services-eu1.arcgis.com | 214 | 214 | `████▏` |
| ArcGIS Online layers (services2.arcgis.com, org G0nODslWoUztnex2) | services2.arcgis.com | 204 | 204 | `████` |
| I.D.T. della Lombardia (ArcGIS Online) | services1.arcgis.com | 184 | 184 | `███▋` |
| ArcGIS Online layers (services7.arcgis.com, org MBHOerVQTRxiVUHo) | services7.arcgis.com | 176 | 176 | `███▍` |
| Unione Comuni Garfagnana (ArcGIS Online) | services9.arcgis.com | 156 | 156 | `███` |
| Roma Servizi per la Mobilità s.r.l. (ArcGIS Online) | services2.arcgis.com | 142 | 142 | `██▊` |
| ArcGIS Online layers (services6.arcgis.com, org RnHgzl8dqjG7J4Kx) | services6.arcgis.com | 139 | 139 | `██▊` |
| ArcGIS Online layers (services3.arcgis.com, org 0sSveCy2kRu5xgwW) | services3.arcgis.com | 132 | 132 | `██▌` |
| Istituto Nazionale di Geofisica e Vulcanologia (ArcGIS Online) | services1.arcgis.com | 119 | 119 | `██▎` |
| ArcGIS Online layers (services-eu1.arcgis.com, org 6vX5VUfaAYOP3Im3) | services-eu1.arcgis.com | 109 | 109 | `██▏` |
| ArcGIS Online layers (services3.arcgis.com, org fk8H6ZIXghEo5UZA) | services3.arcgis.com | 90 | 90 | `█▊` |
| Save the Children Italia (ArcGIS Online) | services3.arcgis.com | 87 | 87 | `█▊` |
| ArcGIS Online layers (services3.arcgis.com, org GS5pg5GvYXCMCEen) | services3.arcgis.com | 82 | 82 | `█▋` |
| ArcGIS Online layers (services5.arcgis.com, org RmYo81Av6MFMIHuo) | services5.arcgis.com | 79 | 79 | `█▌` |
| TeamDev (ArcGIS Online) | services.arcgis.com | 75 | 75 | `█▌` |
| Esri Italia (ArcGIS Online) | services.arcgis.com | 73 | 73 | `█▍` |
| Global to Local to Global (ArcGIS Online) | services3.arcgis.com | 69 | 69 | `█▍` |
| ArcGIS Online layers (services-eu1.arcgis.com, org Y7y8AbJJ842Nq7ZT) | services-eu1.arcgis.com | 64 | 64 | `█▎` |

</details>

<details>
<summary>Rows per test date: 16–17 Nov 2026</summary>

| Date (IST) | Endpoints | |
|---|---:|---|
| 2026-11-17 | 41 | `▏` |
| 2026-11-16 | 7,295 | `████████████████████` |

</details>

## Files

| File | Rows | Size | Use |
|---|---:|---:|---|
| [data/Italy_API_Services_AgentPopulation.csv](data/Italy_API_Services_AgentPopulation.csv) | 242 | 15.7 kB | One row per service with its endpoint count in this pack |
| [data/Italy_API_Endpoints_AgentPopulation_Sample.csv](data/Italy_API_Endpoints_AgentPopulation_Sample.csv) | 1,000 | 321.5 kB | The sample: focus-rule rows first, each service in proportion to its share; ArcGIS Online layers count as one service |
| [data/Italy_API_Endpoints_AgentPopulation_Sample.json](data/Italy_API_Endpoints_AgentPopulation_Sample.json) | 1,000 | 504.4 kB | The same rows as JSON, tags as an array |
| [Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz](https://github.com/agentpopulation/7.3k-italy-apis-for-agents/releases/latest) | 7,336 | 121.5 kB | The full list, gzipped CSV: a download from the latest release, checked by `SHA256SUMS.txt` |
| [tools/test-endpoints.mjs](tools/test-endpoints.mjs) | | | Re-tests endpoints from the sample or the full list |

Sample size: 1,000 rows, which is 1,000 or one third of the pack rounded down, whichever is smaller. Rows that match the focus rule come first. Each service gets rows in proportion to its share of those rows, at least one for the largest services and at most 50% of the sample while other services have rows; ArcGIS Online layers count as one service, whatever their organisation. Within a service, agent-ready rows, rows that return values and the newest test dates come first, and rows are written in turn across services. Service root addresses are placed at the end of the sample.

Full list: download `Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz` (7,336 rows, 121.5 kB) from [releases/latest](https://github.com/agentpopulation/7.3k-italy-apis-for-agents/releases/latest), then gunzip it and pass its path. The scripts also read the `.csv.gz` as it is.

Excel users: Data > From Text/CSV, UTF-8. Files are UTF-8 without a byte-order mark and comma-separated.

## Columns and tags

<details>
<summary>Columns, types and tags</summary>

| Column | Type | Example | Meaning |
|---|---|---|---|
| url | string | [https://services3.arcgis.com/mFSogUeqpA…](https://services3.arcgis.com/mFSogUeqpAu2uWFw/ArcGIS/rest/services/161miglia_lunga_2024/FeatureServer/0/query?where=1%3D1&outFields=*&resultRecordCount=10&f=json) | The address that was tested |
| title | string | 161miglia\_lunga\_2024 | Station, dataset or feed name |
| service | string | ArcGIS Online layers (services3.arcgis.… | The service the endpoint belongs to; joins to the services file together with host |
| host | string | services3.arcgis.com | Host name of the address |
| country | string | IT | ISO 3166-1 alpha-2 code, or EU; empty when global or unknown |
| category | string | Navigation & Geo/Maps | Category of the endpoint |
| subcategory | string |  | Left empty from the 15 Nov 2026 snapshot; kept so the columns stay the same |
| format | string | json | What the test call returned: json, csv, geojson, xml, gtfs, zip, txt and so on |
| tags | string | `no-key\|json\|agent-ready` | Tags separated by \| |
| last_tested | date | 2026-11-16 | Date of the test call, YYYY-MM-DD (IST) |

| Tag | Rows | Meaning |
|---|---:|---|
| agent-ready | 7,336 | No key sent, JSON body, passed a data call on last_tested |
| json | 7,336 | Format of the body |
| no-key | 7,336 | No key was sent in the test call |

A machine-readable copy of this dictionary is in [datapackage.json](datapackage.json).

</details>

## Known limits

- 7,336 rows are map-layer queries with resultRecordCount set: the tested call asked for a few records; change the query to get the full layer.
- 7,277 rows are layers on ArcGIS Online, where anyone can publish: some are class projects, tests or copies. Check the owner and the fields before you rely on one. Layers whose titles read as a test, draft or copy are not used as starting points; named organisations come first in the recommended lists.
- 153 rows have a title that reads as a test, a draft, a copy or a sample; they are not used as starting points.
- The country code (IT) is the code the endpoint is filed under, not the place the data covers and not always the publisher's country. Where a row had no code, the code of its ArcGIS organisation is used when that organisation lists one country only. In a sample of 14 titles read before release, none was about a place outside Italy. Filter by title or service if you need data about one place.
- Stations and feeds can go quiet after their test date; re-test a URL before you rely on it.
- Not in this pack: endpoints that need a key or a POST, and URLs that did not pass.
- Left out: 100 ArcGIS Survey123 layers (they can hold people's form answers).
- Left out: 18 ArcGIS layers that keep a form's default service name (they can hold people's form answers).
- Left out: 84 ArcGIS class or coursework layers (lab, assignment, exam, quiz, lesson, exercise, tutorial and final-project layers, copies of class layers, layers named for a person or a person's home, and layers whose name ends in a person's name or holds a student number).
- Left out: 5 ArcGIS layers that hold reports, comments, submissions or form responses sent in by the public.
- Left out: 25 rows of class sets: one map layer saved under 5 or more students' initials or names in one ArcGIS Online organisation, or in 4 or more students' own organisations.
- Left out: 1,113 rows of university, college and school organisations and hosts (many of their layers are students' work).
- Left out: 2,180 rows that are another address form of an ArcGIS layer already in an earlier pack of the collection (the same rows under another query).
- Left out: 2,147 rows that are a second address form of an ArcGIS layer in this list (the same rows under another query); one address is kept per layer, the newest test first.

## Licence and credit

> [!IMPORTANT]
> This list (URLs, titles, tags and test results) is © 2026 AgentPopulation, released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit AgentPopulation and link agentpopulation.com. The data each endpoint returns belongs to its provider and stays under that provider's terms; this licence does not cover it.

Copy-ready credit:

`Italy API endpoints by AgentPopulation (https://agentpopulation.com), CC BY 4.0, snapshot 16 Nov 2026.`

GitHub's "Cite this repository" button reads [CITATION.cff](CITATION.cff).

<!-- agentpopulation:start -->
## Part of 10M API endpoints for AI agents

This pack is one of the 50 topic packs of [10m-open-apis-for-ai-agents](https://github.com/agentpopulation/10m-open-apis-for-ai-agents), the open collection by [AgentPopulation](https://agentpopulation.com). Target: 10 million+ open API endpoints that pass a keyless API call.

AgentPopulation's test run of 16 Nov 2026: 4,452,803 tested, 3,346,053 passed a data call. This is the Italy pack: 7,336 endpoints from 242 services, none of them in a pack read from the earlier snapshot, by address or as another address of the same map layer. Packs overlap, so an endpoint can appear in more than one.

For the latest tested endpoints, search [agentpopulation.com/apis](https://agentpopulation.com/apis). This pack is a snapshot from 16 Nov 2026.

Sibling packs that share the most URLs with this one: [59k-europe-region-arcgis-apis-for-agents](https://github.com/agentpopulation/59k-europe-region-arcgis-apis-for-agents) (1,000 shared) · [25k-arcgis-server-apis-for-agents](https://github.com/agentpopulation/25k-arcgis-server-apis-for-agents) (59 shared) · [160k-county-and-city-gis-apis-for-agents](https://github.com/agentpopulation/160k-county-and-city-gis-apis-for-agents) (23 shared) · [47k-public-agency-gis-apis-for-agents](https://github.com/agentpopulation/47k-public-agency-gis-apis-for-agents) (7 shared). The rest are listed in [10m-open-apis-for-ai-agents](https://github.com/agentpopulation/10m-open-apis-for-ai-agents).

Questions, pack requests, reports of endpoints that stopped answering and requests to remove a row go to [Discussions](https://github.com/agentpopulation/10m-open-apis-for-ai-agents/discussions), or to [@agentpopulation](https://x.com/agentpopulation) on X. The packs are a work in progress and corrections are welcome.

Spotted a wrong row or a dead URL? Tell us on X: [@agentpopulation](https://x.com/agentpopulation).

If this pack saved you time, a star helps others find it.

---

Compiled by [AgentPopulation](https://agentpopulation.com) with [AP Desk](https://github.com/agentpopulation/apdesk) · [10m-open-apis-for-ai-agents](https://github.com/agentpopulation/10m-open-apis-for-ai-agents)

<!-- agentpopulation:end -->
