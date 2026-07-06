<p align="center">
  <img src="https://ps.w.org/tablecrafter-wp-data-tables/assets/banner-1544x500.png" alt="TableCrafter" width="100%">
</p>

<h3 align="center">The data table engine for WordPress</h3>

<p align="center">Connect any data source. Display it beautifully. Let users edit, filter, and export without leaving the page.</p>

<p align="center">
  <a href="https://wordpress.org/plugins/tablecrafter-wp-data-tables/"><img src="https://img.shields.io/wordpress/plugin/v/tablecrafter-wp-data-tables?label=WordPress%20Plugin&color=0073aa" alt="Version"></a>
  &nbsp;
  <a href="https://wordpress.org/plugins/tablecrafter-wp-data-tables/#reviews"><img src="https://img.shields.io/wordpress/plugin/rating/tablecrafter-wp-data-tables?color=f0ad4e" alt="Rating"></a>
  &nbsp;
  <a href="https://github.com/TableCrafter/tablecrafter.js"><img src="https://img.shields.io/github/stars/TableCrafter/tablecrafter.js?style=social" alt="Stars"></a>
  &nbsp;
  <a href="https://github.com/TableCrafter/tablecrafter.js/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green" alt="License"></a>
</p>

<p align="center">
  <a href="https://wordpress.org/plugins/tablecrafter-wp-data-tables/"><strong>Get it free on WordPress.org</strong></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://tablecrafter.com/#pricing"><strong>Explore Pro at tablecrafter.com</strong></a>
</p>

---

<p align="center">
  <img src="https://ps.w.org/tablecrafter-wp-data-tables/assets/screenshot-1.png" alt="TableCrafter live table UI" width="90%">
</p>

---

## Two ways to use TableCrafter

|  | WordPress Plugin | JS Library |
|---|---|---|
| **Who it's for** | WordPress site owners and developers | Any web project, no WordPress required |
| **License** | Free tier on WordPress.org; Pro via Freemius | MIT, open source |
| **Install** | `wp plugin install tablecrafter-wp-data-tables --activate` | `npm install tablecrafter` or one CDN script tag |
| **Data sources** | 9 sources: Gravity Forms, Google Sheets, Airtable, Notion, JSON/REST, CSV, XML, Excel, external MySQL | Any JavaScript array or REST URL |
| **Key features** | Inline editing, role-based permissions, export, multi-select filters | Virtual scroll, formula columns, events API, i18n |
| **Trial** | 10 days free, no card required; 7-day refund guarantee | Free forever (MIT) |
| **Links** | [WordPress.org](https://wordpress.org/plugins/tablecrafter-wp-data-tables/) · [tablecrafter.com](https://tablecrafter.com/) | [GitHub](https://github.com/TableCrafter/tablecrafter.js) · [npm](https://www.npmjs.com/package/tablecrafter) |

---

## Quick start

### WordPress plugin

```bash
wp plugin install tablecrafter-wp-data-tables --activate
```

Then add `[tablecrafter id="1"]` to any post or page.

### JS library (CDN, no build step)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tablecrafter@2/dist/tablecrafter.css">
<script src="https://cdn.jsdelivr.net/npm/tablecrafter@2/dist/tablecrafter.umd.min.js"></script>
<script>
  new TableCrafter('#my-table', {
    data: '/api/data',
    columns: [{ field: 'name', label: 'Name', editable: true }],
  }).render();
</script>
```

---

## What ships in the box

- **9 data sources, zero custom connectors.** Gravity Forms, Google Sheets, Airtable, Notion, any JSON/REST endpoint, CSV, XML, Excel, and external MySQL all connect through the same UI.
- **Spreadsheet-grade inline editing.** 14 built-in cell editors, 15+ validation rules, bulk actions, and role-based edit permissions. No round-trip per keystroke.
- **Filters users actually use.** Text search, multi-select dropdowns, date ranges, and number ranges with automatic type detection on every column.
- **One-click export.** CSV, XLSX, and PDF export that respects the active filters and handles injection-safe RFC-4180 formatting automatically.
- **Mobile-first layout.** Rows collapse into readable cards at configurable breakpoints. No horizontal scroll, no layout debt.
- **Performance at scale.** Virtual scrolling, SWR caching, and selective script enqueue keep pages fast with thousands of rows.
- **Global-ready out of the box.** Six bundled locales (en, es, fr, de, ar, ur) and a full RTL layout flip for right-to-left languages.
- **Risk-free trial.** 10 days on Pro, no card required. 7-day no-questions refund after purchase.

---

## 🧩 The Crafter ecosystem

| Plugin | What it does |
|---|---|
| [TableCrafter Free](https://github.com/TableCrafter/tablecrafter-free) | Data tables from any source: filterable, editable, exportable |
| [CardCrafter](https://github.com/TableCrafter/cardcrafter-data-grids) | JSON into responsive card grids with Gutenberg support |
| [EventCrafter](https://github.com/TableCrafter/eventcrafter-visual-timeline) | Timelines, roadmaps, and event schedules |
| [LeadCrafter](https://github.com/TableCrafter/leadcrafter-lead-magnets) | Lead magnets with Kit.com integration |
| [WP Data Visualizer](https://github.com/TableCrafter/wp-data-visualizer) | Interactive Chart.js charts from JSON |
| [ChartCrafter](https://github.com/TableCrafter/chartcrafter) | Lightweight JS chart library built on Chart.js |

---

## 🔓 Open source at TableCrafter

**[tablecrafter.js](https://github.com/TableCrafter/tablecrafter.js)** is the MIT-licensed JavaScript library powering the rendering layer. It ships as ESM, CJS, and UMD, weighs ~27 KB min+gz, carries 970+ tests, and works in any framework or plain HTML page.

**[tablecrafter-free](https://github.com/TableCrafter/tablecrafter-free)** is the distribution repository for the free WordPress plugin. Every release is mirrored here and shipped to WordPress.org.

**What's next:** A v3 headless TypeScript rewrite of the JS library is in progress. Read the [v3 RFC](https://github.com/TableCrafter/tablecrafter.js/blob/main/docs/RFC-v3.md) for the roadmap and design decisions.

The Pro plugin develops in a private repository and ships via Freemius and WordPress.org.

---

## Built on solid principles

- **Source-agnostic:** the table UI is identical regardless of where the data lives
- **Performance first:** SWR caching, lazy loading, selective script enqueue
- **Security by design:** SSRF protection, capability checks, encrypted credential storage
- **Developer friendly:** PHP hooks, JS events API, custom data source API

---

<p align="center">
  <a href="https://wordpress.org/plugins/tablecrafter-wp-data-tables/"><strong>Get it free on WordPress.org</strong></a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://tablecrafter.com/#pricing"><strong>Explore Pro at tablecrafter.com</strong></a>
</p>

<p align="center">
  <a href="https://tablecrafter.com/">tablecrafter.com</a> &nbsp;·&nbsp;
  <a href="https://tablecrafter.com/docs/">Documentation</a> &nbsp;·&nbsp;
  <a href="https://tablecrafter.com/guides/">Guides</a> &nbsp;·&nbsp;
  <a href="https://wordpress.org/plugins/tablecrafter-wp-data-tables/">WordPress.org</a> &nbsp;·&nbsp;
  <a href="https://tablecrafter.com/support/">Support</a>
</p>
