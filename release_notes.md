![Microchip logo](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_logo.png)
![Harmony logo small](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_mplab_harmony_logo_small.png)

# Microchip MPLAB® Harmony 3 Release Notes


## Harmony 3 Network Application Examples for PIC32CX SG41 Family v3.0.1

The applications demonstrate the typical usage of Harmony 3 TCP/IP Stack on a hardware board with PIC32CX1025SG41128 device.
- All applications use MCC for configuration.
- All applications created with TCP/IP Configurator Plugin.

### New Features
- None

### Known Issues
- XC32 v4.30 compiler has a known issue wherein applications built with certain configurations could cause a runtime exception. It is recommended to use v4.21 of the XC32 compiler until a newer version becomes available.

### Development Tools

- [MPLAB® X IDE v6.15](https://www.microchip.com/mplab/mplab-x-ide) or later
- [MPLAB® XC32 C/C++ Compiler v4.21](https://www.microchip.com/mplab/compilers)
- [MPLAB® Code Configurator (MCC) 5.3.7](https://www.microchip.com/en-us/tools-resources/configure/mplab-code-configurator) or later
- [Harmony net repository, 3.10.1](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.10.1)
- [Harmony net\_apps\_pic32cx\_sg41 demo apps repositories, 3.0.1](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41/tree/v3.0.1)


### Development Kit Support

This release supports applications for the following development kit.

| Development Kits |
| --- |
| [PIC32CX SG41 Curiosity Ultra](https://www.microchip.com/en-us/development-tool/EV06X38A) |


## Net release notes

- See the [Net 3.10.1 Release notes](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.10.1)

---

## Harmony 3 Network Application Examples for PIC32CX SG41 Family v3.0.0

The applications demonstrate the typical usage of Harmony 3 TCP/IP Stack on a hardware board with PIC32CX1025SG41128 device.
- All applications use MCC for configuration.
- All applications created with TCP/IP Configurator Plugin.

### New Features
- None

### Known Issues
- MPLAB® Harmony 3 SYS\_FS File System service has dependency on [FileX](https://github.com/azure-rtos/filex) and [littlefs](https://github.com/littlefs-project/littlefs), hence FileX and littlefs need to be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki) /by cloning them.

### Development Tools

- [MPLAB® X IDE v6.10](https://www.microchip.com/mplab/mplab-x-ide) or later
- [MPLAB® XC32 C/C++ Compiler v4.30](https://www.microchip.com/mplab/compilers) or later
- [MPLAB® Code Configurator (MCC)](https://www.microchip.com/en-us/tools-resources/configure/mplab-code-configurator), 5.3.7 or later
- [Harmony net repository, 3.10.0](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.10.0)
- [Harmony net\_apps\_pic32cx\_sg41 demo apps repositories, 3.0.0](https://github.com/Microchip-MPLAB-Harmony/net_apps_pic32cx_sg41/tree/v3.0.0)


### Development Kit Support

This release supports applications for the following development kit.

| Development Kits |
| --- |
| [PIC32CX SG41 Curiosity Ultra](https://www.microchip.com/en-us/development-tool/EV06X38A) |


## Net release notes

- See the [Net 3.10.0 Release notes](https://github.com/Microchip-MPLAB-Harmony/net/tree/v3.10.0)

