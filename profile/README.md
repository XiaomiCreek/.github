<div align="center">

## Welcome to the active source code hub for **Xiaomi POCO M7 4G / Redmi 15 4G (`creek`)**.



Note: This is an actively maintained Xiaomi Creek organization for POCO M7 4G / Redmi 15 4G custom ROM bringup, device tree.

<p align="center">
  <a href="https://t.me/LineageOS_creek"><img src="https://img.shields.io/badge/Telegram-Chat-01A9E0?style=flat-square&logo=telegram&logoColor=white"/></a>
  <a href="https://t.me/los_creek"><img src="https://img.shields.io/badge/Telegram-Channel-01A9E0?style=flat-square&logo=telegram&logoColor=white"/></a>
  <a href="https://github.com/XiaomiCreek/android_device_xiaomi_creek/commits/lineage-23.2"><img src="https://img.shields.io/github/last-commit/XiaomiCreek/android_device_xiaomi_creek/lineage-23.2?style=flat-square&color=00D4AA&label=Last+Commit"/></a>
  <img src="https://komarev.com/ghpvc/?username=XiaomiCreek&style=flat-square&color=6C63FF&label=README+Views"/>
</p>

![Creek Banner](https://github.com/XiaomiCreek/.github/raw/main/Xiaomi-Poco-M7-4G.png)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&size=22&pause=600&color=6C63FF&center=true&vCenter=true&width=600&lines=Now+focused+on+LineageOS+23.2;Stock+Android+features.+AOSP+foundation.;Your+device%2C+upgraded.;Built+for+those+who+demand+more.;Monthly+security+patches.+Always.;Open+source.+No+compromises.)](https://git.io/typing-svg)

</div>

---

> ### 🔵 Current Focus: LineageOS
> Development is centered on the **Android 16 (`lineage-23.2`)** branch — fixes and device bring-up land there first. We will try to keep this device actively maintained on a stability-focused updates.

---

## 📦 Core Repositories
* **Device Tree:** [`android_device_xiaomi_creek`](https://github.com/XiaomiCreek/android_device_xiaomi_creek)
* **Vendor Tree:** [`android_vendor_xiaomi_creek`](https://github.com/XiaomiCreek/android_vendor_xiaomi_creek)
* **Kernel Tree:** [`android_kernel_xiaomi_creek`](https://github.com/XiaomiCreek/android_kernel_xiaomi_creek)

---

## ✨ What Makes this device Special!?

<table align="center">
  <tr>
    <td width="240px"><b>SoC</b></td>
    <td width="650px">Qualcomm SM6225 Snapdragon 685 (6 nm)</td>
  </tr>
  <tr>
    <td><b>CPU</b></td>
    <td>4x2.8 GHz Cortex-A73 & 4x1.9 GHz Cortex-A53</td>
  </tr>
  <tr>
    <td><b>GPU</b></td>
    <td>Adreno 610</td>
  </tr>
  <tr>
    <td><b>Memory</b></td>
    <td>6GB/8GB RAM (LPDDR4X)</td>
  </tr>
  <tr>
    <td><b>Storage</b></td>
    <td>128GB/256GB UFS 2.2 (Expandable up to 2TB via SD)</td>
  </tr>
  <tr>
    <td><b>Shipped Android version</b></td>
    <td>15.0 with HyperOS 2</td>
  </tr>
  <tr>
    <td><b>Battery</b></td>
    <td>Non-removable Silicon-Carbon 7000 mAh</td>
  </tr>
  <tr>
    <td><b>Dimensions</b></td>
    <td>169.48 x 80.45 x 8.4 mm</td>
  </tr>
  <tr>
    <td><b>Display</b></td>
    <td>1080 x 2340 pixels, 19.5:9 ratio 6.9" inch</td>
  </tr>
  <tr>
    <td><b>Type</b></td>
    <td>IPS LCD, 144Hz, 850 nits (HBM)</td>
  </tr>
  <tr>
    <td><b>NFC</b></td>
    <td>Yes (Region dependent)</td>
  </tr>
  <tr>
    <td><b>Main Camera</b></td>
    <td>50 MP f/1.8 (Wide) + Auxiliary Lens</td>
  </tr>
  <tr>
    <td><b>Front camera</b></td>
    <td>8 MP, f/2.0 (wide)</td>
  </tr>
  <tr>
    <td><b>Protection</b></td>
    <td>IP64 + Wet Touch 2.0</td>
  </tr>
  <tr>
    <td><b>Weight</b></td>
    <td>214g</td>
  </tr>
  <tr>
    <td><b>Max Wired Input</b></td>
    <td>33W (Turbo Charging)</td>
  </tr>
  <tr>
    <td><b>Reverse Charging</b></td>
    <td>18W Wired (Power bank mode)</td>
  </tr>
  <tr>
    <td><b>0-100% Time</b></td>
    <td>~96 Minutes</td>
  </tr>
  <tr>
    <td><b>Battery Protection</b></td>
    <td>Battery Health 4.0 / Smart Charging Engine 2.0</td>
  </tr>
</table>

---

## 📱 Supported Custom Roms

<div align="center">

| Rom Name | Rom Version | Release Type | Status | Security Patch | Manifest | Downloads |
|----------|-------------|--------------|--------|----------------|----------|-----------|
| **LineageOS** | **23.2** | Unofficial | ![Bringup](https://img.shields.io/badge/Bringup-FF6C37?style=flat-square) | August 2026 | [16](https://github.com/XiaomiCreek/LineageOS/blob/16/local_manifest.xml) | *Coming Soon* |

</div>

---

## 🚀 Building from Source

- Initialize local repository
```
repo init -u https://github.com/LineageOS/android.git -b lineage-23.2 --git-lfs
```

- Clone your local manifest for Device
```
git clone https://github.com/XiaomiCreek/android.git -b 16 .repo/local_manifests
```

- Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

- Set up the build environment
```
. build/envsetup.sh
```

- Breakfast the target
```
Breakfast creek userdebug
```

- start compiling
```
m bacon
```
---

## 🔐 Security & Transparency

Creek device tree is **fully open source**. Every line of code is publicly available for review — from system components to build scripts. We believe users have the right to inspect what's running on their devices.

When choosing a custom ROM, we recommend:

- ✅ Verifying that source code is publicly available
- ✅ Reviewing recent commit history and development activity
- ✅ Checking maintainer reputation and community trust

---

<div align="center">
  
### ⭐ Thanks for checking out Project XiaomiCreek!

**Now focused on Android 16 — let's keep *creek* alive together 🚀**

</div>
