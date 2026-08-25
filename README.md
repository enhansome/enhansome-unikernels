# Awesome Unikernels with stars

> Secure, lightweight and high performance approach to application delivery

## Contents

* [Introduction](#introduction)
* [Projects](#projects)
  * [Linux Binary Compatible](#linux-binary-compatible)
  * [Language oriented](#language-oriented)
  * [Generic](#generic)
  * [Unikernel-like](#unikernel-like)
* [Tools](#tools)

## Introduction

* [Unikernel and Immutable Infrastructures](https://github.com/cetic/unikernels) ⭐ 643 | 🐛 3 | 🌐 C++ | 📅 2022-02-16 - Introductory white paper maintained by CETIC engineers.

## Projects

### Linux Binary Compatible

* [Nanos](https://github.com/nanovms/nanos) ⭐ 3,184 | 🐛 81 | 🌐 C | 📅 2026-08-22 - Linux binary compatible unikernel focused on security.
* [HermiTux](https://github.com/ssrg-vt/hermitux) ⭐ 398 | 🐛 16 | 🌐 C | 📅 2024-08-13 - Research project from Virginia Tech, demonstrating advanced optimizations.
* [OSv](http://osv.io) - Modular unikernel able to execute unmodified Linux binaries, developed in C++.

### Language oriented

* [IncludeOS](https://github.com/includeos/IncludeOS) ⭐ 5,247 | 🐛 108 | 🌐 C++ | 📅 2026-05-15 - Feature rich unikernel development library for C++.
* [LING](https://github.com/cloudozer/ling) ⭐ 824 | 🐛 92 | 🌐 C | 📅 2022-04-17 - Erlang/Elixir unikernel development toolkit targeting Xen.
* [Ultibo Core](https://github.com/ultibohub/Core) ⭐ 185 | 🐛 2 | 🌐 Pascal | 📅 2026-08-04 - Lazarus/FreePascal unikernel targeting Raspberry Pi as the runtime environment.
* [rekernel](https://github.com/imbsky/rekernel) ⭐ 30 | 🐛 0 | 🌐 Makefile | 📅 2020-04-10 - Minimal setup for developing unikernels in ReasonML.
* [Union](https://github.com/pmuens/union) ⭐ 1 | 🐛 9 | 🌐 Assembly | 📅 2018-05-19 - POSIX compliant unikernel written in Rust.
* [binaryno](https://github.com/gmodena/binaryno) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2020-02-23 - Rust unikernel running on bare ARM CortexM hardware.
* [HaLVM](https://galois.com/project/halvm) - Port of Glasgow Haskell compiler producing Xen optimized unikernels.
* [MirageOS](https://mirage.io) - OCaml unikernel development library.
* [runtime.js](http://runtimejs.org) - KVM oriented unikernel for running JavaScript applications via the V8 engine.
* [Toro Kernel](https://torokernel.io) - Lazarus/FreePascal toolkit for unikernel development.

### Generic

* [BareMetal](https://github.com/ReturnInfinity/BareMetal) ⭐ 920 | 🐛 1 | 🌐 Assembly | 📅 2026-06-12 - Self described as an exokernel, it can be used as the starting point for unikernel development.
* [HermitCore](https://github.com/hermitcore/libhermit) ⚠️ Archived - A C-based, lightweight unikernel project from Aachen University.
* [EbbRT](https://github.com/SESA/EbbRT) ⭐ 76 | 🐛 8 | 🌐 C | 📅 2024-07-23 - Boston University unikernel research project.
* [Nautilus](https://github.com/HExSA-Lab/nautilus) ⭐ 50 | 🐛 8 | 🌐 C | 📅 2022-05-11 - Aerokernel from Sandia National Laboratories, supporting bare metal x86\_64 and Xeon Phi.
* [unicycle](https://github.com/libunicycle/unicycle) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2025-06-01 - Unikernel application framework developed in C.
* [JML](https://github.com/yesco/jml) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2024-05-23 - Proof of concept for a minimal web server unikernel implementing its own language.
* [ClickOS](http://cnp.neclab.eu/projects/clickos) - Efficient network function virtualization platform, optimized for Xen and developed by NEC.
* [Clive](http://lsub.org/ls/clive.html) - Research project from Rey Juan Carlos University (Madrid), developed in Go.
* [Mini-OS](https://wiki.xen.org/wiki/Mini-OS) - Reference kernel distributed with Xen.
* [Rump Kernels](http://rumpkernel.org) - Development platform reusing NetBSD components for producing efficient unikernels.
* [Firecracker](https://firecracker-microvm.github.io) - AWS's VM isolation engine, using in products such as Lambda and Fargate.
* [Unikraft](https://xenproject.org/developers/teams/unikraft) - Collection of building blocks for unikernel development.
* [UNICORE](http://unicore-project.eu) - Common code base and toolkit for deployment of applications to secure and reliable execution environments.

### Unikernel-like

* [Graphene](https://github.com/oscarlab/graphene) ⚠️ Archived - Library OS optimized for Intel SGX.
* [Drawbridge](https://www.microsoft.com/en-us/research/project/drawbridge) - Research prototype platform from Microsoft.

## Tools

* [UniK](https://github.com/solo-io/unik) ⭐ 2,821 | 🐛 51 | 🌐 Go | 📅 2023-04-27 - Unikernel compiler supporting a Firecracker, rump kernels, OSv, IncludeOS and MirageOS.
* [Solo5](https://github.com/Solo5/solo5) ⭐ 986 | 🐛 41 | 🌐 C | 📅 2026-08-18 - Middle-ware interfacing unikernels with the host systems.
* [Albatross](https://github.com/hannesm/albatross) ⭐ 166 | 🐛 17 | 🌐 OCaml | 📅 2026-08-15 - MigrageOS unikernel orchestration, via Solo5.
* [OPS](https://ops.city) - Orchestration tool for building and deploying Nanos based images.
* [Capstan](http://osv.io/capstan) - Orchestration tool for packaging and running OSv based images.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
