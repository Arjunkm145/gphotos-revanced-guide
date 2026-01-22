# GPhotos ReVanced – Release Repository

This repository provides official release documentation and build instructions
for patching Google Photos using ReVanced CLI.

No APK files are distributed here.
Users must build the app locally from original APKs.

---

## What is this project?

This project is a release-style repository that documents the process of
building Google Photos ReVanced using the ReVanced command-line interface.

It is useful when:
- ReVanced Manager fails
- You want to patch the latest version
- You prefer PC-based workflow

---

## Requirements

You need:

- A PC (Windows / Linux / macOS)
- Java 11 or newer
- ReVanced CLI
- ReVanced patches file
- Original Google Photos APK

---

## Official Downloads

Java:
https://www.azul.com/downloads/

ReVanced CLI:
https://github.com/ReVanced/revanced-cli/releases

ReVanced patches:
https://github.com/ReVanced/revanced-patches/releases

Original APK sources:
https://www.apkmirror.com  
https://apkpure.com

---

## How to Build

1. Install Java
2. Download ReVanced CLI (`revanced-cli.jar`)
3. Download patches file (`patches.rvp`)
4. Download original APK and rename to `input.apk`
5. Put all files in one folder
6. Open terminal in that folder
7. Run:

```bash
java -jar revanced-cli.jar patch -p patches.rvp -o Output.apk input.apk


