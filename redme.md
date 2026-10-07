# Lenovo IdeaPad Gaming 3 15ACH6 Ryzen EFI

OpenCore EFI configuration for the Lenovo IdeaPad Gaming 3 15ACH6 with an AMD Ryzen 5 5600H.

## Hardware

| Component | Details |
|---|---|
| Laptop | Lenovo IdeaPad Gaming 3 15ACH6 |
| CPU | AMD Ryzen 5 5600H |
| GPU | NVIDIA GTX 1650 |
| RAM | 16 GB |
| Bootloader | OpenCore |

## Compatibility

| Feature | Status |
|---|---|
| Camera | ✅ Working |
| Brightness | ✅ Working |
| Speakers | ✅ Working |
| Microphone | ✅ Working |
| Ethernet | ✅ Working |
| Bluetooth | ✅ WORKING |
| Wi-Fi | ❌ Not working (im trying to fix it)|
| NVIDIA GPU | ❌ Not supported |

## Requirements

- Ryzen 5 5600H Lenovo IdeaPad Gaming 3
- USB drive of at least 18 GB
- macOS installer
- Ethernet or Android USB tethering
- Secure Boot disabled
- time

## BIOS settings

- Disable Secure Boot.
- Disable the dedicated NVIDIA GPU.
- Set integrated graphics memory to 2 GB.
- Boot in UEFI mode.

## Notes
GENERATE YOUR OWN SMBIOS
## Credits

- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [AMD Ryzen Guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html)
