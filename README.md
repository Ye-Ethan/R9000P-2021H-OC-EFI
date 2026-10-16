# MacOS 26 OC EFI for Legion R9000P 2021H (5800H + Vega 8)

> [!CAUTION]
>
> Occasional [freezes](https://github.com/ChefKissInc/NootedRed/issues/158) may occur, especially for some apps like chrome.

> [!WARNING]
>
> - Replace the SMBIOS using [GenSMBIOS](https://github.com/corpnewt/gensmbios)

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

## Tips

**OS install**

- Following [usbtoolbox/tool](https://github.com/usbtoolbox/tool) 's guide to replace `UTBMap.kext` before OS install

## Refs

- [wifi](https://github.com/laobamac/itlwm/)
- [bluetooth](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/issues/505#issuecomment-3370000263)
- [audio](https://github.com/laobamac/SimpleHDA)
