# MOS Docker shim

mos-docker-shim provides a **MOS plugin** that allows container which are
using a br0 or eth0 network to communicate with the Host (MOS).

---

## Overview

This plugin allows Docker containers which are using a br0 or eth0 network
to communicate with the Host.

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
