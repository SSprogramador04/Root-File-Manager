# 📂 Root File Manager

A modern, iOS-inspired Root File Manager built with **Jetpack Compose** and **Material 3**. Designed for performance and clean aesthetics in 2026.

## ✨ Features
* **iOS Aesthetics:** Large, collapsing titles and smooth "Action Sheet" menus.
* **Root Power:** Full access to system partitions using `su` commands.
* **Dynamic Theme:** Automatically switches between Light and Dark mode based on system settings.
* **Smart Navigation:** Intercepts physical back button gestures for folder-by-folder navigation.
* **Boot Customization:** Dedicated logic to apply custom `bootanimation.zip` files to the `/product/media` partition.

## 🚀 Installation
1. Download the `app-release.apk` from the releases section.
2. Enable **USB Debugging (Security Settings)** if using a Xiaomi device.
3. Grant **All Files Access** in the Android Special App Access settings.
4. Grant **Superuser** (Root) permissions via Magisk or KernelSU.

## ⚠️ Device Compatibility Note
> [!IMPORTANT]
> **Redmi 10 Prime Users:** This app may experience stability issues on the Redmi 10 Prime (Helio G88). Due to Xiaomi's **Super Partition** (Dynamic Partitions) and aggressive MIUI/HyperOS memory management, "Read-Write" (RW) remounting of the `/product` partition may fail.

[Tested phisically on Xiaomi REDMI 10 prime and SAMSUNG Galaxy A015M/DS]

## 🛠️ Tech Stack
* **Language:** Kotlin
* **UI Framework:** Jetpack Compose (Material 3)
* **Architecture:** MVVM (ViewModel + StateFlow)
* **Shell:** RootShell integration for `su` execution.

## 📜 License
This project is for educational "rookie-to-pro" development purposes. Use at your own risk when modifying system files.
