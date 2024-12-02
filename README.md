# HP 247 G8 Hackintosh EFI 🌸  
_A minimalist EFI setup for the HP 247 G8 with Ryzen 3 3250U._

---

## ✨ Overview  
This repository contains the EFI folder for macOS on the HP 247 G8, built for Hackintosh enthusiasts who appreciate simplicity and efficiency. Please note: **Wi-Fi is non-functional** due to the Realtek wireless card, and SMBIOS customization is pending.  

**Specs:**  
- **Model:** HP 247 G8  
- **Processor:** AMD Ryzen 3 3250U  
- **Graphics:** Integrated Radeon Vega 3  
- **Wi-Fi:** Not supported (Realtek card)  
- **Bootloader:** OpenCore  

---

## ⚙️ Features  
- Basic macOS functionality on Ryzen.  
- Configured for maximum performance and minimal issues.  
- Support for future updates and customization.  

---

## 🚧 What's Missing?  
- **Wi-Fi Support**: No driver available for Realtek cards. Consider a USB Wi-Fi dongle or replacement card.  
- **SMBIOS Configuration**: You'll need to generate and customize your SMBIOS for iCloud and App Store access.  

> Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to create a unique and valid SMBIOS.  

---

## 📂 EFI Details  
- **OpenCore Version**: [Insert OpenCore version used]  
- **Kexts Included**:  
  - Lilu.kext  
  - WhateverGreen.kext  
  - VirtualSMC.kext  
  - AMD kernel patches  

---

## 🔧 Installation  

1. **Prepare USB:**  
   - Format your USB drive as `MacOS Extended (Journaled)` with a GUID partition table.  
   - Create a bootable macOS installer using Terminal.  

2. **Copy EFI Folder:**  
   - Replace the default EFI folder with the one provided here.  

3. **Customize SMBIOS:**  
   - Open `config.plist` with [ProperTree](https://github.com/corpnewt/ProperTree) and set your SMBIOS details.  

4. **BIOS Settings:**  
   - Disable Secure Boot.  
   - Enable AHCI mode for storage.  

---

## 🌸 Recommendations  

- Replace the Realtek wireless card with a macOS-compatible one, such as the **Broadcom BCM94360NG**.  
- Use an external USB Wi-Fi adapter if replacing the card isn't an option.  
- Stay updated with OpenCore and kexts for optimal performance.  

---

## 🖤 Disclaimer  
This EFI is provided "as-is." I am not responsible for any damage to your system. Ensure you have a backup before proceeding.  

---

### ✨ Aesthetics Matter  
_“In chaos, I find structure. In the unknown, I build systems.”_  

Enjoy the blend of beauty and utility. 🌌  
