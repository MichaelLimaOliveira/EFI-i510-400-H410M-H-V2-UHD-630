# Gigabyte-H410M-H-V2 + Intel i5 10400 (iGPU) OpenCore Configuration

Baseline config for Gigabyte-H410M-H-V2 and Intel i5 10400 Hackintosh

![Epic Flex](docs/Screenshot.png)

## System Information

| Part        |                                                                        |
| ----------- | ---------------------------------------------------------------------- |
| Motherboard | Gigabyte H410M H V2 (OBS. V3 dont work IGPU)                           |
| CPU         | Intel i5 10400 Hexa core 4Ghz max                                      |
| GPU         | Intel UHD Graphics 630                                                 |
| Audio       | Realtek ALC897 @ Intel Comet Point-H PCH - cAVS (Audio, Voice, Speech) |
| Ethernet    | Realtek PCIe GbE Family Controller (192. [ TRIAL VERSION ])            |
| Chipset     | H470                                                                   |
| Cabinet     | Rise Mode Z3 Glass, Black - RM-Z03-03-FB                               |
| Bios        | FG (june 2023)                                                         |

## Tested OS

| macOS Version             | Status |
| ------------------------- | ------ |
| macOS 12.4                | ✅     |
| macOS 12.5                | ✅     |
| macOS 12.5.1              | ✅     |
| macOS 12.6                | ✅     |
| macOS 12.6.X              | ✅     |
| macOS 13                  | ✅     |
| macOS 13.0.1              | ✅     |
| macOS 13.1                | ✅     |
| macOS 13.2                | ✅     |
| macOS 13.2.1              | ✅     |
| macOS 13.3                | ✅     |
| macOS 13.3.1              | ✅     |
| macOS 13.3.1 (a)          | ✅     |
| macOS 13.4                | ✅     |
| macOS 13.4.1              | ✅     |
| macOS 13.6.1              | ✅     |
| macOS 14 Developer Beta 1 | ✅     |
| Others                    | N/A    |

## Next Steps

In this configuration, You have to use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate your own SMBIOS. I recommend using `iMac20,1`.

ACPIs here came from the OpenCore docs. I have compiled my own ACPIs and if you also wish to do so, this [guide](https://dortania.github.io/Getting-Started-With-ACPI/) will help you out. It's easy.

**Remember, if you made changes to ACPIs or kexts, reload them in the config first!**

If you are ready, then might as well test it!

## Updates

This repository will be updated regularly every new macOS Versions. If there are no updates, then this EFI works on that version. Though, I may get tired of updating this in the near future so might as well try to fix issues on your own.

## Props

Gabriel Luchina repository 10th Base EFI

Visite their Github: https://github.com/luchina-gabriel
