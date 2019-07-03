# MechLlama-KiCad
KiCad Libraries for MechLlama projects

## Footprints
### `MechLlama.pretty`
- `Buzzer_SMD_KLJ-1102_11x9`: Buzzer footprint for Keliking KLJ-1102 low profile piezo buzzer.
- `D_SOD-123_Nice`: KiCad D_SOD-123 footprint with diode symbol between pads.
- `LED_WS-2812B-Mini_Cutout`: Worldsemi WS-2812B-Mini footprint with edge cuts and reversed pads. For placement under key switches.
- `LED_WS-2812B-Mini`: Worldsemi WS-2812B-Mini footprint for surface mount placement.
- `MountingHole_4.5mm_SpacerThrough`: Hole for M2 spacers.
- `PinHeader_1x06_P2.54mm_Vertical_ISP`: 1 row pin header for ISP programmer. Silkscreen on both sides.
- `PinHeader_2x03_P2.54mm_Vertical_ISP`: 2 row pin header for ISP programmer.
- `PinHeader_SSD1306`: Pin header for SSD1306 OLED screen. Includes Dwgs.User layer of PCB and screen location.
- `PinHeader_SSD1306_NoLCD`: Pin header for SSD1306 OLED screen.
- `SOT-143B`: Footprint for SOT-143B package. Pads are as small as possible to allow for nicer trace routing.
- `Tag-Connect_TC2030-IDC-NL_2x03_P1.27mm_Vertical`: KiCad Tag Connect ISP header pads with connector outline on silkscreen.
- `USB_C_Receptacle_HRO_TYPE-C-31-M-12`: Korean Hroparts Elec TYPE-C-31-M-12 footprint with correct KiCad pad names. Use with `USB_C_Receptacle_USB2.0-ReducedPins` schematic.

## Symbols
### `MechLlama.lib`
- `USB_C_Receptacle_USB2.0-ReducedPins`: KiCad USBC2.0 schematic with overlapping pins removed.
- `SW_Push_PinReverse`: KiCad SW_Push_Pin schematic reversed to nicer schematic layout in Eeschema.
