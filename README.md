# XBMC

![license](https://img.shields.io/badge/license-GPL-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-consumer_electronics-lightgrey)

> Anticloud-hardened packaging of the upstream project `XBMC` in category **CONSUMER ELECTRONICS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CONSUMER ELECTRONICS · **Upstream:** https://github.com/XBMC/xbmc · **Upstream pin:** `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

![Kodi Logo](docs/resources/banner.png)

<p align="center">
  <strong>
    <a href="https://kodi.tv/">website</a>
    •
    <a href="https://kodi.wiki/view/Main_Page">docs</a>
    •
    <a href="https://forum.kodi.tv/">community</a>
    •
    <a href="https://kodi.tv/addons">add-ons</a>
  </strong>
</p>

<p align="center">
  <a href="LICENSE.md"><img alt="License" src="https://img.shields.io/badge/license-GPLv2-blue.svg?style=flat-square"></a>
  <a href="https://docs.kodi.tv/"><img alt="Documentation" src="https://img.shields.io/badge/code-documented-brightgreen.svg?style=flat-square"></a>
  <a href="https://github.com/xbmc/xbmc/pulls"><img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"></a>
  <a href="#how-to-contribute"><img alt="Contributions Welcome" src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square"></a>
  <a href="http://jenkins.kodi.tv/"><img alt="Build" src="https://img.shields.io/badge/CI-jenkins-brightgreen.svg?style=flat-square"></a>
  <a href="https://github.com/xbmc/xbmc/commits/master"><img alt="Commits" src="https://img.shields.io/github/commits-since/xbmc/xbmc/latest.svg?style=flat-square"></a>
</p>

<a href="https://play.google.com/store/apps/details?id=org.xbmc.kodi" target="_blank">
  <img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="80"/>
</a>

<h1 align="center">
  Welcome to Kodi Home Theater Software!
</h1>

Kodi is an award-winning **free and open source** software media player and entertainment hub for digital media. Available as a native application for **Android, Linux, BSD, macOS, iOS, tvOS and Windows operating systems**, Kodi runs on most common processor architectures.

Created in 2003 by a group of like minded programmers, Kodi is a non-profit project run by the XBMC Foundation and developed by volunteers located around the world. More than 500 software developers have contributed to Kodi to date, and 100-plus translators have worked to expand its reach, making it available in more than 70 languages.

While Kodi functions very well as a standard media player application for your computer, it has been designed to be the perfect companion for your HTPC. With its **beautiful interface and powerful skinning engine**, Kodi feels very natural to use from the couch with a remote control and is the ideal solution for your home theater.

## Give your media the love it deserves
Kodi can be used to play almost all popular audio and video formats around. It was designed for network playback, so you can stream your multimedia from anywhere in the house or directly from the internet using practically any protocol available.

Point Kodi to your media and watch it **scan and automagically create a personalized library** complete with box covers, descriptions, and fanart. There are playlist and slideshow functions, a weather forecast feature and many audio visualizations. Once installed, your computer or HTPC will become a fully functional multimedia jukebox.

<p align="center">
  <img src="docs/resources/kodi.gif" alt="Kodi">
</p>

## Getting Started
Kodi's developers work hard to make it support a large range of devices and operating systems. We provide final as well as development builds. To get started, head over to the **[downloads section](https://kodi.tv/download)** and simply select the platform that you want to install it on. A **[quick start guide](https://kodi.wiki/view/quick_start_guide)** to help you get acquainted with Kodi is available in our wiki.

## How to Contribute
Kodi is created by users for users and **we welcome every contribution**. There are no highly paid developers or poorly paid support personnel on the phones ready to take your call. There are only users who have seen a problem and done their best to fix it. This means Kodi will always need the contributions of users like you. How can you get involved?

* **Coding:** Developers can help Kodi by **[fixing a bug](https://github.com/xbmc/xbmc/issues)**, adding new features, making our technology smaller and faster and making development easier for others. Kodi's codebase consists mainly of C++ with small parts written in a variety of coding languages. Our add-ons mainly consist of python and XML. For more information, please have a look at our **[contributing guide](docs/CONTRIBUTING.md)**.
* **Helping users:** Our support process relies on enthusiastic contributors like you to help others get the most out of Kodi. The #1 priority is always answering questions in our **[support forums](https://forum.kodi.tv/)**. Everyday new people discover Kodi, and everyday they are virtually guaranteed to have questions.
* **Localization:** Translate **[Kodi](https://kodi.weblate.cloud/projects/kodi-core/kodi-main/)**, **[add-ons, skins etc.](https://kodi.weblate.cloud/)** into your native language.
* **Add-ons:** **[Add-ons](https://kodi.tv/addons)** are what make Kodi the most extensible and customizable entertainment hub available. **[Get started building an add-on](https://kodi.tv/create-an-addon)**.
* **Documentation:** Kodi's **[wiki pages](https://kodi.wiki/)** are the hub for information about Kodi and surrounding ecosystem. Help make our documentation better by writing new content or correcting existing material.

**Not enough free time?** No problem! There are other ways to help Kodi.

* **Spread the word:** Share Kodi with the world! Tell your friends and family about how Kodi creates an amazing entertainment experience. Stay up to date on the latest stories about Kodi reading our **[news](https://kodi.tv/blog)** section, follow us on **[Twitter](https://twitter.com/koditv)** and **[Facebook](https://www.facebook.com/XBMC/)**, or **star Kodi's project** if you want to follow development.
* **Donate:** We are always happy to receive a **[donation](https://kodi.tv/contribute/donate)**. Donations are typically used for travel to attend conferences, any necessary paperwork

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **C/C++ / CMake** (manifests: CMakeLists.txt; scanned in UPSTREAM_CLONE)
- Top-level source layout: `LICENSES/`, `addons/`, `cmake/`, `lib/`, `media/`, `project/`, `system/`, `tools/`, `userdata/`, `xbmc/`
- Snapshot size: **9764 files**, **1116594 lines of code** (measured; see Benchmarks)
- Primary languages: `.h` (2513), `.cpp` (2233), `.po` (1213), `.json` (862), `.png` (809), `.txt` (452)
- Upstream commit pinned for this packaging: `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04`

---

## Installation

<a href="https://github.com/xbmc/xbmc/commits/master"><img alt="Commits" src="https://img.shields.io/github/commits-since/xbmc/xbmc/latest.svg?style=flat-square"></a>
</p>

<a href="https://play.google.com/store/apps/details?id=org.xbmc.kodi" target="_blank">
  <img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="80"/>
</a>

<h1 align="center">
  Welcome to Kodi Home Theater Software!
</h1>

Kodi is an award-winning **free and open source** software media player and entertainment hub for digital media. Available as a native application for **Android, Linux, BSD, macOS, iOS, tvOS and Windows operating systems**, Kodi runs on most common processor architectures.

Created in 2003 by a group of like minded programmers, Kodi is a non-profit project run by the XBMC Foundation and developed by volunteers located around the world. More than 500 software developers have contributed to Kodi to date, and 100-plus translators have worked to expand its reach, making it available in more than 70 languages.

While Kodi functions very well as a standard media player application for your computer, it has been designed to be the perfect companion for your HTPC. With its **beautiful interface and powerful skinning engine**, Kodi feels very natural to use from the couch with a remote control and is the ideal solution for your home theater.

## Give your media the love it deserves
Kodi can be used to play almost all popular audio and video formats around. It was designed for network playback, so you can stream your multimedia from anywhere in the house or directly from the internet using practically any protocol available.

Point Kodi to your media and watch it **scan and automagically create a personalized library** complete with box covers, descriptions, and fanart. There are playlist and slideshow functions, a weather forecast feature and many audio visualizations. Once installed, your computer or HTPC will become a fully functional multimedia jukebox.

<p align="center">
  <img src="docs/resources/kodi.gif" alt="Kodi">
</p>

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

## Give your media the love it deserves
Kodi can be used to play almost all popular audio and video formats around. It was designed for network playback, so you can stream your multimedia from anywhere in the house or directly from the internet using practically any protocol available.

Point Kodi to your media and watch it **scan and automagically create a personalized library** complete with box covers, descriptions, and fanart. There are playlist and slideshow functions, a weather forecast feature and many audio visualizations. Once installed, your computer or HTPC will become a fully functional multimedia jukebox.

<p align="center">
  <img src="docs/resources/kodi.gif" alt="Kodi">
</p>

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

<a href="https://github.com/xbmc/xbmc/pulls"><img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"></a>
  <a href="#how-to-contribute"><img alt="Contributions Welcome" src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square"></a>
  <a href="http://jenkins.kodi.tv/"><img alt="Build" src="https://img.shields.io/badge/CI-jenkins-brightgreen.svg?style=flat-square"></a>
  <a href="https://github.com/xbmc/xbmc/commits/master"><img alt="Commits" src="https://img.shields.io/github/commits-since/xbmc/xbmc/latest.svg?style=flat-square"></a>
</p>

<a href="https://play.google.com/store/apps/details?id=org.xbmc.kodi" target="_blank">
  <img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height="80"/>
</a>

<h1 align="center">
  Welcome to Kodi Home Theater Software!
</h1>

Kodi is an award-winning **free and open source** software media player and entertainment hub for digital media. Available as a native application for **Android, Linux, BSD, macOS, iOS, tvOS and Windows operating systems**, Kodi runs on most common processor architectures.

Created in 2003 by a group of like minded programmers, Kodi is a non-profit project run by the XBMC Foundation and developed by volunteers located around the world. More than 500 software developers have contributed to Kodi to date, and 100-plus translators have worked to expand its reach, making it available in more than 70 languages.

While Kodi functions very well as a standard media player application for your computer, it has been designed to be the perfect companion for your HTPC. With its **beautiful interface and powerful skinning engine**, Kodi feels very natural to use from the couch with a remote control and is the ideal solution for your home theater.

## Give your media the love it deserves
Kodi can be used to play almost all popular audio and video formats around. It was designed for network playback, so you can stream your multimedia from anywhere in the house or directly from the internet using practically any protocol available.

Point Kodi to your media and watch it **scan and automagically create a personalized library** complete with box covers, descriptions, and fanart. There are playlist and slideshow functions, a weather forecast feature and many audio visualizations. Once installed, your computer or HTPC will become a fully functional multimedia jukebox.

<p align="center">
  <img src="docs/resources/kodi.gif" alt="Kodi">
</p>

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | C/C++ / CMake |
| Manifests detected | CMakeLists.txt |
| Files in snapshot | 9764 |
| Lines of code | 1116594 |
| Dependency references | 15 |
| Dependencies by ecosystem | native: 15 |
| Upstream license | GPL |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| native | PkgConfig | - | CMakeLists.txt |
| native | Threads | - | CMakeLists.txt |
| native | Shairplay | - | CMakeLists.txt |
| native | Gtest | - | CMakeLists.txt |
| native | Doxygen | - | CMakeLists.txt |
| native | SWIG | - | xbmc/interfaces/swig/CMakeLists.txt |
| native | Bluetooth | - | tools/EventClients/Clients/WiiRemote/CMakeLists.txt |
| native | CWiid | - | tools/EventClients/Clients/WiiRemote/CMakeLists.txt |
| native | GLU | - | tools/EventClients/Clients/WiiRemote/CMakeLists.txt |
| native | Lzo2 | - | tools/depends/native/TexturePacker/src/CMakeLists.txt |
| native | PNG | - | tools/depends/native/TexturePacker/src/CMakeLists.txt |
| native | GIF | - | tools/depends/native/TexturePacker/src/CMakeLists.txt |
| native | JPEG | - | tools/depends/native/TexturePacker/src/CMakeLists.txt |
| native | Meson | - | tools/depends/native/pkgconf/CMakeLists.txt |
| native | Ninja | - | tools/depends/native/pkgconf/CMakeLists.txt |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `CMakeLists.txt`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `XBMC` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: GPL** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
Kodi is provided under

    SPDX-License-Identifier: GPL-2.0-or-later

Being under the terms of the GNU General Public License v2.0 or later, according with

    LICENSES/GPL-2.0-or-later

In addition, other licenses may also apply. Please see

    LICENSES/README.md

for more details.

```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original GPL terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `GPL` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `XBMC` (category: CONSUMER ELECTRONICS)
- **Upstream URL:** https://github.com/XBMC/xbmc
- **Pinned commit (SHA):** `e99bb6a9192c26a8575fb2d16a7247bf49f8fb04`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`f25a4abd036c8333fed75115cb627a8d59596f1baefe74582e11c8b58658e424`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

