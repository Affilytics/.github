<picture>
  <source media="(prefers-color-scheme: light)" srcset="./assets/header.png">
  <img alt="Affilytics — Affiliate link geo-routing and broken-link monitoring, built in Rust" src="./assets/header-dark.png" width="100%">
</picture>

# Affilytics

**Affiliate link infrastructure for content creators: geo-routed smart links, link-health monitoring, and an MCP server for AI-agent workflows.**

Most creators link to Amazon.com by default, but a large share of their audience is international. Those clicks land on the wrong regional store and the commission disappears. Affilytics geo-routes every affiliate click to the visitor's local retailer so the sale is kept, then scans a creator's full YouTube and blog footprint and flags links that have gone broken, out-of-stock, or attribution-lost, with a weekly email digest.

## What it does

- **Geo-routed smart links:** every click resolves to the visitor's country and routes to the correct regional retailer.
- **Full-footprint link discovery:** scans YouTube channels and blogs to find every affiliate link a creator has already published, across most networks.
- **Continuous health monitoring:** flags broken, out-of-stock, attribution-lost, and blocked links, not just simple 404s.
- **MCP server (shipping):** Claude, Cursor, and any MCP client can audit a channel, build geo-routed smart links, and spot lost traffic from inside the editor, using the same data the dashboard uses.

## Built as real infrastructure

Affilytics is production software built by senior engineers, not an AI wrapper. The link-health and routing engine does stealth HTTP checking, proxy rotation, WAF detection, and GeoIP routing across three independent Rust services.

Free Starter at $0/mo (1 channel, 14 days of full Pro to start) or Pro at $9/mo flat (10 channels, unlimited smart links). No credit card on the free plan.

[affilytics.io](https://affilytics.io)
