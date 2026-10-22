# html-services-section (file format)

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

This is the **serialization-services-section** `html-services-section`: the canonical serialization boundary for HTML, home to `services/html-file-codec-service` and its Semantic Hypertext Packet (SHP) codec, lint, and escaping surface. It reads and writes HTML files; it does not render documents from data.

A different `html-services-section` exists at `web-services-section/services/html-services-section` — the web-tier rendering seat, home to `html-document-render-service` (carrier + CSS in, HTML document string out). If you are producing styled HTML from data rather than decoding or encoding an HTML file, that is the section you want.
