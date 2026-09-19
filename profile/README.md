# Technicomp Labs

The home of **Technicomp Benchtop Linux**, and of future open-source projects from [Technicomp Labs](https://technicomplabs.io).

## Technicomp Benchtop Linux

An immutable, transactional GNOME desktop for benchtop and laptop hardware, built as an openSUSE Slowroll derivative. It keeps Aeon's foundation (read-only btrfs snapshots, UEFI with systemd-boot, Ignition first-boot configuration) and departs from it in two deliberate ways: a verbatim upstream kernel.org LTS kernel, and GNOME held one release behind current, both delivered through the openSUSE Build Service. Graphical applications come from Flatpak and command-line tooling from Homebrew.

Benchtop Linux is in alpha. Installable disk images are released through the Build Service; the graphical installer and branding packages are the next packaging tasks.

| Repository | Contents |
|---|---|
| [benchtop-image](https://github.com/TechnicompLabs/benchtop-image) | The OS disk image (kiwi configuration, built on OBS via scmsync) |
| [benchtop-settings](https://github.com/TechnicompLabs/benchtop-settings) | `tc-benchtop-settings`: tuned system defaults, layered as drop-ins over openSUSE's vendor defaults |
| [benchtop-patterns](https://github.com/TechnicompLabs/benchtop-patterns) | `patterns-tc-benchtop`: the package patterns that define the image |
| [benchtop-notes](https://github.com/pauldmartinphd/benchtop-notes) | Design notes: decisions, open questions, and references |

Packages and images build at [home:technicomp](https://build.opensuse.org/project/show/home:technicomp) on the openSUSE Build Service. A project site at benchtoplinux.org is in preparation.

## Elsewhere

- [technicomplabs.io](https://technicomplabs.io): the lab, the collection, and the writing
- [LLM Performance Engineering Notebook](https://github.com/pauldmartinphd/llm-performance-engineering-notebook): open lab notebook on inference performance of large Mixture-of-Experts models

Maintained by [Paul D. Martin, Ph.D.](https://pauldmartin.phd)
