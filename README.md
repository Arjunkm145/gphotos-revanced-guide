# 📸 Google Photos ReVanced — CLI Release

![Release](https://img.shields.io/badge/release-latest-blue)
![Toolchain](https://img.shields.io/badge/toolchain-ReVanced%20CLI-orange)
![Java](https://img.shields.io/badge/java-11%2B-red)
![License](https://img.shields.io/badge/license-GPL--3.0-green)

Official **release repository** for building **Google Photos ReVanced**
using the **ReVanced CLI toolchain**.

This repository publishes release metadata, build references, and
reproducible commands for generating Google Photos ReVanced builds.

> ⚠️ **No APK files are distributed in this repository.**  
> All builds must be generated locally from original APKs.

---

## 🔍 Repository Purpose

This repository exists as a **release surface**, not as a build tool and not as a tutorial.

It serves as:

- A reference implementation for Google Photos ReVanced
- A release tracking repository
- A reproducible CLI-based build definition
- A fallback when ReVanced Manager does not support Google Photos

All patching is performed using **official ReVanced components only**.

---

## 📦 Scope

### This repository provides:
- Release metadata
- CLI build command reference
- Toolchain definitions
- Reproducible build workflow

### This repository does NOT provide:
- Prebuilt APKs
- Modded binaries
- Redistribution of proprietary software

---

## 🛠 Toolchain

The official toolchain used for all releases:

| Component | Purpose |
|----------|--------|
| Java 11+ | Runtime for CLI |
| ReVanced CLI | Core patching engine |
| ReVanced patches | Patch definitions |
| Original APK | Base input |

---

## 🔗 Official Upstream Sources

ReVanced CLI:  
https://github.com/ReVanced/revanced-cli/releases

ReVanced patches:  
https://github.com/ReVanced/revanced-patches/releases

Original APK providers:  
https://www.apkmirror.com  
https://apkpure.com

---

## 🔁 Reproducible Build Command

All releases are generated using the standard ReVanced CLI invocation:

```bash
java -jar revanced-cli.jar patch -p patches.rvp -o Output.apk input.apk

