# 💻 Dell Latitude 3340 OpenCore EFI for macOS Big Sur & Monterey 🍏

This is my custom **OpenCore EFI** configuration for running **macOS Big Sur** and **macOS Monterey** on the **Dell Latitude 3340** laptop.
The EFI **might** work on newer versions like Ventura, Sonoma or Sequoia, but do be informed that iGPU acceleration won't work.
If you patch it with OCLP it might work. I have not tested that.

EFI Tested on:
Dell Latitude 3340 - i3-4010U @ 1.7GHz @ 2 Cores, 4 Threads @ Intel HD Graphics 4400.

## ✅ Functional Features
- **Wi-Fi**: Fully working with the appropriate kexts. 🌐
- **Audio**: Sound output works as expected. 🔊
- **HDMI (Patched framebuffer)**: HDMI output is functional. 🎥
- **USB**: All USB ports are operational. 🔌
- **Hardware Acceleration**: iGPU Hardware Acceleration works. 📺

## ❌ Non-Functional Features
- **Ethernet**: Ethernet does not work currently and will require additional drivers or fixes. 🌐🚫
- **Bluetooth**: Bluetooth is non-functional and requires further tweaks to enable. 🌀

Note: Supply yourself with your own macOS installer.
