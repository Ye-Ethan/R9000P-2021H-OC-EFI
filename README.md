# MacOS 26 OC EFI for Legion R9000P 2021H (5800H + Vega 8)

> [!CAUTION]
>
> Occasional [freezes](https://github.com/ChefKissInc/NootedRed/issues/158) may occur, especially for some apps like chrome.

> [!WARNING]
>
> - Replace the SMBIOS using [GenSMBIOS](https://github.com/corpnewt/gensmbios)

## Usage

- If you want an one-time boot to bypass display issues during nullmoth driver testing:

  1. Backup your current EFI first
  2. Switch to this EFI
  3. Switch to hybrid mode
  4. Choose "NullMoth: start macOS once without the NVIDIA driver" in the OC menu

- If you want use this permanently, just make sure the nullmoth driver is uninstalled.

## Verification

|     | Component            | Model               |
| --- | -------------------- | ------------------- |
| ✅  | OS                   | 26.7.1              |
| ✅  | internal BOE monitor | 2560x1600@165hz     |
| ❌  | external monitor     | 2560x1440@60hz@hdmi |
| ✅  | CPU                  | 5800H               |
| ❌  | dGPU                 | 3060 Laptop         |
| ✅  | iGPU                 | Vega 8              |
| ✅  | SSD                  | SN730               |
| ✅  | WIFI / Bluetooth     | AX210               |
| ✅  | Audio                | ALC287              |
| ✅  | Trackpad             | -                   |

## Tips

**OS install**

- Following [usbtoolbox/tool](https://github.com/usbtoolbox/tool) 's guide to replace `UTBMap.kext` before OS install

## Refs

- [dgpu](https://github.com/nullmoth/nvidia-macos-driver)
- [igpu](https://github.com/ChefKissInc/NootedRed)
- [wifi](https://github.com/laobamac/itlwm/)
- [bluetooth](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/issues/505#issuecomment-3370000263)
- [audio](https://github.com/laobamac/SimpleHDA)
