@ -0,0 +1,46 @@
<p align="center">
  <img src="assets/vanta-logo.png" alt="Vanta OS logo" width="160">
</p>

# Vanta OS

Vanta OS is a desktop operating system built on Debian 13 (trixie) with the Xfce desktop. I'm building it for everyday use: browsing, files, media and some coding. It should also run well on older PCs.

## Goals

1. Boot reliably, support common hardware and get updates from the official Debian repositories.
2. Keep background load low so the desktop stays responsive.
3. Ship a small set of apps with one program per task.
4. Give it a consistent look: dark grey with purple accents, readable fonts, visible focus states.

## Included apps

| Task | App |
|---|---|
| Web | Firefox ESR |
| Files | Thunar |
| Text | Mousepad |
| Terminal | Xfce Terminal |
| Network | NetworkManager, with Wi-Fi in the panel |
| Audio | PipeWire, with volume in the panel |

Office, games and developer tools are left out. You install what you need with APT.

## Roadmap

| Stage | Scope | Status |
|---|---|---|
| 1 | Live ISO that boots to the desktop | in progress |
| 2 | Vanta theme and default apps | planned |
| 3 | Installer | planned |
| 4 | Performance comparison with Windows 10 | planned |

There is no download yet. I'll publish speed comparisons once I have measured them on real hardware, with the method and raw numbers.

## Reference hardware

Intel Pentium G4560, NVIDIA GTX 1050 Ti, 8 GB RAM, SATA SSD.

---

Vanta OS uses Debian but is not affiliated with the Debian project.
