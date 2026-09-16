# Marker Importer

Public support and feedback tracker for **Marker Importer**, a Premiere Pro UXP panel for moving recording markers into an edit timeline.

> This repository is for support, bug reports, feature requests, and public release information. The application source code is maintained privately and is not published in this repository.

## Current release

- Marker Importer **1.0.0**
- Adobe Premiere Pro **25.6 or newer**
- Windows and macOS

## What Marker Importer does

Marker Importer is built around recording-to-edit workflows, including OBS/XMEML markers. It can:

- import sequence markers from XMEML XML and Marker Importer CSV files
- place markers relative to a configurable **Recording starts at** timeline position
- preview new, duplicate, replacement, and excluded markers before changing the sequence
- preserve marker names, comments, durations, types, and colors when supported
- override marker color/type globally or per marker
- export Premiere sequence markers to a round-trip CSV format
- remove the most recent import conservatively without guessing at edited markers
- copy non-sensitive diagnostics for support

Marker Importer runs locally. It does not require an account and does not include analytics.

## Support and feedback

Use GitHub Issues for public support:

- **Found a bug?** [Report a bug](https://github.com/MFlys/marker-importer/issues/new?template=bug_report.yml)
- **Have an idea?** [Request a feature](https://github.com/MFlys/marker-importer/issues/new?template=feature_request.yml)
- **Browse existing reports:** [Issues](https://github.com/MFlys/marker-importer/issues)

Before opening a bug report, please check whether the issue already exists and include enough information to reproduce it.

For the most useful report, include:

- Marker Importer version
- Premiere Pro version
- Windows or macOS version
- source type used (`XML` or `CSV`)
- exact steps to reproduce
- what you expected and what actually happened
- a screenshot or short screen recording when useful
- **Copy Diagnostics** output from Marker Importer when available

Diagnostics are designed not to include local filesystem paths, but you should still review anything you paste into a public issue.

## Source code

Marker Importer is currently distributed as closed-source software. This public repository intentionally contains support material only; it is not a source mirror.

Please do not open pull requests expecting application source files to be present here. Product feedback and reproducible bug reports are welcome through Issues.
