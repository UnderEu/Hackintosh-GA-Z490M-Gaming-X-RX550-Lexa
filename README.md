# Hardware:

- Processor: Intel Core i5-10400F (Comet Lake)
- Memory: 2 x 8GB Crucial Ballistix DDR4-3000MHz (Total: 16GB)
- Motherboard: Gigabyte Z490M Gaming X - BIOS: F21
- Graphics Card: AMD RX550 4GB (Lexa Core)
- Storage: 480GB Crucial BX500 SSD
- Wireless: TP-Link Archer T2U Nano USB

# Bootloader
OpenCore v0.7.6-RELEASE

# Operating System
![About this Mac](https://user-images.githubusercontent.com/16519758/147834797-bb6af13f-86ef-43db-ae98-4ab4905886d7.png)

## BIOS Settings

**Disabled:**

- Fast Boot
- VT-d
- CSM
- Intel SGX
- Intel Platform Trust
- Trusted Platform Module
- CFG Lock (MSR 0xE2 write protection)
- Secure Boot

**Enabled:**

- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS type: Other OS


# Highlights:
- Installation procedure is 99.9% based on OpenCore's guide: https://dortania.github.io/OpenCore-Install-Guide

- SIP + GateKeeper is disabled; it makes things WAAAAAAAAY easier to set-up.

- Graphics Card doesn't work out of the box (Explained here: https://github.com/dortania/bugtracker/issues/129 ), however there's a trick to spoof the device ID and make the OS recognizes it as a RX 560 of some sort. Multiple monitors, UI effects like animations, transparency and HW-Accelerated tasks with Adobe software, Wondershare Filmora works fine. How to do it here: https://www.reddit.com/r/hackintosh/comments/lnadiw/comment/go6kjpy/?context=3

- Wireless: AirDrop, Hand-off, Continuity, Sidecar etc. doesn't work.
Driver installation process here: https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter

- USB ports were mapped according to the following scheme - Case uses 2 x USB2 ports + 1 x USB3 port
![Hackintool - In use USB ports](https://user-images.githubusercontent.com/16519758/147834787-36f4ea91-6be3-42a9-be1f-b6c46a84a3b7.png)


Screenshots (System Report):
![System Report - Audio](https://user-images.githubusercontent.com/16519758/147834807-73a1132f-9614-49b8-b88a-8165ea56c5ca.png)
![System Report - Graphics](https://user-images.githubusercontent.com/16519758/147834811-30d700f3-f34d-4ffb-8da6-b32a707b723d.png)
![System Report - Network](https://user-images.githubusercontent.com/16519758/147834812-795aa177-1103-4a17-9644-567c60ea9650.png)
![System Report - SATA](https://user-images.githubusercontent.com/16519758/147834996-70f5909a-79f9-4bc4-8fe6-f56f3dad6d74.png)
![System Report - USB](https://user-images.githubusercontent.com/16519758/147834814-7d14f790-f83e-48e3-aa68-1fd461c70caf.png)
