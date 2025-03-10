# ESP-IDF SPP GATT CLIENT/Server demo

ble_spp test interface for server & client in seperate instances. Two Demos, a server & client that connect and exchange data wirelessly with each other, using a BLE SPP

- With UART interfaces exposed on each side to establish a serial connection

## Config

- server: WROVER-Kit	(ESP32 - COM6 UART)

	@url	 https://github.com/ErisdarDemo/esp32_spp_server 'r0'

- client: Waveshare 	(ESP32-S3 - COM4 JTAG)	

	@url	 https://github.com/ErisdarDemo/esp32_spp_client 'r0'

## Procedure

@pre Boards unplugged, LabVIEW closed
	
- Connect boards & validate COM ports

- Open both test interfaces
	
- ... demo away! A seperate copy of this test application can be hosted in each firmware project (ref - .gitignore)

## Development Opens

- Get Client UART Rx working (debug with LabVIEW? Why is it not catching the PuTTy tx?)

- Get both serial streams open & working

- Some sort of pause (button-init?)or reset (serial-cmd?) to synchronize demo with apps?

### Example Performance

- x

