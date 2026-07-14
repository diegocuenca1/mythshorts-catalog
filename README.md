# MythShorts catalog

Public, source-bounded story catalog for MythShorts.

`myth-catalog.json` is deliberately data-only: the iPhone downloads it, caches it locally, and tracks used story IDs on-device. Each entry has a concise set of reviewable facts and source context; the app turns those facts into a Short script rather than reading a database entry aloud.

## Updating the catalog

From the MythShorts project, run:

```bash
node scripts/build-myth-catalog.js catalog/myth-catalog.json
```

Review changes before publishing. Do not add API keys, private data, or copied source text to this repository.
