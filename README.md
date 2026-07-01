# infoblox-tif-blocklist

<p align="center">
  <img src="logo.png" alt="infoblox-tif-blocklist logo" width="160">
</p>

<p align="center">
  <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-blue.svg">
  <img alt="build" src="https://img.shields.io/badge/build-pass-green">
  <img alt="Last generation" src="https://img.shields.io/badge/last_generation-2026.07.01%2003%3A24%20UTC-brightgreen">
</p>

Automatically generated DNS blocklists based on the public Infoblox Threat Intelligence combined indicator list.

---

## Available lists

### Primary list

```text
https://raw.githubusercontent.com/ensmingera/infoblox-tif-blocklist/main/lists/infoblox-tif-adblock.txt
```

### Plain domain list

```text
https://raw.githubusercontent.com/ensmingera/infoblox-tif-blocklist/main/lists/infoblox-tif-domains.txt
```

### Machine-readable metadata

Includes generation details, conversion statistics, and SHA-256 checksums for the published blocklists.

```text
https://raw.githubusercontent.com/ensmingera/infoblox-tif-blocklist/main/lists/metadata.json
```

### SHA-256 checksums

```text
https://raw.githubusercontent.com/ensmingera/infoblox-tif-blocklist/main/lists/SHA256SUMS
```

---

## Philosophy

This project intentionally does **not** modify, score, enrich, or
supplement the upstream threat intelligence. The published entries are
sourced from the public Infoblox Threat Intelligence indicator list.

No additional indicators are added. No valid indicators are removed.

## Update Status

See `lists/metadata.json`.

## Source Data

https://github.com/infobloxopen/threat-intelligence

## License

MIT License
