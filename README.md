# MSI-B360M-Mortar-Hackintosh-OC
Another (almost) fully functioning OpenCore EFI for MSI B360M Mortar

### OpenCore: 0.5.9

## Hardware
- CPU: Intel i5 9400
- MB: MSI B360M Mortar
- GPU: Sapphire RX 5500 XT 8GB
- Display: AOC U2790 (27 inches, 3840x2160) via dp
- RAM: 16GB
- SSD: Intel NVME 256GB
- Wifi + Bluetooth: BCM943602CS

Another SSD (Samsung 860 Evo) is installed for Windows 10. OC set to boot macOS as default. Function key F11 to boot Windows 10 from the Samsung SSD.

## Caveat

- You may want to generate your own CPUFriendDataProvider.kext. Alternatively, you can delete CPUFriend.kext and CPUFriendDataProvider.kext all together, and disable / delete the corresponding entries in config.plist.
- You may want to generate your own USBPorts.kext or use USBInjectAll.kext (mutually exclusive).
- You can also delete IntelMausi.kext if ethernet is not needed, and disable / delete the entry in config.plist.

(remember to rebuild cache if kexts are deleted)

## Credit:

[GeQ1an](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI)<br>
[ArchFeh](https://github.com/ArchFeh/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI-without-core-graphic)<br>
