# azure_iot_getstarted_python
Read data from a BME280 environmental sensor and write to Azure IoT Hub.

This code is a combination of bme280.py written by Matt Hawkins to read data from the BME280 sensor via the I2C bus and SimulatedDevice.py provided by Microsoft to connect to a device-specific MQTT endpoint on your IoT Hub.

https://www.raspberrypi-spy.co.uk/2016/07/using-bme280-i2c-temperature-pressure-sensor-in-python/

https://bitbucket.org/MattHawkinsUK/rpispy-misc/raw/master/python/bme280.py

https://github.com/Azure-Samples/azure-iot-samples-python/

IoT Hub requires the following:

  pip install azure-iothub-device-client
  
  sudo apt-get install libboost-all-dev
