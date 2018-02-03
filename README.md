DC brushed motor speed control with stable RPM
==============================================

__WORK IN PROGRESS !!!__

> Advanced speed control for DC 48v-220v brushed motor. With RPM stabilization
> via Back EMF measure. Replacement for default board.

Useful when:

- You need very compact device to control 48-220V & 200-1000W brused DC motor
  from AC power source. Such motors can be found in small CNC spindles, blenders
  and so on.
- You need stable RPM on varied rotor load - in small drills, saws and other
  devices.

2 versions available:

- Mini. Without galvanic isolation. With just single wheel to change motor speed.
- Full. With galvanic isolation, optional OLED display, buttons and external
  CNC controller interface.


How to build
------------


### Components

1. Go to [mini](https://easyeda.com/speed/DC_motor_speed_control_mini-d948481ca44946ff954814c61bb46eaf) or [full](https://easyeda.com/speed/DC_Motor_speed_control-519b34b17950473d802eea899ae2dcdd) driver page at EasyEda.
    - Order PCB
    - Order details from BOM. We already prepeared links to LCSC for your
      convenience. It's not the cheapest in the wold, but good enougth and you
      may find useful to buy all details in one place.
2. Get additional details, not included into BOM:
    - [Cheap stlink programmer](https://www.aliexpress.com/af/stlink-stm32.html?jump=afs)
      for stm32 devices (only 2$).
    - Terminal blocks
      - 9.5mm HB-9500 4 pin (optional, with top cover, if you
        don't like one from BOM)
      - 2.5mm [2 pin](https://www.aliexpress.com/item/10pcs-2-Poles-2-Pin-2-54mm-PCB-Universal-Screw-Terminal-Block-Connector/32774484674.html) and [3 pin](https://www.aliexpress.com/item/10pcs-3-Poles-3-Pin-2-54mm-PCB-Universal-Screw-Terminal-Block-Connector/32776711319.html). Or alternative [2 pin](https://www.aliexpress.com/item/10Pcs-KF141R-2P-2-Pin-2-54mm-Pitch-Pcb-Connector-Spring-Screless-Terminal-Block/32711499898.html) and [3 pin](https://www.aliexpress.com/item/20PCS-Lot-141R-2-54-3P-3Pin-PCB-Spring-Terminal-Block-ROHS-connector-Pitch-2-54mm/32603606570.html). For full version
        only. Mini has 3.5mm terminals.
    - [Silicone insulation film](https://www.aliexpress.com/item/Free-shipping-200pcs-The-TO-3-p-insulation-pad-silicone-heat-sink-The-silicone-insulation-film/2044809128.html)
      for TO-247, if you need MOSFET heatsink for > 2A RMS current (500W load
      at 220v).
    - Better [fuse holder](https://www.aliexpress.com/item/Panel-Mount-PCB-Fuse-Holder-Case-w-Cover-5x20mm-Free-Shipping/32801396605.html) and [fuse](https://www.aliexpress.com/store/product/Promotion-100Pcs-Set-5x20mm-Quick-Blow-Glass-Tube-Fuse-Assorted-Kits-Fast-blow-Glass-Fuses/2949063_32813385139.html).
    - [Potentiometer with insulated shaft](https://ru.aliexpress.com/item/2PCS-LOT-Imported-American-PTD902-precision-potentiometer-double-C20K-insulated-shaft-long-15MM-volume-potentiometer/32830882837.html). For mini version only.
    - Any 2K-10K potentiometer for full version. Or 2 buttons (-/+).
    - [I2C OLED display](https://www.aliexpress.com/item/1PCS-1-3-OLED-module-white-color-128X64-1-3-inch-OLED-LCD-LED-Display-Module/32683094040.html)
      and [headers](https://lcsc.com/product-detail/Female-Header_Female-header-1-4P-2-54mm-Straight-line_C124413.html).
      For full version only. Optional. Other i2c 128x64 displays with 4-wire
      connectors and 3.3v power will be ok too.
    - [Jumpers](https://lcsc.com/product-detail/Shunts-Jumpers_Short-hood2-54mm-Top-seal-Closed-type_C100114.html)
    - Alternate shunt and amplifier resistors
      - TBD
    - [TSP-12](https://www.aliexpress.com/item/TSP-12-replace-HLK-PM12-AC-DC-220V-to-12V-Buck-Step-Down-Power-Supply-Module/32596516492.html)
    - [TSP-05](https://www.aliexpress.com/item/TSP-05-replace-HLK-PM01-AC-DC-220V-to-5V-mini-power-supply-module-intelligent-household/32705471039.html), for full version only.


### Assembly

TBD
