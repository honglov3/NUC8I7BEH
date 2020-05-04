# NUC8I7BEH Hackintosh Opencore 0.5.7 UEFI

![About_Mac](https://user-images.githubusercontent.com/31032428/80986699-84d9e380-8e63-11ea-934c-6ad4d18866d2.png)

* can dual-boot with **Windows 10** on another seperate m2.ssd 
* remember pull out **Windows 10** ssd/harddisk before start to install Hackintosh on another ssd
* place **Windows Boot Manager** under Hackintosh disk on the BIOS UEFI startup

won't works
 * Intel Wifi
 
works but ...
 * line-in mic (sound bit loose)
 
not yet test
 * thunderbolt 3 port
 * micro-sd slot
 
specs
  * OS: macOS Catalina 10.15.4/Macmini8,1
  * CPU: Intel® Core™ i7-8559U Processor (8M Cache, up to 4.50 GHz)
  * SSD: 960GB KINGSTON A400 2.5 SATA
  * RAM: 16GB X 2 HYPERX DDR4 2400
  * BIOS: 0078
  * MONITOR: LG29WK600
  
bootloader
  * Opencore 0.5.7
 
how to install
 * DIsable **Vt-d** on the BIOS
  * Disable **Legacy Boot** on the BIOS
  * Create bootable USB with macOS Catalina (Windows or Mac)
  * Copy OC/0.5.7/EFI to your BOOT folder
  * Change your mac serial number in OC/**config.plist**
  
tips
  * use ProperTree and GenSMBIOS files to change your mac serial number
  * can use Clover Configurations application to mount the harddisk
  
credits

**Youtube Video**
  * https://www.youtube.com/watch?v=p3epD8qqVeA&t=1367s
  * https://www.youtube.com/watch?v=6KGuINOyHh0&t=1137s
  
**Article**
  * https://dortania.github.io/OpenCore-Desktop-Guide/
  * https://github.com/csrutil/NUC8I5BEH
  * https://www.jianshu.com/p/b298da6afef3
  
**IntelBluetoothFirmware**
  * https://github.com/zxystd/IntelBluetoothFirmware/releases/
  
**AppleALC_CodecGuide**
  * https://github.com/acidanthera/AppleALC/wiki/Supported-codecs
