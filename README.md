# MOS Docker shim

mos-docker-shim provides a **MOS plugin** that allows container which are
using a br0 or eth0 (macvlan/ipvlan) network reach the Host (MOS).

---

## Overview

This plugin allows containers in LAN networks (br0/eth0, macvlan/ipvlan)
to reach the host.

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
