# Hackintosh Big Sur with OpenCore on Dell Inspiron 5570

This is a post-install EFI folder based on OpenCore bootloader for macOS Big Sur and Catalina.

Laptop specifications:
- CPU : Intel(R) Core(TM) i5-8250U CPU @ 1.80GHz - 3.4GHz (Kaby Lake R)
- GPU : Intel UHD Graphics 620 (Kaby Lake R)
- RAM : 16GB DDR4 2400 Mhz Samsung
- SSD : WD Blue 128
- Ethernet : Realtek/Intel
- Wifi : Qualcomm Atheros **** (Unsupported/Not Working)
- SoundCard : Realtek ALC3236

What is working: 
- Graphics acceleration
- Audio/microphone/audio control
- Trackpad
- Battery Managment
- And everything else

What is not working: 
- Sleep
- Wifi/Bluetooth (Ethernet is working perfectly)
- Brightness control (F11 & F12)

Follow the Official OpenCore guide on [Dortania](https://dortania.github.io/getting-started/) then you can use my EFI files and config.

Happy hackintoshing :)

I would like to give credits to : 
The dortania team for their hard work on the OpenCore bootloader and for the good documentation & everyone contributing on making hackintoshing easy and accessible by developing drivers, kernel extensions, tutorials and more...
