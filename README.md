# MacOS 15 OC EFI for Legion R9000P 2021H (5800H + 3060 Laptop)

> [!WARNING]
> It's a rather minimal/rough EFI that mainly focuses on testing [nullmoth/nvidia-macos-driver](https://github.com/nullmoth/nvidia-macos-driver).
>
> Known issues:
>
> - unusable functions: wifi, bluetooth, ~~audio~~

Verified driver 1.15.0 on OS 15.8.1

Some tips:

- Using hybird mode during OS install
- Turn to dGPU only mode after finishing the manual install steps in [nullmoth/nvidia-macos-driver](https://github.com/nullmoth/nvidia-macos-driver)
- Following [usbtoolbox/tool](https://github.com/usbtoolbox/tool) 's guide to replace `UTBMap.kext` before OS install
- **Do not use default wallpaper**

My specs:

| Component | Model       |
| --------- | ----------- |
| CPU       | 5800H       |
| GPU       | 3060 Laptop |
| SSD       | SN730       |
| WIFI      | AX210       |
