# Tiresias Boards

This repository contains the board files for the board used in the Tiresias Project.

## Tiresias DK

The complete design files for the **Tiresias Hearing Aid Development Board** (Tiresias DK) can be found on its [GitHub Repository](https://github.com/joaocolombari/Tiresias_HW).

### Antenna

| Connector |
| --------- |
| J1 |

### JST SH Connectors

| Connector | Pin 1 | Pin 2 |
| --------- | ----- | ----- |
| J2 | GND | VBAT |
| J3 | HPOUTP1 | HPOUTN1 |
| J4 | HPOUTN0 | HPOUTP0 |
| J5 | GND | VBUS |

### Test Points (TP)

| Test Point | Pin Name | Description |
| ---------- | -------- | ----------- |
| TP1  | NTC | Negative Temperature Coefficient thermistor input (battery temperature sensing) |
| TP2  | MIC0_OUT | Analog Microphone 0 Output |
| TP3  | MIC1_OUT | Analog Microphone 1 Output |
| TP4  | MICBIAS0 | Microphone 0 bias voltage output |
| TP5  | MICBIAS1 | Microphone 1 bias voltage output |
| TP6  | VBUS | Voltage Bus |
| TP7  | VDD_LED | LED supply voltage rail |
| TP8  | VBAT | Battery positive voltage |
| TP9  | VDD_PMIC_1V8_DIGITAL | 1.8 V digital supply from PMIC |
| TP10 | VDD_PMIC_0V9 | 0.9 V supply from PMIC |
| TP11 | BAT_MON_EN | Battery monitor enable control signal |
| TP12 | BAT_MON | Battery voltage monitor sense output |
| TP13 | FSYNC_0/MP0 | I²S Frame Sync 0 (multipurpose pin MP0) |
| TP14 | BLCK_0/MP1 | I²S Bit Clock 0 (multipurpose pin MP1) |
| TP15 | SDATAO_0 | Serial Audio Data Output 0 |
| TP16 | SDATAI_0/MP2 | Serial Audio Data Input 0 (multipurpose pin MP2) |
| TP17 | FSYNC_1/MP3 | I²S Frame Sync 1 (multipurpose pin MP3) |
| TP18 | BCLK_1/MP4 | I²S Bit Clock 1 (multipurpose pin MP4) |
| TP19 | SDATAI_1/MP6 | Serial Audio Data Input 1 (multipurpose pin MP6) |
| TP20 | SDATAO_1/MP5 | Serial Audio Data Output 1 (multipurpose pin MP5) |
| TP21 | CS# | Quas-SPI Chip Select (active low) |
| TP22 | SCLK | Quad-SPI Serial Clock |
| TP23 | SIO0 | Quad-SPI IO0 |
| TP24 | SIO1 | Quad-SPI IO1 |
| TP25 | SIO2 | Quad-SPI IO2 |
| TP26 | SIO3 | Quad-SPI IO3 |
| TP27 | SCL | I²C Serial Clock |
| TP28 | SDA | I²C Serial Data |
| TP29 | TRACEDATA3 | Debug Trace Data bit 3 |
| TP30 | TRACEDATA2 | Debug Trace Data bit 2 |
| TP31 | TRACEDATA1 | Debug Trace Data bit 1 |
| TP32 | TRACEDATA0 | Debug Trace Data bit 0 |
| TP33 | TRACECLK | Debug Trace Clock |
| TP34 | VDD_PMIC_1V8_ANALOG | 1.8 V analog supply from PMIC |
| TP35 | GND | Analog Ground |
| TP36 | GND | Analog Ground |
| TP37 | GND | Ground (selectable with SB5 / NTC reference return) |
| TP38 | AIN2 | Analog Input Channel 2 |
| TP39 | AIN3 | Analog Input Channel 3 |
| TP40 | DMIC23/MP10 | Digital Microphone Data input (DMIC2/3) / Multipurpose pin MP10 | 
| TP41 | DMIC_CLK1/MP8 | Digital Microphone Clock 1 output / Multipurpose pin MP8 |

### Solder Bridges (SB)

| Solder Bridge | Pins | Description |
| ------------- | ---- | ----------- |
| SB1  | VDD_LED - ISET | |
| SB2  | ISET - GND |
| SB3  | VDD_LED - MODE |
| SB4  | MODE - GND |
| SB5  | NTC - GND |
| SB6  |  |
| SB7  | IOVDD - GND |
| SB8  | REG_EN - AVDD |
| SB9  | REG_EN - GND |
| SB10 | GND - STANDBY |
| SB11 | OUTPUT - MCLKIN |
| SB12 | EXT_CLK - MCLKIN |
| SB13 | VSYS - CE |
| SB14 | VSYS - CE |
