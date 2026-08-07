# Fathom-OS

*A deeper Linux. Built for clarity.*

Fathom-OS is a custom Linux distribution built from source using the Linux From Scratch (LFS) methodology. No Debian base, no Ubuntu package set, no inherited configuration. Every binary in the final system is compiled by hand from verified source.

Built for developers, sysadmins, and anyone who wants a system they fully understand.

## Project Philosophy

- Terminal-first. A GUI may come later, but the command-line experience is the priority.
- Modular by default. Every component is isolated and replaceable.
- Clarity over clutter. Nothing ships unless it is clean, documented, and justified.
- Solo-driven by Dennis Ayotte. Every build decision, command, and configuration is done by hand. AI is used as a reference tool only.

## Status

Pre-alpha. Active development in progress. The source repository is private at this time, and the project is not yet accepting contributors or publishing builds.

Build methodology: [Linux From Scratch 13.0-systemd](https://www.linuxfromscratch.org/lfs/view/13.0-systemd/)

### Build Progress

- [x] Build host provisioned (fathomos-dev, Proxmox)
- [x] Host system requirements verified (Ch. 2.2)
- [x] Partition and filesystem setup (Ch. 2.4 and 2.5)
- [x] Set the $LFS variable and umask (Ch. 2.6 and 2.7)
- [x] Packages and patches downloaded (Ch. 3)
- [x] Final host preparations (Ch. 4)
- [x] Cross-compilation toolchain (Ch. 5)
- [x] Cross compiling temporary tools (Ch. 6)
- [x] Entering chroot and additional tools (Ch. 7)
- [ ] Core system build (Ch. 8, Part 3 complete)
- [ ] System configuration and kernel (Ch. 9 and 10)
- [ ] Post-LFS: package manager, branding, v0.1 release

## Build Host

Ubuntu Server 24.04 LTS VM on Proxmox (fathomos-dev)
10 vCPUs, 32 GB RAM, 245 GB /lfs partition

## Links

- Website: [fathom-os.com](https://fathom-os.com)
- Project log: [Fathom-OS Project Log](https://thecaptaindumbass.com/posts/fathom-os-project-log-vision-status-milestones/)
- Category: [thecaptaindumbass.com/categories/fathom-os](https://thecaptaindumbass.com/categories/fathom-os/)

## References

- [Linux From Scratch](https://www.linuxfromscratch.org/lfs/)

## License

Copyright (C) 2026 Dennis Ayotte.

The original work in this repository (scripts, configuration, and documentation) is licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE). Upstream LFS packages retain their own respective licenses.
