<h3>1. Final result</h3>

![macOS Big Sur](/public/img/result.png "macOS Big Sur")

<h3>2. Specs</h3>

> Laptop model: Dell Inspiron 7566

| Component | Name                           |
| :-------- | :----------------------------- |
| CPU       | Intel Core i5-6300HQ (Skylake) |
| iGPU      | Intel HD Graphic 530           |
| dGPU      | NVIDIA GTX 960M                |
| Storage   | LITEON CV3-8D128-11 SATA 128GB |
| Display   | 15.6 inch Full HD (1920x1080)  |
| Audio     | Realtek ALC256 (ALC3246)       |

- macOS Big Sur 11.6.7
- OpenCore 0.8.1
<p>ㅤ</p>
<h3>3. Working</h3>

> Tested on macOS Big Sur & Monterey

- [x] Wifi
- [x] Ethernet
- [x] Bluetooth
- [x] Audio
- [x] 3.5mm Headphone
- [x] USB (All ports supported)
- [x] Touchpad & function buttons
- [ ] HDMI (Not working)
- [ ] NVIDIA GTX 960M (Not working)
<p>ㅤ</p>
<h3>4. Installation guide</h3>

- Just copy EFI folder to your EFI
- You'll need [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) & [ProperTree](https://github.com/corpnewt/ProperTree) to edit your PlatformInfo in config.plist (follow this <strong>[guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/skylake.html#platforminfo)</strong> to know how to config [PlatformInfo](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/skylake.html#platforminfo) in config.plist)
- For macOS Monterey, follow this <strong>[guide](https://dortania.github.io/OpenCore-Install-Guide/extras/monterey.html#bluetooth)</strong> to make bluetooth working back
<p>ㅤ</p>
<h3>5. Credits</h3>

> Thanks to:
- [Apple](https://www.apple.com/) (macOS)
- [OpenCore](https://github.com/acidanthera/OpenCorePkg) (bootloader)
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/) (guide)
