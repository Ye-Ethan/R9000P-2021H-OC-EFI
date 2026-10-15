# MacOS 26 OC EFI for Legion R9000P 2021H (5800H + 3060 Laptop)

> [!CAUTION]
>
> - Tahoe with driver 2.0.0 is a little choppy (but less buggy?) than Sequoia with driver 1.15.0 for now.

> [!WARNING]
>
> - Replace the SMBIOS using [GenSMBIOS](https://github.com/corpnewt/gensmbios)
> - ~~**DO NOT USE DEFAULT WALLPAPER** to avoid glitch / black screen / screen flicker (HEIC decoding bug)~~

## Verification

|     | Component            | Model               |
| --- | -------------------- | ------------------- |
| ✅  | NVIDIA Driver        | 2.0.0               |
| ✅  | OS                   | 26.7.1              |
| ✅  | internal BOE monitor | 2560x1600@165hz     |
| ✅  | external monitor     | 2560x1440@60hz@hdmi |
| ✅  | CPU                  | 5800H               |
| ✅  | GPU                  | 3060 Laptop         |
| ✅  | SSD                  | SN730               |
| ✅  | WIFI / Bluetooth     | AX210               |
| ✅  | Audio                | ALC287              |

## Tips

**OS install**

- Using hybird mode during OS install
- Turn to dGPU only mode after finishing the manual install steps in [nullmoth/nvidia-macos-driver](https://github.com/nullmoth/nvidia-macos-driver)
- Following [usbtoolbox/tool](https://github.com/usbtoolbox/tool) 's guide to replace `UTBMap.kext` before OS install

## Refs

- [wifi](https://github.com/laobamac/itlwm/)
- [bluetooth](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/issues/505#issuecomment-3370000263)
- [audio](https://github.com/laobamac/SimpleHDA)
