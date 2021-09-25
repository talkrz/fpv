# Remap Tx1 in order to use Crossfire receiver with Diatone GTB-229 drone

## Default resource settings

```
# resource
resource BEEPER 1 B02
resource MOTOR 1 B03
resource MOTOR 2 B04
resource MOTOR 3 B06
resource MOTOR 4 B07
resource PPM 1 B09
resource LED_STRIP 1 A08
resource SERIAL_TX 1 A09
resource SERIAL_TX 2 A02
resource SERIAL_RX 1 A10
resource SERIAL_RX 2 A03
resource INVERTER 1 B10
resource LED 1 C13
resource LED 2 C14
resource SPI_SCK 1 A05
resource SPI_SCK 2 B13
resource SPI_MISO 1 A06
resource SPI_MISO 2 B14
resource SPI_MOSI 1 A07
resource SPI_MOSI 2 B15
resource ESCSERIAL 1 B09
resource CAMERA_CONTROL 1 B05
resource ADC_BATT 1 A00
resource ADC_RSSI 1 B01
resource ADC_CURR 1 A01
resource OSD_CS 1 B12
resource SPI_PREINIT_IPU 1 A04
resource SPI_PREINIT_IPU 2 B12
```

# Remap PPM pin to serial Tx1

```
# remap
resource PPM 1 NONE
resource ESCSERIAL 1 NONE
resource SERIAL_TX 1 B09
Save
```