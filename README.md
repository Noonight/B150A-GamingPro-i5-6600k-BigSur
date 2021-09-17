# MSI B150A GAMING PRO i5 6600k BigSur

### Used OC guide

### Installed Big Sur 11.5.2

## Setup

- B150A GAMING PRO
- i5 6660k
- hd 530
- 16gb ram
- 512gb ssd
- 2560x1080 monitor. HDMI

> Note: By default `hd 530` max resolution 1920x1080. 

## OC

`Version` - `0.7.2`

> Note: was released 0.7.3. 

> Note: ProperTree version - before release OC 0.7.3 Not sure how it affect

## Kexts

| Kext | Version |
| ------ | ------ |
| VirtualSMC | 1.2.8 |
| Lilu | 1.5.7 |
| WhateverGreen | 1.5.4 |
| IntelMausi | 1.0.8 |
| AppleALC | 1.6.5 |

## BIOS

- `Restore default`
- In `Overclocking`, `CPU Features` make `Intel VT-D` and `CFG Lock` to `Disabled`
- In `Advance`, `Super IO Configuration` make `Serial(COM) Port` to `Disabled`
- In `Advance`, `USB Configuration` make `XHCI Hand-off` to `Enabled`
- Make first boot from `USB flash`

Taken bios configuration from [this site](https://www.codejam.info/2019/03/macos-high-sierra-msi-h110m-pro-d-skylake-nvidia-pascal.html)

## Installation process

1. Erase disk 
  1. Configure `Format` - `APFS`, `Scheme` - `GUID Partition Map`
2. Start install

> Note: Had black screen long time `~2 hrs`. Don't reboot, wait.

##### TODO:
- fix resoultion
