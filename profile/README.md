# TableCrafter

[TableCrafter Official Website](https://tablecrafter.com/)

**WordPress data tools -- built for teams that work with real data.**

We make plugins that turn WordPress into a functional data layer. Filter, edit, export, and automate -- without leaving the page, writing custom code, or exporting to a spreadsheet.

---

## What Is Public Here

### [TableCrafter Free Plugin](https://github.com/TableCrafter/tablecrafter-free)

`tablecrafter-free` is the free plugin's distribution repository. Development happens upstream on a private source repo; every release is mirrored here and shipped to WordPress.org.

Display, filter, and inline-edit data from any source as a responsive frontend table.

**Supported data sources:**
- Gravity Forms entries
- WooCommerce orders and products
- Airtable bases
- Google Sheets (public and private)
- REST APIs and JSON endpoints
- MySQL custom tables
- CSV / Excel files

**Key capabilities:** Inline cell editing, role-based permissions, column-level visibility, live search and multi-select filters, CSV / XLSX / PDF export, data bars, status badges, email alerts, auto-refresh, bulk actions, entry duplication

**Links:**
- [WordPress.org listing](https://wordpress.org/plugins/tablecrafter-wp-data-tables/)
- [Documentation](https://tablecrafter.com/docs/)
- [Guides](https://tablecrafter.com/guides/)

**Pro version:** The Pro plugin is built on a private development repo. Releases ship via Freemius and WordPress.org. See [tablecrafter.com/#pricing](https://tablecrafter.com/#pricing) for plans and features.

---

### [tablecrafter.js](https://github.com/TableCrafter/tablecrafter.js)

Zero-dependency JavaScript data table library. Framework-agnostic, MIT-licensed, and under 27 KB min+gzipped.

Features include inline editing, advanced filters, formula columns, mobile card view, virtual scrolling, an events API, and heatmap visualization. Ships with 970+ tests.

npm package coming soon.

---

## The Ecosystem

| Plugin | What it does |
|---|---|
| [TableCrafter Free](https://github.com/TableCrafter/tablecrafter-free) | Data tables from any source -- filterable, editable, exportable |
| [CardCrafter](https://github.com/TableCrafter/cardcrafter-data-grids) | JSON into responsive card grids with Gutenberg support |
| [EventCrafter](https://github.com/TableCrafter/eventcrafter-visual-timeline) | Timelines, roadmaps, and event schedules |
| [LeadCrafter](https://github.com/TableCrafter/leadcrafter-lead-magnets) | Lead magnets with Kit.com integration |
| [WP Data Visualizer](https://github.com/TableCrafter/wp-data-visualizer) | Interactive Chart.js charts from JSON |

---

## Developer Libraries

| Library | What it does |
|---|---|
| [tablecrafter.js](https://github.com/TableCrafter/tablecrafter.js) | Standalone JS table library -- zero dependencies, API-ready |
| [ChartCrafter](https://github.com/TableCrafter/chartcrafter) | Lightweight JS chart library built on Chart.js |

---

## Philosophy

- **Source-agnostic:** the table UI is the same regardless of where the data lives
- **Performance first:** SWR caching, lazy loading, selective script enqueue
- **Security by design:** SSRF protection, capability checks, encrypted credential storage
- **Developer friendly:** PHP hooks, JS events, custom data source API
