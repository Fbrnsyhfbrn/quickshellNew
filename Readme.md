
# 📦 Custom Quickshell For Hyprland — *illogical-impulse* 🚀  

![Arch Linux](https://img.shields.io/badge/Arch_Linux-%231793D1.svg?style=for-the-badge&logo=arch-linux&logoColor=white)  
![Hyprland](https://img.shields.io/badge/Hyprland-black?style=for-the-badge&logo=linux&logoColor=white)  
![Quickshell](https://img.shields.io/badge/Quickshell-%23FF6F61.svg?style=for-the-badge&logo=gnometerminal&logoColor=white)  
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)  
![Made With Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=for-the-badge)  

> Keep your Quickshell fresh, clean & fast 🔥  

---

## 📝 Info
- **Name:** Custom Quickshell  
- **Description:** Config yang bisa langsung dipaste/replace di `.config` ✨  

---

## 📦 Requirements
- **Hyprland — illogical-impulse** 🖥️  
- **All Linux Distro** 🐚  

---

## ⚡ Usage
### 1. Install Illogical-impulse

- install = https://github.com/end-4/dots-hyprland

### 2. . Backup sebelum replace

- example = mv /to/path/.config/quickshell/  /to/path/.config/quickshell.Backup/

### 3. Replace all .config to your directory, If you use a network manager like in KDE or Gnome, please see [Tips Network Manager]

- example = cp /to/path/Downloads/quickshell/  /to/path/.config/quickshell/


## 🔧[TIPS ENABLE NETWORK]

- Remove Folder quickshell/ii/modules/bar/network.qml quickshell/ii/modules/bar/BarContent.qml and quicshell/ii/modules/sidebar/* From the zip you get 🛠️
- Or Replace modules bar default to quickshell custom 💡
- Or you can also turn on the command below
```
**/patch/to/.config/quickshell/ii/modules/bar/BarContent.qml**
 search **MaterialSymbol** and turn off the command underneath or save it

                    MaterialSymbol {
                         Layout.rightMargin: indicatorsRowLayout.realSpacing
                         text: Network.materialSymbol
                         iconSize: Appearance.font.pixelSize.larger
                         color: rightSidebarButton.colText
                     }

 ```

---
## [ENABLE BLUR WINDOW HYPERLAND]
- [blurhyperland](https://github.com/Fbrnsyhfbrn/BlurHyperland.git)

## ✨ Features
- Simple Control Music and Minimalist ✨
- Notification is in the middle 📜
- Blur effect on windows in all applications 🎟️
- Nothing has changed again from the default there 🛠️
- If you use the [Network Manager Base KDE, Gnome, etc] you can activate / Remove bar in quicshell/ii/modules 💡
- Tested on Arch Linux & other distros 🐧
---

## 👀 View
![Example](expl.png)  
![Example](Default.png)  
![Example](notifandmedia.png)
## ✨ Update Bar Preview
![Example](U-Bar.png)  

##❗*Illogical impulse* is still listed here, I just change what I want to change
![Example](original.png)
---

## 📜 License
MIT License — use, modify, share freely 📜

---

## 👤 Author
**Fbrnsyh**  

---

## 🔗 Source
- [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland)  
- [Hyprland](https://hypr.land/)  

---

## 💡 Quote
> *"Keep your tools sharp, your code clean, and your mind open."*  
