# MacOS 15 OC EFI for Legion R9000P 2021H (5800H + 3060 Laptop)

> [!WARNING]
> Replace the SMBIOS using [GenSMBIOS](https://github.com/corpnewt/gensmbios)

## Verification

|     | Component        | Model       |
| --- | ---------------- | ----------- |
| ✅  | NVIDIA Driver    | 1.15.0      |
| ✅  | OS               | 15.8.1      |
| ✅  | CPU              | 5800H       |
| ✅  | GPU              | 3060 Laptop |
| ✅  | SSD              | SN730       |
| ✅  | WIFI / Bluetooth | AX210       |
| ✅  | Audio            | ALC287      |

## Tips

**ax210 bluetooth**

Make sure `bluetoothInternalControllerInfo` and `bluetoothExternalDongleFailed` related settings exist like the `config.plist` in this repo.

**OS install**

- Using hybird mode during OS install
- Turn to dGPU only mode after finishing the manual install steps in [nullmoth/nvidia-macos-driver](https://github.com/nullmoth/nvidia-macos-driver)
- Following [usbtoolbox/tool](https://github.com/usbtoolbox/tool) 's guide to replace `UTBMap.kext` before OS install

**Tune**

- **DO NOT USE DEFAULT WALLPAPER** to avoid glitch / black screen / screen flicker (HEIC decoding bug)

  Change to any normal image like builtin's pure color.

## Refs

- wifi: [AirportItlwm.kext](https://github.com/laobamac/itlwm/)
- [bluetooth](https://www.tonymacx86.com/threads/intel-bluetooth-ax210-and-macos-15-3-2-sequoia.331670/)
