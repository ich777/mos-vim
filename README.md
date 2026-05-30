# MOS Vim Plugin

Terminal-based text editor plugin for MOS.
mos-vim provides a **MOS plugin** that integrates the `vim`
utility into the MOS ecosystem.

---

## Overview

This repository contains the **MOS plugin implementation**, packaged
`vim` binary required to use Vim within MOS.

The plugin allows MOS to use Vim in the CLI.

### Binary Source

- vim: [https://github.com/vim/vim](https://github.com/vim/vim)

---

## Build & Automation

This repository includes a **GitHub Actions workflow** used to build and package
the plugin and its associated binaries for MOS.

The build process is fully automated and produces artifacts that can be
installed through the MOS Hub.

---

## Licensing

The contents of this repository (plugin code, build scripts, configuration,
and automation) are licensed under **GPL-3.0**.

`vim` itself is licensed under its respective upstream license.

---

## Third-Party Software

This repository builds and packages third-party open-source software.
Packaged components remain licensed under their original upstream licenses.

Refer to `THIRD_PARTY.md` for details.