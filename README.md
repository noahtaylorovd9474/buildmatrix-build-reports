# BuildMatrix - DevOps Reporting Tool 2026

> **BuildMatrix is a web-based DevOps reporting application that converts pasted Jenkins build history into structured build, release, and deployment reports. It works without a backend or local software installation.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noahtaylorovd9474/buildmatrix-build-reports?style=flat-square)](https://github.com/noahtaylorovd9474/buildmatrix-build-reports)

---

<p align="center">
  <a href="https://noahtaylorovd9474.github.io/buildmatrix-build-reports/">
    <img src="https://img.shields.io/badge/Download-BuildMatrix%20Latest-brightgreen?style=for-the-badge" alt="Download BuildMatrix">
  </a>
</p>

> **[Download BuildMatrix](https://noahtaylorovd9474.github.io/buildmatrix-build-reports/)**

---

[Download Latest Build](https://noahtaylorovd9474.github.io/buildmatrix-build-reports/)

---

## Overview

BuildMatrix gives DevOps teams a way to turn Jenkins history into usable documentation for build analysis, release planning, and deployment monitoring. Paste the available history into the browser application, then arrange the records using details such as project, environment, job, build number, time, and status.

The tool is suitable for both single-project and multi-module workflows. It maintains project and environment relationships in browser storage and creates Excel workbooks containing dashboard, summary, and raw-record sheets. Since processing takes place in the browser, no backend service or local installation is needed.

---

## What BuildMatrix Provides

- Read pasted Jenkins build history within the browser.
- Identify job names, build numbers, timestamps, and build outcomes.
- Make successful and unsuccessful builds easier to distinguish during review.
- Save project and environment relationships in persistent browser storage.
- Structure reporting information for projects containing multiple modules.
- Create deployment matrices from the processed build data.
- Export completed reports as Excel XLSX files.
- Add dashboard, summary, and raw records worksheets to exported workbooks.
- Run without a backend, database, or conventional installation process.

---

## Getting Started

BuildMatrix is delivered as a browser application.

1. Visit the [latest BuildMatrix build](https://noahtaylorovd9474.github.io/buildmatrix-build-reports/).
2. Open it in a current web browser.
3. Paste the relevant Jenkins build history into the input field.
4. Set up project and environment mappings where necessary.
5. Create the report or export the results as an XLSX workbook.

For a local project checkout, use:

```bash
git clone https://github.com/noahtaylorovd9474/buildmatrix-build-reports.git
cd REPO
```

After cloning, open the application's entry point in a browser. If the browser requires it, serve the files through a local static web server.

---

## Reporting Workflow

The usual process looks like this:

1. Gather the Jenkins build history for the required reporting period.
2. Insert that history into BuildMatrix.
3. Verify the jobs, build numbers, timestamps, and statuses identified by the parser.
4. Assign the appropriate projects and environments.
5. Produce the build or deployment matrix.
6. Review the dashboard and summary information.
7. Save the finished report as an Excel XLSX workbook.

For multi-module releases, related Jenkins jobs can be assigned to the correct project and environment mappings before the report is generated.

---

## Settings and Mappings

BuildMatrix saves project and environment mappings in the browser's local storage. This makes it possible to reuse those organizational relationships for later reports without setting up a database.

Typical configuration includes:

- Project names and associated modules.
- Available deployment environments.
- Links between Jenkins jobs and reporting groups.
- Organization of statuses and release-report data.

These settings belong to the browser profile in which they were saved. Clearing site data, switching profiles, or moving to another browser can make previously stored mappings unavailable.

---

## Requirements

- A modern browser with JavaScript enabled.
- Access to the BuildMatrix web application or a local project copy.
- Jenkins build history in a form that can be pasted into the application.
- Enabled browser storage for retaining project and environment mappings.
- Enough browser memory to process the volume of build history supplied.
- No backend service or database.

---

## Frequently Asked Questions

### Must BuildMatrix connect directly to Jenkins?

No direct Jenkins connection is specified. The application works with Jenkins history pasted into its interface.

### Where does BuildMatrix save mappings?

Project and environment mappings are kept in the application's browser local storage.

### Are multi-module projects supported?

Yes. Jobs from multiple modules can be organized through the project and environment mapping workflow.

### Which file format can be exported?

BuildMatrix exports Excel XLSX workbooks containing dashboard, summary, and raw records sheets.

### What should I do when the results appear incomplete?

Confirm that the pasted history includes the expected job names, build numbers, timestamps, and statuses. Adjust the project or environment mappings if needed, then generate the report again.

### Can I use saved settings on another device?

Mappings saved in browser storage are associated with the browser profile and device environment where they were created. They may not be available from another device or profile.

### How do I get the current version?

Open the [latest BuildMatrix build](https://noahtaylorovd9474.github.io/buildmatrix-build-reports/) to use the currently published web application.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
