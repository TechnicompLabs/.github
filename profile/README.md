<p align="center"><img src="logo.png" alt="Technicomp Labs" width="420"></p>

# Technicomp Labs

The home of **Technicomp Benchtop Linux**, and of future open-source projects from [Technicomp Labs](https://technicomplabs.io).

## Technicomp Benchtop Linux

*The operating system for the technical workbench.*

**Updates that don't break your bench.** Benchtop Linux is an immutable operating system for x86 and ARM workstations, with LTS core packages and a GNOME Oldstable desktop, so the system stays stable while security fixes arrive promptly. Every update is a snapshot that can be rolled back. Flatpak and Homebrew are managed per user. The motto is "Let other people be your beta testers."

Benchtop Linux is in alpha. Installable images are released through the Build Service.

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
