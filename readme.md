# macOS Ventura

**Boot args:** alcid=1 -wegnoegpu

**System Audio Volume:** 50 (0x32)

**Keyboard:** en_GB:250

* **Debug Config Changes:**
    * **NVRAM > Add > 7C436110-AB2A-4BBB-A880-FE41995C9F82 > boot-args:**
        * **From:** alcid=1 -wegnoegpu
        * **To:** -v keepsyms=1 debug=0x100 alcid=1 -wegnoegpu
    * **MISC > Boot > ShowPicker**
        * **From:** False
        * **To:** True
    * **MISC > Debug > AppleDebug**
        * **From:** False
        * **To:** True
    * **MISC > Debug > ApplePanic**
        * **From:** False
        * **To:** True
    * **MISC > Debug > Target**
        * **From:** 0
        * **To:** 67

* **System specs:**
    * **Motherboard:** [Gigabyte Z370P D3](https://www.gigabyte.com/Motherboard/Z370P-D3-rev-10)
    * **CPU:** [Intel Core i5-9500K OC'd 4.8GHz](https://www.intel.com/content/www/us/en/products/sku/134896/intel-core-i59600k-processor-9m-cache-up-to-4-60-ghz/specifications.html)
    * **RAM:** [x2 White Corsair Vengeance 8GB 3000MHz OC'd 3200MHz](https://www.corsair.com/uk/en/p/memory/cmk16gx4m2b3000c15w/vengeancea-lpx-16gb-2-x-8gb-ddr4-dram-3000mhz-c15-memory-kit-white-cmk16gx4m2b3000c15w)
    * **GPU:** [MSI GTX 1660 VENTUS XS 6GB OC](https://www.msi.com/Graphics-Card/GeForce-GTX-1660-VENTUS-XS-6G-OC)
    * **WiFi Card:** [Intel Dual Band Wireless-AC 7275](https://www.intel.com/content/www/us/en/products/sku/83635/intel-dual-band-wirelessac-7265/downloads.html)
    * **USB Cards:**
        * [SupaHub USB Card x4 Type A, x1 Type C (unsupported with MacOS)](https://amzn.eu/d/gim95Xe)
        * [highka USB Card x5 Type A, x2 Type C (supported with MacOS)](https://www.aliexpress.com/item/1005004603466760.html)
    * **Drives:**
        * [Crucial P5 Plus 500GB M.2](https://uk.crucial.com/ssd/p5-plus/ct500p5pssd8)
        * [Kingston A400 240GB](https://www.kingston.com/unitedkingdom/en/ssd/a400-solid-state-drive)
        * [WD Blue 1TB (unplugged)](https://www.westerndigital.com/en-gb/products/internal-drives/wd-blue-desktop-sata-hdd)

* **SSDTs:**
    * [SSDT-AWAC](https://dortania.github.io/Getting-Started-With-ACPI/Universal/awac.html)
    * [SSDT-EC-USBX](https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html)
    * [SSDT-PLUG](https://dortania.github.io/Getting-Started-With-ACPI/Universal/plug.html)

* **Drivers:**
    * [HfsPlus](https://github.com/acidanthera/OpenCorePkg/releases)
    * [OpenRuntime](https://github.com/acidanthera/OpenCorePkg/releases)
    * [ResetNvramEntry](https://github.com/acidanthera/OpenCorePkg/releases)

* **Kexts:**
    * [AirportItlwm](https://github.com/OpenIntelWireless/itlwm/releases)
    * [AppleALC](https://github.com/acidanthera/AppleALC/releases)
    * [Lilu](https://github.com/acidanthera/Lilu/releases)
    * [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases)
    * [SMCProcessor](https://github.com/acidanthera/VirtualSMC/releases)
    * [SMCSuperIO](https://github.com/acidanthera/VirtualSMC/releases)
    * [VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases)
    * [VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2/releases)
    * [WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases)
    * [USBToolbox](https://github.com/USBToolBox/kext)