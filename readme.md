# Open Media System

## Modules

### Main Controller

OS, controlling all other modules. Suggestions:
 * **Toradex**
   * [Carrier board: Ixora V1.0A](https://www.toradex.com/products/carrier-boards/ixora-carrier-board), 89,00€
     * 125 x 90 mm
     * 1x Ethernet 10/100/1000 Mbit, 2x USB 3.0 Host
     * 1x mSATA, 1x mini PCIe
     * 1x S/PDIF In / Out
     * 1x HDMI, 1x RGB
     * 1x Micro SD (4 Bit)
     * **BEWARE:** No Wi-Fi
     * Power: Max. 5V / 5A (25W) or 3.3V / 5A (16.5W)
       * The connector X2, which is a standard 5.5mm power jack barrel connector which is widely used in consumer electronic devices.
       * The connector X3, which is a pluggable, dual-pin male screw type Phoenix terminal block which is widely used in industrial applications. This connector is not assembled by default.
     * Micro SIM
   * [SoM: Apalis T30 2GB - V1.0E, NVIDIA Tegra 3](https://www.toradex.com/computer-on-modules/apalis-arm-family/nvidia-tegra-3), 146,00€
     * ARM Cortex™-A9, Quad Core, 1.4 GHz
     * RAM 2GB DDR3L @ 1600MT/s (32 Bit), Flash 8GB eMMC (8 Bit)
     * PCIe (Gen 1.0) 5 Lane (1x1 + 1x4)
     * Integrated Ultra-low power NVIDIA GeForce GPU
     * HDMI V1.4a 1080p (1920x1080), DiVX 4/5/6, H.263, H.264, JPEG, MPEG-2, MPEG-4, WMV9 VC-1, XviD
   * [SoM alternative: Apalis iMX6 Quad 2GB IT - V1.1A, Freescale® i.MX 6Q](https://www.toradex.com/computer-on-modules/apalis-arm-family/freescale-imx-6), 124,00€
     * industrial -40° to 85° C
     * Freescale i.MX6 ARM Cortex™-A9, Quad Core, 800 MHz
     * RAM 2GB DDR3 @ 1066MT/s (64 Bit), Flash 4GB eMMC (8 Bit)
     * PCIe (Gen 2.0) 1 Lane
     * Vivante GC2000
     * V1.4a 1080p (1920x1080), DivX 3/4/5/6, H.263, H.264, MJPEG, MPEG-2, MPEG4, VC1
   * Apalis Heatsink Type 2 V1.0A, 11,00€
     * **BEWARE:** Does V1.0A imply it only works with the Apalis T30 1GB V1.0A and **not** the Apalis T30 2GB V1.0E
   * Carrier Board Accessory Kit V1.0A, 25,00€
     * Cables: USB, Ethernet, RS232, Jumper Wires
     * Adapters: DVI to VGA, DVI to HDMI, USB to RS232, USB Micro-A to A (USB Micro-AB receptacle to Type A), RS232 Header to D-Sub, Iris Power-adapter
     * Power Adapter: 12VDC 30W with international plugs
   * Apalis T30 Mezzanine V1.1A, x16 (x4 mode) PCI Express slot, 32,00€
     * Alternative to mini PCIe to PCI adapter?
     * **BEWARE:** Does V1.1A imply it only works with the development carrier board and **not** the Ixora? 

 * **Keith & Koep** TODO
   * [Base board: pConXS FF](http://www.keith-koep.com/en/products/pconxs-ff/)
     * PCIe
     * 4x USB 2.0
   * [SoM: Trizeps VII](http://www.keith-koep.com/en/products/trizeps7-i.MX6/)
     * Freescale i.MX6 ARM Cortex™-A9, Quad, 1 GHz
     * RAM 1GB DDR3 (64 Bit)
 
 * **Boundary Devices**
   * [SoC: Nitrogen6_MAX](http://boundarydevices.com/product/nitrogen6max/), 249,00$
     * Freescale i.MX6 ARM Cortex™-A9, Quad Core, 1 GHz
     * RAM 4GB DDR3 @ 532MHz (64 Bit), Flash 4GB eMMC
     * 1x Ethernet 10/100/1000 Mbit, 3x USB
     * 1x mini PCIe, SATA
     * 1x HDMI
     * 1x Micro SD
     * Wi-Fi 802.11b/g/n/Bluetooth
     * Includes 5V power adapter, 4GB Micro SD, Serial console cable
   * [mini PCIe to PCIe Converter board](http://boundarydevices.com/product/mpcie-to-pci-e-db/), 50,00$
 
 * **Solid Run**, All together 170,00€:
   * [Carrier board: HummingBoard Carrier Pro](http://www.solid-run.com/product/hummingboard-carrier-pro/)
     * Raspberry Pi size
     * 1x Ethernet 10/100/1000 Mbit, 2x USB 2.0
     * 1x mSATA II, 1x mini PCIe (half sized)
     * 1x S/PDIF In / Out
     * 1x HDMI 1080p with CEC
     * 1x Micro SD
     * Wi-Fi 802.11n/Bluetooth
     * Infra red receiver
   * [SoM: MicroSOM-i4Pro](http://www.solid-run.com/product/hummingboard-carrier-pro/)
     * Freescale i.MX6 ARM Cortex™-A9, Quad, 1 GHz
     * RAM 2GB DDR3 (64 Bit)
   * AC power adapter, 10,00€

 * [Amfeltec Flexible mini PCIe 2.0 to 2x PCIe 2.1 Splitter](http://amfeltec.com/products/flexible-minipci-express-to-2-x1-pci-express-splitter/)
   * Power from either:
     * Standard ATX power supply (“floppy disk” connector, 12 and 5 volts) via x1 PCIe adapter board
     * Any external 12V power supply via x1 PCIe adapter board

 * [Amfeltec Flexible mini PCIe 2.0 to PCIe Adapter (SKU-035)](http://amfeltec.com/products/flexible-minipci-express-to-pci-express-adapter/)
   * mini PCIe 2.0 full or half size
   * Power from either:
     * mini PCIe Host card (3.3 volt only) via power cable and x1 PCIe adapter board (maximum peak current 2.75A, maximum normal current 1.1A)
       * **BEWARE:** Not sufficient for Asus Xonar STX!
     * Standard ATX power supply (“floppy disk” connector, 12 and 5 volts) via x1 PCIe adapter board
     * Any external 12V power supply via x1 PCIe Adapter board

### Audio

Audio amplifier, decoder & interface.

 * [Asus Xonar STX](http://www.asus.com/Essence_HiFi_Audio/Xonar_Essence_STX/overview/), 160,00€
   * PCIe 1.0, compatible with x1, x4, x8 or x16 slots
   * **BEWARE:** Requires additional 4-pin power supply
