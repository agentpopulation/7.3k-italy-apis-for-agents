## Italy API endpoints, snapshot 16 Nov 2026

- 7,336 endpoints passed a keyless data call, tested 16–17 Nov 2026 (IST)
- 242 services · country IT · 7,336 keyless JSON rows

### Download

- `Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz`: the full list, 7,336 rows, 121.5 kB gzipped (2.4 MB as CSV), SHA-256 `2aae663ad050e91bb1468ab165abb934f1b6401a724353d5686dfb02e7b12890`
- `SHA256SUMS.txt`: the checksum of that file

Check the download in the folder that holds both files:

```bash
sha256sum -c SHA256SUMS.txt          # Linux
shasum -a 256 -c SHA256SUMS.txt      # macOS
certutil -hashfile Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz SHA256   # Windows: compare with SHA256SUMS.txt
```

Then `gunzip Italy_API_Endpoints_AgentPopulation_Snapshot_2026-11-16.csv.gz` and pass the CSV path to the examples or to `node tools/test-endpoints.mjs`. The repository itself holds a 1,000-row sample and the services list.

### What's in it for you

- 🤖 Agent tools: 7,336 · Wrap one layer query as a get_layer_features tool: pass a where clause or a bounding box, return the matching features with a timeout.
- 📱 App features: 7,336 · Add the layers to an app map: read the layer once for its fields, then ask for the features in the visible area.
- 🧠 Grounding and data pipelines: 23 · Load the tables and layers on a schedule into your own store, so an agent can cite a dated source.
- 🧪 Evals and testing: 7,336 · Run your tool calls against a fixed set of URLs across formats and record which answer; last_tested is the baseline for your own re-tests.

### Changes

- First release
- Left out: 100 ArcGIS Survey123 layers (they can hold people's form answers).
- Left out: 18 ArcGIS layers that keep a form's default service name (they can hold people's form answers).
- Left out: 84 ArcGIS class or coursework layers (lab, assignment, exam, quiz, lesson, exercise, tutorial and final-project layers, copies of class layers, layers named for a person or a person's home, and layers whose name ends in a person's name or holds a student number).
- Left out: 5 ArcGIS layers that hold reports, comments, submissions or form responses sent in by the public.
- Left out: 25 rows of class sets: one map layer saved under 5 or more students' initials or names in one ArcGIS Online organisation, or in 4 or more students' own organisations.
- Left out: 1,113 rows of university, college and school organisations and hosts (many of their layers are students' work).
- Left out: 2,180 rows that are another address form of an ArcGIS layer already in an earlier pack of the collection (the same rows under another query).
- Left out: 2,147 rows that are a second address form of an ArcGIS layer in this list (the same rows under another query); one address is kept per layer, the newest test first.
- Overlap: 1,000 of these URLs are also in 59k-europe-region-arcgis-apis-for-agents.
- Overlap: 23 of these URLs are also in 160k-county-and-city-gis-apis-for-agents.
- Overlap: 7 of these URLs are also in 47k-public-agency-gis-apis-for-agents.
- Overlap: 59 of these URLs are also in 25k-arcgis-server-apis-for-agents.

On the date in last_tested (IST), one GET to the URL, sent with no key, returned HTTP 2xx and a non-empty data body. HTML pages and empty results did not pass. The format column records what came back. This is a test result for that date, not a promise that the URL answers today. Licences, terms, rate limits, accuracy and freshness were not reviewed. Endpoints are URLs, not separate APIs; many share one service. This pack was tested 16–17 Nov 2026; snapshot 16 Nov 2026.

For the latest tested endpoints, search agentpopulation.com/apis. This pack is a snapshot from 16 Nov 2026.

Credit: Italy API endpoints by AgentPopulation (https://agentpopulation.com), CC BY 4.0, snapshot 16 Nov 2026.

Compiled by [AgentPopulation](https://agentpopulation.com) with [AP Desk](https://github.com/agentpopulation/apdesk) · corrections: [@agentpopulation](https://x.com/agentpopulation) on X
