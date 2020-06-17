# MSI-B360M-Mortar-Hackintosh-OC
Another (almost) fully functioning OpenCore EFI for MSI B360M Mortar

### OpenCore: 0.5.9

## Hardware
- CPU: Intel i5 9400
- MB: MSI B360M Mortar
- GPU: Sapphire RX 5500 XT 8GB
- Display: AOC U2790 (27 inches, 3840x2160) via dp
- RAM: 16GB
- HDD: Intel NVME 256GB
- Wifi + Bluetooth: BCM943602CS

## Caveat

- You may want to generate your own CPUFriendDataProvider.kext. Alternatively, you can delete CPUFriend.kext and CPUFriendDataProvider.kext, and the corresponding entries in config.plist.
- You may want to generate your own USBPorts.kext. You can delete USBInjectAll.kext if USBPorts.kext is added, and delete the corresponding entry in config.plist.

(remember to rebuild cache if kexts are deleted)

## Credit:

[GeQ1an](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI)<br>
[ArchFeh](https://github.com/ArchFeh/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI-without-core-graphic)<br>
