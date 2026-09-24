<p align="center"><img src="logo.png" alt="Technicomp Labs" width="420"></p>

# Technicomp Labs

The home of **Technicomp Benchtop Linux**, and of future open-source projects from [Technicomp Labs](https://technicomplabs.io).

## Technicomp Benchtop Linux

*The operating system for the technical workbench.*

Updates that don't break your bench. Benchtop Linux is an immutable, transactional GNOME desktop for desktop and laptop workstations, with rolling updates on an LTS foundation. Core packages track LTS releases and GNOME runs one release behind current, so the base stays stable while security patches arrive promptly. The motto is "Let other people be your beta testers." Benchtop Linux prioritizes low interactive latency and workstation stability, so the desktop stays responsive even when the machine is busy. Benchtop Linux is optimized for widely used hardware, including Microsoft Surface devices, Apple MacBooks, Lenovo ThinkPads, ASUS and Razer laptops, and common peripherals. ARM will be a supported architecture in the future.

Graphical applications come from Flatpak and command-line tooling from Homebrew. This is a batteries-included distro, with out-of-the-box support for the threads of technical work: AI, virtualization, software development, system administration, security, reverse engineering, and content creation.

Technicomp Benchtop Linux is in alpha. Installable disk images are released through the Build Service.

| Repository | Contents |
|---|---|
| [benchtop-image](https://github.com/TechnicompLabs/benchtop-image) | The OS disk image (kiwi configuration, built on OBS via scmsync) |
| [benchtop-settings](https://github.com/TechnicompLabs/benchtop-settings) | `tc-benchtop-settings`: tuned system defaults, layered as drop-ins over openSUSE's vendor defaults |
| [benchtop-patterns](https://github.com/TechnicompLabs/benchtop-patterns) | `patterns-tc-benchtop`: the package patterns that define the image |
| [benchtop-linux](https://github.com/TechnicompLabs/benchtop-linux) | Build coordination, package integration notes, and release tracking |
| [packages](https://github.com/TechnicompLabs/packages) | Additional RPM packages not carried by openSUSE |
| [benchtop-notes](https://github.com/pauldmartinphd/benchtop-notes) | Design notes: decisions, open questions, and references |

Packages and images build at [home:technicomp](https://build.opensuse.org/project/show/home:technicomp) on the openSUSE Build Service.

## Elsewhere

- [technicomplabs.io](https://technicomplabs.io): the lab, the collection, and the writing
- [LLM Performance Engineering Notebook](https://github.com/pauldmartinphd/llm-performance-engineering-notebook): open lab notebook on inference performance of large Mixture-of-Experts models

Maintained by [Paul D. Martin, Ph.D.](https://pauldmartin.phd)
