DevaamoMuHalf V1.20 BOM
=======================

Bill of materials

R1, R2  0603 2k15 (or 2k2) I2C 3.3V pullups. I usually use 2k15 from E96 series.

R3      0603 330 ohms or something like that for led series resistor

C1, C2  0603 1µF 16V X7R

H1      0603 Led of your favorite colour (for blue or white, change R3)

N1      MCP1700-1802E (Microchip) in SOT23 1.8V Regulator

D1      PCA9517DGKR (TI) in MSOP8 (or PCA9517DP (NXP) in TSSOP-8) I2C Level translator
        http://www.nxp.com/documents/data_sheet/PCA9517.pdf
        
D3      AT24C02D-STUM-T (Atmel) in SOT23-5 I2C EEPROM 2kbit
        http://www.atmel.com/Images/Atmel-8871-SEEPROM-AT24C01D-02D-Datasheet.pdf
        
X1      2.54mm (0.1") pinheader 10 pins, or just solder wires
