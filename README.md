# MacOS 15 OC EFI for Legion R9000P 2021H (5800H + 3060 Laptop)

Verified driver 1.15.0 on OS 15.8.1

Some tips:

**OS install**

- Using hybird mode during OS install
- Turn to dGPU only mode after finishing the manual install steps in [nullmoth/nvidia-macos-driver](https://github.com/nullmoth/nvidia-macos-driver)
- Following [usbtoolbox/tool](https://github.com/usbtoolbox/tool) 's guide to replace `UTBMap.kext` before OS install

**In OS**

- **DO NOT USE DEFAULT WALLPAPER** to avoid glitch / black screen / screen flicker
- wifi: [AirportItlwm.kext](https://github.com/laobamac/itlwm/)
- [bluetooth](https://www.tonymacx86.com/threads/intel-bluetooth-ax210-and-macos-15-3-2-sequoia.331670/)

**My specs**

| Component | Model       |
| --------- | ----------- |
| CPU       | 5800H       |
| GPU       | 3060 Laptop |
| SSD       | SN730       |
| WIFI      | AX210       |
