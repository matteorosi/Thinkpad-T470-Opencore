# Thinkpad T470 Opencore


## Hardware 

|    Category            |Component                           |Note                       
|----------------|-------------------------------|-----------------------------|
|CPU|Intel i5-6300U               
|GPU|Intel HD 520           
|SSD|       
|MEMORY|8 Gb DDR4 2400 
|BATTERY|Dual Battery
|CAMERA|720p Camera
|WIFI & BT|Intel card with WD1830A
|WWAN|Sierra Wireless EM7455 LTE

## Software 

|    Component            |Version                           
|---------------------------|-----------------------------|
|MacOS Catalina|10.15.7
|OpenCore|0.6.1
|Bios|1.64

## Bios Setting
BIOS Settings

### Config
* USB UEFI Bios Support -> Enabled
* Keyboard Mouse
- Trackpoint -> Enabled
- Trackpad -> Enabled
Display
Total Graphics Memory -> 512 MB
Boot Time Extension -> Disabled
Thunderbolt 2
Wake by TB3 -> Disabled
Support in Preboot Env -> Enabled
### Security
Fingerprint
Predesktop Auth -> Disabled
Security Mode -> Normal
Security Chip
TPM 2.0
Security Chip -> Disabled/All
Memory Protection -> Enabled
Virtualization
Intel Virtualization -> Enabled
Intel VT -d -> Disabled
I/O port access -> Enable All
Secure Boot -> Disabled
Intel SGX -> Disabled
Device Guard -> Disabled
### Startup
UEFI/Legacy -> UEFI only
CSM Support -> No
