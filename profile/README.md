<p align="center"><img src="logo.png" alt="Technicomp Labs" width="420"></p>

# Technicomp Labs

The home of **Technicomp Benchtop Linux**, and of future open-source projects from [Technicomp Labs](https://technicomplabs.io).

## Technicomp Benchtop Linux

*The operating system for the technical workbench.*

The LTS distro that rolls: an immutable, transactional GNOME desktop for desktop and laptop workstations. Core packages track LTS releases and GNOME runs one release behind current, so the base stays stable while security patches arrive promptly. The motto is "Let other people be your beta testers." The system is tuned for very low interactive latency: kernel preemption, scheduling, memory reclamation, and I/O are configured so the desktop stays responsive under heavy load. The kernel is patched to support widely used hardware, including Microsoft Surface and Apple MacBooks, and userspace support is included for common peripherals. ARM will be a supported architecture in the future.

Graphical applications come from Flatpak and command-line tooling from Homebrew. This is a batteries-included distro, with out-of-the-box support for AI, virtualization, software development, system administration, and security workflows. Audio and content-creation workloads are supported as well, with realtime scheduling and memory limits set for low-latency audio.

Technicomp Benchtop Linux is in alpha. Installable disk images are released through the Build Service; the graphical installer and branding packages are the next packaging tasks.

| Repository | Contents |
|---|---|
| [benchtop-image](https://github.com/TechnicompLabs/benchtop-image) | The OS disk image (kiwi configuration, built on OBS via scmsync) |
| [benchtop-settings](https://github.com/TechnicompLabs/benchtop-settings) | `tc-benchtop-settings`: tuned system defaults, layered as drop-ins over openSUSE's vendor defaults |
| [benchtop-patterns](https://github.com/TechnicompLabs/benchtop-patterns) | `patterns-tc-benchtop`: the package patterns that define the image |
| [benchtop-linux](https://github.com/TechnicompLabs/benchtop-linux) | Build coordination, package integration notes, and release tracking |
| [packages](https://github.com/TechnicompLabs/packages) | Additional RPM packages not carried by openSUSE |
| [benchtop-notes](https://github.com/pauldmartinphd/benchtop-notes) | Design notes: decisions, open questions, and references |

Packages and images build at [home:technicomp](https://build.opensuse.org/project/show/home:technicomp) on the openSUSE Build Service. A project site at benchtoplinux.org is in preparation.

## Elsewhere

- [technicomplabs.io](https://technicomplabs.io): the lab, the collection, and the writing
- [LLM Performance Engineering Notebook](https://github.com/pauldmartinphd/llm-performance-engineering-notebook): open lab notebook on inference performance of large Mixture-of-Experts models

Maintained by [Paul D. Martin, Ph.D.](https://pauldmartin.phd)
