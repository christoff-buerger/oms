# Open Media System

## Modules

### Main Controller

UDOO x86 Ultra (120 mm x 85 mm):
 * Fanless
 * Intel Curie Microcontroller
   * Bluetooth low energy
   * Arduino 101-compatible (3.3 V compliant)
   * 6-axis combo sensor (accelerometer, gyroscope, UDOO Bricks connector)
 * Intel Pentium N3710 (Intel Braswell)
   * 1.6-2.56 GHz, 2 MB L2 cache, 64 bit, 4 cores
   * Intel HD Graphics 405 (400-700 MHz, 16 execution units, max 3 displays)
 * Memory:
   * 8 Gb DDR3 Dual Channel
 * Mass storage:
   * 32 GB eMMC
   * 1x Micro SD card slot
   * 1x SATA
   * 1x M.2 Key B, 2242/2260 mm (SSD/PCIe module)
 * USB interfaces:
   * 3x USB 3.0 type A
 * Network interfaces:
   * 1x Gigabit Ethernet LAN
   * 1x M.2 Key E (wireless module)
 * Video Interfaces:
   * 1x HDMI (CEC)
   * 2x mini DisplayPort++

### Audio

Audio amplifier, decoder & interface:

 * [Asus Xonar STX](http://www.asus.com/Essence_HiFi_Audio/Xonar_Essence_STX/overview/), 160,00€
   * PCIe 1.0, compatible with x1, x4, x8 or x16 slots
   * **BEWARE:** Requires additional 4-pin power supply

### Power and connections

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
