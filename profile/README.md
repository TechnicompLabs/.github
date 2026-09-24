<p align="center"><img src="logo.png" alt="Technicomp Labs" width="420"></p>

# Technicomp Labs

The home of **Technicomp Benchtop Linux**, and of future open-source projects from [Technicomp Labs](https://technicomplabs.io).

## Technicomp Benchtop Linux

*The operating system for the technical workbench.*

**Updates that don't break your bench.** Benchtop Linux is a GNOME desktop operating system for desktop and laptop workstations. Its core packages follow long-term-support releases and its desktop is GNOME Oldstable, which keeps the system stable while security fixes continue to arrive promptly. Each update is installed as a snapshot that can be rolled back. The project's motto is "Let other people be your beta testers."

The desktop remains responsive under heavy load, and the system is configured for technical work ranging from AI and virtualization to reverse engineering and content creation. Applications are installed through Flatpak and command-line tools through Homebrew, both managed per user rather than system-wide. Benchtop Linux runs on workstation-class x86 and ARM hardware and ships two kernels, LTS and Current, both with patches that extend support for laptops, tablets, convertibles, and common peripherals.

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
