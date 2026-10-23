# UsurperProject

**Rethinking how operating systems are installed, booted, and managed.**

UsurperProject is an open-source initiative focused on simplifying operating system deployment, booting, and experimentation.

We believe that installing or booting another operating system shouldn't require dedicated removable media, unnecessarily complicated workflows, or starting from scratch every time.

Our projects aim to remove these barriers by building tools that work with your existing environment, leverage established technologies, and give users greater control over how they interact with their systems.

## Projects

### [YoRBo](https://github.com/UsurperProject/YoRBo)

**You only ReBoot once.**

Boot ISO, IMG, and VHDX images directly from your existing system, without preparing a bootable USB drive.

YoRBo builds heavily on [Ventoy](https://github.com/ventoy/Ventoy), inheriting much of its existing image compatibility while working to bridge the differences introduced by booting from internal storage.

### [Usurper](https://github.com/UsurperProject/Usurper)

**Install Linux without leaving Windows.**

A Windows-hosted Linux installer aiming to eliminate the need for bootable installation media or a separate live environment.

Usurper explores a more flexible approach to Linux installation, including support for different distributions, customizable installations, and reusable deployment infrastructure.

### [TinyWeasel](https://github.com/UsurperProject/TinyWeasel)

Lightweight virtualization infrastructure built around QEMU and minimal Linux environments.

TinyWeasel provides reusable components for performing Linux-oriented operations from other host environments without requiring a full virtual machine setup.

## Our Approach

- **Remove unnecessary dependencies** — external installation media shouldn't be a prerequisite for installing or booting an operating system.
- **Build on existing foundations** — reuse proven technologies instead of reinventing entire systems without good reason.
- **Keep things modular** — develop reusable components that can serve multiple projects independently.
- **Prioritize user control** — simplify complex operations without unnecessarily restricting what users can do.
- **Stay open** — develop in the open and make the tools available for others to inspect, modify, and improve.

## Development

UsurperProject is an evolving collection of experimental and actively developed tools. Not every project is production-ready, and supported configurations may change as development progresses.

Contributions, bug reports, technical discussions, and experimentation are welcome.

---

*Less preparation. More possibilities.*
