# MechLlama-KiCad
KiCad Libraries for MechLlama projects

## Footprints
### `MechLlama.pretty`
- `Buzzer_SMD_KLJ-1102_11x9`: Buzzer footprint for Keliking KLJ-1102 low profile piezo buzzer.
- `D_SOD-123-DualSide`: KiCad D_SOD-123 Footprint modified with vias and double sided pads to allow installation on either side of board.
- `LED_WS-2812B-Mini_Cutout`: Worldsemi WS-2812B-Mini footprint with edge cuts and reversed pads. For placement under key switches.
- `LED_WS-2812B-Mini`: Worldsemi WS-2812B-Mini footprint for surface mount placement.
- `LED_Wurth_150141M173100_Cutout`: Wurth WL-SFTW SMT Full-color LED with edge cuts and reversed pads. For placement under key switches.
- `LED_Wurth_150141M173100`: Wurth WL-SFTW SMT Full-color LED for surface mount placement.
- `MountingHole_4.5mm_SpacerThrough`: Hole for M2 spacers.
- `PinHeader_1x05_P2.54mm_Vertical_STM32_SWD_Debug_Header`: 1 row pin header for STM32 debugger.
- `PinHeader_1x06_P2.54mm_Vertical_ISP`: 1 row pin header for ISP programmer. Silkscreen on both sides.
- `PinHeader_2x03_P2.54mm_Vertical_ISP`: 2 row pin header for ISP programmer.
- `PinHeader_SSD1306`: Pin header for SSD1306 OLED screen. Includes Dwgs.User layer of PCB and screen location.
- `PinHeader_SSD1306_NoLCD`: Pin header for SSD1306 OLED screen.
- `SOT-143B`: Footprint for SOT-143B package. Pads are as small as possible to allow for nicer trace routing.
- `TestPoint_Keystone_5000-5004_Miniature-DualSide.kicad_mod`: Test point with dual sided silkscreen markings.

## Symbols
### `MechLlama.lib`
- `OLED_SSD1306`: SSD1306 clone 4-pin
- `PCA9675PW`: Remote 16-bit I/O Expander for Fm+ I2C-bus with interrupt.
- `STM32_SWD`: Debug header for stm32 SWD
- `STM32_SWD`: Debug header for stm32 SWD with no SWO pin
- `SW_Push_PinReverse`: KiCad SW_Push_Pin schematic reversed to nicer schematic layout in Eeschema.
- `TCA9617A/PCA9617A`: TI FM+ i2c bus repeater.
- `TPD2E1B06`: Dual-Channel Bidirectional High-Speed ESD Protection
