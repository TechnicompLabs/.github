<p align="center"><img src="logo.png" alt="Technicomp Labs" width="420"></p>

# Technicomp Labs

The home of **Technicomp Benchtop Linux**, and of future open-source projects from [Technicomp Labs](https://technicomplabs.io).

## Technicomp Benchtop Linux

*The operating system for the technical workbench.*

**Updates that don't break your bench.** Benchtop Linux is a GNOME desktop for desktop and laptop workstations. Its core follows long-term-support releases and the desktop runs GNOME Oldstable, so the system stays stable while security fixes still arrive quickly. Every update is a snapshot you can roll back. The motto is "Let other people be your beta testers."

The desktop stays responsive under heavy load, and it's ready out of the box for every thread of your work: AI, virtualization, software development, system administration, security, reverse engineering, and content creation. Apps come from Flatpak and command-line tools from Homebrew. It runs on workstation-class x86 hardware and is also optimized for Microsoft Surface devices, Apple MacBooks, Lenovo ThinkPads, and ASUS and Razer laptops, along with common peripherals. ARM support is coming.

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
