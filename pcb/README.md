# DSMR Splitter

## Pictures
[<img src="Pictures/TopView.png" width="256" alt="Top view 3D render.">](Pictures/TopView.png)
[<img src="Pictures/BottomView.png" width="256" alt="Bottom view 3D render.">](Pictures/BottomView.png)

## Schema
You can find the schema [here](DSMR-Splitter.pdf).

## BOM
| Ref | Value         | Footprint                                                  | Farnell | DigiKey        | Mouser         | Notes |
|-----|---------------|------------------------------------------------------------|---------|----------------|----------------|-------|
| C1  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C2  | CP            | Capacitor_Tantalum_SMD:CP_EIA-3216-12_Kemet-S              |         |                |                |       |
| C3  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C4  | CP            | Capacitor_Tantalum_SMD:CP_EIA-3216-12_Kemet-S              |         |                |                |       |
| C5  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C6  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C7  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C8  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C9  | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C10 | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C11 | 20pF          | Capacitor_SMD:C_0603_1608Metric                            | 2627461 |                |                |       |
| C12 | 20pF          | Capacitor_SMD:C_0603_1608Metric                            | 2627461 |                |                |       |
| C13 | 1µF           | Capacitor_SMD:C_0603_1608Metric                            |         |                |                |       |
| C14 | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C15 | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| C16 | 100nF         | Capacitor_SMD:C_0603_1608Metric                            | 1833843 |                |                |       |
| D1  | LED           | LED_SMD:LED_0603_1608Metric                                |         |                |                |       |
| D2  | 1N4148        | Diode_SMD:D_0603_1608Metric                                |         |                |                |       |
| D3  | 1N4148        | Diode_SMD:D_0603_1608Metric                                |         |                |                |       |
| J1  | JTAG          | Connector_PinHeader_1.27mm:PinHeader_2x03_P1.27mm_Vertical |         |                |                |       |
| J2  | UART          | Connector_PinHeader_1.27mm:PinHeader_1x04_P1.27mm_Vertical |         |                |                |       |
| J3  | IN            | Connector_RJ:RJ12_Amphenol_54601                           | 2135977 |                |                |       |
| J4  | OUT-A         | Connector_RJ:RJ12_Amphenol_54601                           | 2135977 |                |                |       |
| J5  | OUT-B         | Connector_RJ:RJ12_Amphenol_54601                           | 2135977 |                |                |       |
| J6  | OUT-C         | Connector_RJ:RJ12_Amphenol_54601                           | 2135977 |                |                |       |
| R1  | 100           | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R2  | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R3  | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R4  | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R5  | 2k2           | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R6  | 100k          | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R7  | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R8  | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R9  | 2k2           | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R10 | 100k          | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R11 | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R12 | 1k            | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R13 | 2k2           | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| R14 | 100k          | Resistor_SMD:R_0603_1608Metric                             |         |                |                |       |
| U1  | EFM32PG12B500 | Package_DFN_QFN:QFN-48-1EP_7x7mm_P0.5mm_EP5.3x5.3mm        |         | 336-3941-ND    |                |       |
| U2  | TPS76933      | Package_TO_SOT_SMD:SOT-23-5                                | 3122539 |                |                |       |
| U3  | 74AHC1G126    | Package_TO_SOT_SMD:SOT-23-5                                | 3119379 |                |                |       |
| U4  | 74AHCT1G04    | Package_TO_SOT_SMD:SOT-23-5                                | 2057387 |                |                |       |
| U5  | 74AHCT1G04    | Package_TO_SOT_SMD:SOT-23-5                                | 2057387 |                |                |       |
| U6  | VOH1016AG-V   | Package_DIP:SMDIP-6_W7.62mm                                |         |                | 78-VOH1016AB-T |       |
| U7  | VOH1016AG-V   | Package_DIP:SMDIP-6_W7.62mm                                |         |                | 78-VOH1016AB-T |       |
| U8  | 74AHCT1G04    | Package_TO_SOT_SMD:SOT-23-5                                | 2057387 |                |                |       |
| U9  | VOH1016AG-V   | Package_DIP:SMDIP-6_W7.62mm                                |         |                | 78-VOH1016AB-T |       |
| U10 | VOH1016AG-V   | Package_DIP:SMDIP-6_W7.62mm                                |         |                | 78-VOH1016AB-T |       |
| U11 | 74AHCT1G04    | Package_TO_SOT_SMD:SOT-23-5                                | 2057387 |                |                |       |
| U12 | VOH1016AG-V   | Package_DIP:SMDIP-6_W7.62mm                                |         |                | 78-VOH1016AB-T |       |
| U13 | VOH1016AG-V   | Package_DIP:SMDIP-6_W7.62mm                                |         |                | 78-VOH1016AB-T |       |
| Y1  | 40MHz         | Crystal:Crystal_SMD_2016-4Pin_2.0x1.6mm                    |         | 1253-1120-1-ND |                |       |
