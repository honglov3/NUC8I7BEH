# NUC8I7BEH Hackintosh Opencore 0.5.9 UEFI

![about os](https://user-images.githubusercontent.com/31032428/83754831-3193c480-a69f-11ea-9c4b-0c18c1ac71a0.png)

* boot with OpenCore GUI
* can dual-boot with **Windows 10** on another seperate m2.ssd 
* remember pull out **Windows 10** ssd/harddisk before start to install Hackintosh on another ssd
* place **Windows Boot Manager** under Hackintosh disk on the BIOS UEFI startup

Intel Wifi kext, Max Download Speed 30mbps
 - credit to: PC Video / Games Channel
 - link to this video
 https://www.youtube.com/watch?v=kHfUjJ2RkyU
 
works but ...
 * line-in mic (sound bit loose)
 
not yet test
 * thunderbolt 3 port
 * micro-sd slot
 
specs
  * OS: macOS Catalina 10.15.5/Macmini8,1
  * CPU: Intel® Core™ i7-8559U Processor (8M Cache, up to 4.50 GHz)
  * SSD: 960GB KINGSTON A400 2.5 SATA
  * RAM: 16GB X 2 HYPERX DDR4 2400
  * BIOS: 0078
  * MONITOR: LG29WK600
  
bootloader
  * Opencore 0.5.9
  * Opencore 0.5.7
 
how to install
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
  * https://www.jianshu.com/p/78510cfa4a64
  
**IntelBluetoothFirmware**
  * https://github.com/zxystd/IntelBluetoothFirmware/releases/
  
**AppleALC_CodecGuide**
  * https://github.com/acidanthera/AppleALC/wiki/Supported-codecs
