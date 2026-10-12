# Bluebird sites catalog

Static `sites.json` for the Bluebird Vic dive app (GitHub Pages).

**Public URL:** https://adriantanz.github.io/bluebird-sites/sites.json

## Schema

```json
{
  "version": 1,
  "updatedAt": "ISO-8601",
  "sites": [{ "id": "slug", "name": "Display name", "lat": -38.0, "lng": 145.0 }]
}
```

Add a site by appending an object and pushing to `main`. The app fetches this on boot and fills scoring/UI defaults locally for unknown IDs.
