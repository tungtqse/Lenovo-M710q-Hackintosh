# Lenovo-M710q-Hackintosh

OpenCore EFI compatible with macOS Big Sur for Lenovo ThinkCentre M710q
My unit is equiped with a Xeon E2286M, but should works with any M710q device with modified BIOS to support 8th gen CPUs 

![Screen Shot 2022-11-27 at 23 58 37](https://user-images.githubusercontent.com/48742600/204149356-7faf80f9-3335-4aaa-b9cb-54b96ccc6b11.png)


![Screen Shot 2022-11-27 at 23 07 29](https://user-images.githubusercontent.com/48742600/204148030-a5f3a3b6-7608-4377-a078-5f0bcd696967.png)

**System Specs :**


| Component | Specifications |
|-----:|---------------|
|CPU	|Intel® Xeon™ E-2286M(Mobile)
|iGPU	|Intel® UHD Graphics 630
|RAM	|2 * Kingston 8GB DDR4 2666Mhz
|NVMe	|WD Blue SN570 500GB
|LAN	|Intel I219-V
|Audio|Realtek ALC294
|WiFi & Bluetooth|	Apple BCM94360CS2 with adapter to NGFF
|SMBIOS|	MacMini8,1
|BootLoader|	OpenCore 0.8.4

**What Works :**

 - [x] Intel UHD Graphics P630 iGPU DP Output
 - [x] DP to HDMI Adapter
 - [x] ALC294 Internal Speakers
 - [x] ALC294 & DP Audio Output
 - [x] ALC294 Audio Input
 - [x] All USB Ports
 - [x] Intel I219-V
 - [x] Apple Wi-Fi & Bluetooth, Airdrop, Handoff (not test)
 - [x] NVRAM
 
**UEFI Firmware :**

Modified M710q BIOS to support 8th gen CPUs

Disable: CSM

In Bios change DVMT to 64MB or 128MB

# Credits

- [wxjiyc](https://github.com/wxjiyc/Lenovo-M710q-QNCT-Hackintosh) based on @wxjiyc's EFI files.
- [nvt194](https://github.com/nvt194/Lenovo-M910q-Hackintosh) efi files
- [Dortania](https://github.com/dortania) for great and detailed guides.
