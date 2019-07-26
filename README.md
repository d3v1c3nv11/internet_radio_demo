# Play HTTP aac Living stream

The demo plays a m3u downloaded from HTTP. 

## Compatibility

ESP32-ADF
https://www.olimex.com/Products/IoT/ESP32/ESP32-ADF/open-source-hardware

## Usage

Prepare the audio board:

- Connect speakers or headphones to the board.

# Get ESP-ADF
```bash
cd ~/
git clone --recursive https://github.com/espressif/esp-adf.git
cd esp-adf
git submodule update --init
export ADF_PATH=~/esp-adf
```
Configure the example:

- Set up the Wi-Fi connection by running `menuconfig` > `Example Configuration` and filling in `WiFi SSID` and `WiFi Password`.

Load and run the example:
```bash
git clone https://github.com/d3v1c3nv11/internet_radio_demo.git
cd internet_radio_demo
make menuconfig
make flash monitor
```
- The audio board will first connect to the Wi-Fi.
- Then the board will start playing automatically.
```bash
Use Touch buttons:
Volume: Vol- Vol+
Next station: <Play>
Presset station: <Set>
```


