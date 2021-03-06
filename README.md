# iot2018

Arduino-programs for module Internet of Things - version 2018

The following programs are intended for ESP8266 (especially Wemos D1 mini,
with sensor board):

* wifi-node-xd
* sensor-webserver-0
* mqtt-node-0
* rfm69-gateway-0

The wifi-node-xd program is the most general, it contains:

* i2c display control (displays configuration, sensor values)
* WiFi-configuration of WiFI- and MQTT settings
* MQTT client and webserver to control actuators and sensors

The following programs are intended for Arduino (Pro Mini, or UNO):

* rfm69-mini-client-2
* ttn_bmp280_mini_node_0

The following local libraries can be used in both ESP8266- and Arduino-based systems:

* rf69min.h
* jsonlpp.h

The following libraries are used in these programs:

* Adafruit BME280, BMP280
* `lmic.h`: TTN/LoRaWan client library, see: https://github.com/matthijskooijman/arduino-lmic
* `LowPower.h`: https://github.com/rocketscream/Low-Power
* `i2c_BMP280.h`: I2C-Sensor-Lib (Ingmar Splitt)
* LittleFS: Flash file system (ESP8266)
* ArduinoJon
* PubSubClient: MQTT client software
