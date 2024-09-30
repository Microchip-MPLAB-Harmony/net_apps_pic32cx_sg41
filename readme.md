![Microchip logo](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_logo.png)
![Harmony logo small](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_mplab_harmony_logo_small.png)

# Harmony 3 Net library application examples for PIC32CX SG41 family

MPLAB® Harmony 3 is an extension of the MPLAB® ecosystem for creating embedded firmware solutions for Microchip 32-bit SAM and PIC® microcontroller and microprocessor devices.  Refer to the following links for more information.

- [Microchip 32-bit MCUs](https://www.microchip.com/design-centers/32-bit)
- [Microchip 32-bit MPUs](https://www.microchip.com/design-centers/32-bit-mpus)
- [Microchip MPLAB X IDE](https://www.microchip.com/mplab/mplab-x-ide)
- [Microchip MPLAB® Harmony](https://www.microchip.com/mplab/mplab-harmony)
- [Microchip MPLAB® Harmony Pages](https://microchip-mplab-harmony.github.io/)

This repository contains the MPLAB® Harmony 3 Net library application examples for PIC32CX SG41 family

- [Release Notes](./release_notes.md)
- [Microchip Software License Agreement](Microchip_SLA001.md)

# Contents Summary

| Folder     | Description                                               |
| ---        | ---                                                       |
| apps       | Contains Net library example applications        |
| docs       | Contains documentation in html format for offline viewing (to be used only after cloning this repository onto a local machine). Use [github pages](https://microchip-mplab-harmony.github.io/net_apps_pic32cx_sg41/) of this repository for viewing it online. |

## Code Examples

The following applications are provided to demonstrate the typical or interesting usage models of the Net libraries.

| Name | Description |
| ---- | ----------- |
| [iperf_demo](./docs/GUID-AC846A86-7D49-495E-9FB4-0DAF3B3957A0.html) | This example application shows running iperf and measuring the network performance |
| [tcpip_client_server](./docs/GUID-2926F4D6-8723-46AA-AE9A-4AFEDC9E1B49.html) | This example application shows a multi-threaded example with TCP and UDP server and client threads |
| [tcpip_tcp_client](./docs/GUID-1DF603D1-C7CF-4760-B50E-3D6611E5465E.html) | This example application shows a TCP Client demo using Harmony native API |
| [tcpip_tcp_client_server](./docs/GUID-F41A7C22-A9E5-414A-9B87-7B23FED090B8.html) | This example application shows a TCP Client and Server demo using Harmony native API |
| [tcpip_tcp_demo_at24mac](./docs/GUID-532DD798-B9C0-4F9C-A503-87D79736D941.html) | This example application shows a TCP Client and Server demo with AT24MAC402 Serial EEPROM using Harmony native API |
| [tcpip_tcp_server](./docs/GUID-28A48072-12AA-4288-97C3-C63924074387.html) | This example application shows a TCP Server demo using Harmony native API |
| [tcpip_udp_client](./docs/GUID-FAB9410A-CB2E-4AA1-B963-18D42B18668A.html) | This example application shows a UDP Client demo using Harmony native API |
| [tcpip_udp_client_server](./docs/GUID-F078D3F7-7A65-4611-B10E-8526FE0ACF3D.html) | This example application shows a UDP Client and Server demo using Harmony native API|
| [tcpip_udp_server](./docs/GUID-38F33EEA-17C0-4AAA-9965-F68685AFF846.html) | This example application shows a UDP Server demo using Harmony native API |
| [web_ftp_server_usb_fatfs](./docs/GUID-BA8A46CC-72C7-40A5-A4CB-99A1B08CA65E.html) | This example application shows a Web server and FTP server with FAT FS file system on the USB flash device |
| [web_net_server_nvm_mpfs](./docs/GUID-BE0BE681-87E6-4A11-8957-87CE233A69EB.html) | This example application shows a Web server with Microchip Proprietary File System (MPFS) in the Non-Volatile Memory (NVM) |
| [web_net_server_sdcard_fatfs](./docs/GUID-38E13DEA-6C0F-4970-BDB4-6B6892C535FE.html) | This example application shows a Web server with FAT FS file system on the external SD card |
| [wolfssl_tcp_client](./docs/GUID-68074BE4-0776-4782-B986-1338F33E5F0A.html) | This example application shows a connection to a Web server using TLS to encrypt the connection with wolfSSL |
| [wolfssl_tcp_server](./docs/GUID-6CC6170D-CE91-4DD2-AD84-CE7115D75E02.html) | This example application shows Web server demo accepting encrypted TLS connections using wolfSSL |
____


[![License](https://img.shields.io/badge/license-Harmony%20license-orange.svg)](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41/blob/master/Microchip_SLA001.md)
[![Latest release](https://img.shields.io/github/release/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41.svg)](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41/releases/latest)
[![Latest release date](https://img.shields.io/github/release-date/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41.svg)](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41/releases/latest)
[![Commit activity](https://img.shields.io/github/commit-activity/y/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41.svg)](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41/graphs/commit-activity)
[![Contributors](https://img.shields.io/github/contributors-anon/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41.svg)]()

____

[![Developer Help](https://img.shields.io/badge/Youtube-Developer%20Help-red.svg)](https://www.youtube.com/MicrochipDeveloperHelp)
[![Developer Help](https://img.shields.io/badge/XWiki-Developer%20Help-torquiose.svg)](https://developerhelp.microchip.com/xwiki/bin/view/software-tools/harmony/)
[![Follow us on Youtube](https://img.shields.io/badge/Youtube-Follow%20us%20on%20Youtube-red.svg)](https://www.youtube.com/user/MicrochipTechnology)
[![Follow us on LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20us%20on%20LinkedIn-blue.svg)](https://www.linkedin.com/company/microchip-technology)
[![Follow us on Facebook](https://img.shields.io/badge/Facebook-Follow%20us%20on%20Facebook-blue.svg)](https://www.facebook.com/microchiptechnology/)
[![Follow us on Twitter](https://img.shields.io/twitter/follow/MicrochipTech.svg?style=social)](https://twitter.com/MicrochipTech)

[![](https://img.shields.io/github/stars/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41.svg?style=social)]()
[![](https://img.shields.io/github/watchers/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41.svg?style=social)]()


