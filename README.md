# Thinkpad T470 Opencore
## Opencore Hackintosh

**Infomation Laptop**

<details>  
<summary><strong>Hardware</strong></summary>  

|    Category            |Component                           |Note                       
|----------------|-------------------------------|-----------------------------|
|CPU|Intel i5-6300U               
|GPU|Intel HD 520           
|SSD|Toshiba 180GB       
|MEMORY|8 Gb DDR4 2133 
|BATTERY|Dual Battery
|CAMERA|720p Camera
|WIFI & BT|Broadcom wireless DW1830 BCM943602BAED
|WWAN|Sierra Wireless EM7455 LTE
<details>  

<details>  
<summary><strong>Software</strong></summary> 
    
|    Component            |Version                           
|---------------------------|-----------------------------|
|MacOS Catalina|10.15.7
|OpenCore|0.6.1
|Bios|1.64
<details>  

## Settings

<details>  
<summary><strong>BIOS Settings</strong></summary>
    


1. Config
* USB UEFI Bios Support -> Enabled
* Keyboard Mouse
    - Trackpoint -> Enabled
    - Trackpad -> Enabled
* Display
    - Total Graphics Memory -> 512 MB
    - Boot Time Extension -> Disabled
* Thunderbolt 3
    - Wake by TB3 -> Disabled
    - Support in Preboot Env -> Disabled
2. Security
* Fingerprint
    - Predesktop Auth -> Disabled
    - Security Mode -> Normal
* Security Chip
    - TPM 2.0
    - Security Chip -> Disabled/All
* Memory Protection -> Enabled
* Virtualization
    - Intel Virtualization -> Enabled
    - Intel VT -d -> Enabled
* I/O port access -> Enable All
* Secure Boot -> Disabled
* Intel SGX -> Disabled
* Device Guard -> Disabled
3. Startup
* UEFI/Legacy -> UEFI only
* CSM Support -> No
<details>  
