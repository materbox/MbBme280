# MbBme280 Sending telemetry to thingsboard server

## Devices
| Supported Devices |
|-------------------|
|  ESP8266          |

## Libraries needed
[WiFiManager.h](https://github.com/tzapu/WiFiManager)
[LittleFS.h](https://github.com/esp8266/Arduino/tree/master/libraries/LittleFS)
[Thingsboard](https://github.com/thingsboard/thingsboard-client-sdk)
[ESP_DoubleResetDetector.h](https://github.com/khoih-prog/ESP_DoubleResetDetector)
[time.h]
[stdio.h]
[FS.h]

## Feature
Send telemetry from a bme280 sensor to thingsboard server. Values sent are (temperature, humidity)
WifiManager manages wifi connection
DoubleReset manages reconfig in case we need to change device data configuration.
