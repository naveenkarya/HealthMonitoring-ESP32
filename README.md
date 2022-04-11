# HealthMonitoring-ESP32

### Health sensors used
| Sensor        | Function           |
| ------------- |:-------------|
| MAX30102      | SPO2 and BPM |
| DS18B20      | Body Temperature     |
| AD8232      | ECG      |
| MPU-6050      | Accelerometer & Gyroscope      |
| DHT11      | Environment humidity and temperature      |

### References
1. https://github.com/me-no-dev/ESPAsyncWebServer - "simple_server" example
1. https://github.com/milesburton/Arduino-Temperature-Control-Library - "Simple" example
1. https://github.com/adafruit/DHT-sensor-library - "DHTTester" example
1. https://github.com/sparkfun/SparkFun_MAX3010x_Sensor_Library - "Example8_SPO2" example
1. https://github.com/adafruit/Adafruit_MPU6050 - "basic_readings" example

### Setup
Populate SENSOR_DATA_URL and FALL_DETAILS_URL with your application's POST APIs which will accept sensor readings in JSON format
After uploading the code, select your ESP32's WiFi Access point, then browse 192.168.4.1, and then select WiFi.
Once your ESP32 is connected to WiFi, touch and hold the Touch3 sensor for 5 seconds to begin reading sensor values.
