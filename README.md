# 供应商勘察地图

Public GitHub Pages package for the canonical `20260322-seven-factory-deep` supplier field-scout map.

- Source map: `field-scout-map.html`
- Default entry: `index.html`
- Runtime: static HTML with AMap Web JS API
- Deployment URL: `https://waynejapan.github.io/supplier-field-scout-map/`

## Mobile Field Notes

- The top status strip summarizes enabled suppliers, A/B priority count, and coordinate caveats.
- The side panel mirrors the Penang trip-map pattern: route overview, trust-level legend, and a checklist-style supplier sequence.
- A/B/C labels are research confidence and follow-up priority, not final supplier qualification.
- `苏州瑞杰服饰绣花厂` is corrected to a Suzhou Yuexi township-level coordinate in this deployment; confirm the exact door address by phone before field travel.
- AMap live routing is the driving authority during use. Cached shell files help repeat access, but route tiles, geolocation, POI search, and navigation handoff still require network access.
