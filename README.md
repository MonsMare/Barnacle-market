# Barnacle-market

Public **plugin-market index** for Barnacle on DeepSeek Harness (DSH).

This repository intentionally contains **metadata only**. The plugin code and
bundles are not published here: the index points to a private distribution
channel, and installation requires access granted by the copyright holder.

## Add the index to DSH

1. Open **Discover** in DSH.
2. **Manage index sources… → Add index source**.
3. Paste:

```
https://raw.githubusercontent.com/MonsMare/Barnacle-market/main/index.json
```

The index lists two bundles; install **Barnacle Team Bridge first**, then
**Barnacle** (the Bridge must be installed after the native Agent Teams bundle).
Both require DSH `0.2.1-rc.5`.

## Installation requires authorisation

Package installs pull from a private Git channel. A machine needs read access to
that channel (GitHub credentials granted by the copyright holder). Without that
access the market entry is visible but installation fails — by design.

## Licensing and copying

Barnacle is proprietary software. See [LICENSE](LICENSE). Copying, modification,
redistribution, sublicensing, or commercial use of the Barnacle software, its
bundles, its source code, or this index requires prior written permission from
the copyright holder. "Barnacle" and "Barnacle Hatchery" are project names of
the copyright holder.

Internal architecture, evidence, and design documents are kept out of this
repository on purpose.
