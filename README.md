<p align="center">
  <img src="assets/vanta-logo.png" alt="Vanta OS logo" width="128">
</p>

<h1 align="center">Vanta OS</h1>

<p align="center">
  A Debian-based desktop for everyday use, built around Xfce and a small set of essentials.
</p>

<p align="center">
  <strong>Debian 13 “trixie”</strong> · <strong>Xfce</strong> · <strong>In development</strong>
</p>

## Overview

Vanta OS is designed for browsing, managing files, playing media and writing code. The aim is a desktop that feels responsive on older hardware and gives you control over what runs in the background.

The default setup keeps common tasks within reach. Network and volume controls live in the panel, everyday programs are easy to find, and additional software is available through APT. A charcoal theme with violet accents, readable text and visible keyboard focus gives the desktop its own identity.

## Planned desktop

| Task | Default |
| --- | --- |
| Browse the web | Firefox ESR |
| Manage files | Thunar |
| Edit text | Mousepad |
| Use the command line | Xfce Terminal |
| Connect to a network | NetworkManager with panel controls |
| Manage audio | PipeWire with panel volume control |

The base system uses Debian’s official repositories for packages and security updates. Office suites, games and development tools are optional installs.

## Development roadmap

| Stage | Milestone | Status |
| --- | --- | --- |
| 01 | Build a live ISO and verify that it boots to a usable Xfce desktop | In progress |
| 02 | Integrate the Vanta theme, panel layout and default software | Planned |
| 03 | Add an installer and verify that the installed system boots and updates | Planned |
| 04 | Measure boot time, memory use and desktop responsiveness against Windows 10 | Planned |

The first public milestone is a **bootable live ISO**. Once testing reaches physical hardware, performance results will include the test conditions, measurement method and raw numbers.

---

Vanta OS is an independent project based on Debian.
