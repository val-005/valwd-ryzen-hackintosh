# valwd-hackintosh-ryzen
![Logo](https://www.podfeet.com/blog/wp-content/uploads/2022/02/OpenCore-Logo-bg.png)
## Setup
[![OpenCore](https://img.shields.io/badge/OpenCore-v0.9.4-blue?style=flat&logo=okta)](https://github.com/acidanthera/OpenCorePkg)

| **Category**   | **Component**                 		
|----------------|--------------------------------------|
|**CPU**		       |Ryzen 7 5800X 		            |	
|**Motherboard**		       |MSI B450 Gaming Plus	            |										      
|**GPU1**		       |NVIDIA RTX 2070 (Disabled with ACPI) 				     		 										       |
|**GPU2**		       |AMD RX 560 4GO 				     		 										       |
|**RAM**         |32GO (2x16GB) Corsair Vengeance RGB PRO 3200mhz CAS 16              		   |
|**NVME**         |WD BLUE SN570 500GB M.2	 		                |									      
|**Wi-Fi/BT**    |BCM94360CD (Apple genuine)			     		                |	     
|**Ethernet**    |Realtek RTL8111H				 		                    |										      								      

### Versions
- **OpenCore:** 0.9.4
- **macOS:** 13.5.1
- **SMBIOS** MacPro7,1

### Kexts Versions
| **Name**   | **Version**                 		
|----------------|--------------------------------------|
|**Lilu.kext**		       |1.6.7		            |										      
|**RealtekRTL8111.kext**		       |2.4.2 				     		 										       |
|**VirtualSMC.kext**		       |1.3.2			     		 										       |
|**WhateverGreen.kext**         |1.6.6              		   |
|**AMDRyzenCPUPowerManagement.kext**         |0.7.1 		                |									      
|**NVMeFix.kext**    |1.1.1			     		                |	     
|**RadeonSensor.kext**    |1.1.0		 		                    |	
|**SMCRadeonGPU.kext**    |1.1.0		 		                    |
|**RestrictEvents.kext**    |1.1.2	 		                    |		

### BIOS configuration
- Fast Boot: Disabled
- Secure Boot : Disabled


### What is working:
- Wifi & Bluetooth
- Ethernet
- Receiving and sending calls
- Airdrop, Handoff and most continuity functions
- Apple services ([More info](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html))

![Desktop](https://cdn.discordapp.com/attachments/935250431523848322/1147638156670288022/Capture_decran_2023-09-02_a_23.02.21.png)