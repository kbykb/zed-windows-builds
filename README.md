# Unofficial builds of Zed for Windows

## Is it safe?

This repository is just a [simple GitHub workflow](./.github/workflows/build.yml) that builds Zed from `zed-industries/zed`.

See the [Zed homepage](https://zed.dev/) or [official repository](https://github.com/zed-industries/zed) for more details.

## Prerequisites

You may need Microsoft Visual C++ Redistributable:
- [ARM64](https://aka.ms/vs/17/release/vc_redist.arm64.exe)
- [x86](https://aka.ms/vs/17/release/vc_redist.x86.exe) 
- [x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)

## Usage

The default build (zed-windows-{{ VERSION }}.zip) uses [Vulkan](https://vulkan.lunarg.com/). If nothing happens when launching zed.exe, please try updating your graphics drivers:

- [NVIDIA Drivers](https://www.nvidia.com/en-us/drivers/)
- [AMD Drivers](https://www.amd.com/en/support/download/drivers.html)
- [Intel Drivers](https://www.intel.com/content/www/us/en/download-center/home.html)

Feel free to Fork and Star!
