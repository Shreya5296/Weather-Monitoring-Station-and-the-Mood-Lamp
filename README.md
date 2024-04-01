# Weather-Monitoring-Station-and-the-Mood-Lamp

1. Take the following required components from the kit.
● 1 x Breadboard
● 1 x RGB LED
● 1 X DHT11 sensor
● 1 x 330-ohm resistor
● 1 x ESP32
● 1 x USB Programming Cable
● 13 x Male to Male Jumper wires

2. Insert the DHT11 sensor, RGB LED, resistor and the ESP32 in the breadboard.
   
3. Connect the DHT sensor and RGB LED with ESP32 using male to male jumper wire. By doing this step, your hardware connections are ready.
   
4. write appropriate code, so that you can :
a) Fetch temperature and humidity values from the DHT sensor.
b) Convert the temperature values into fahrenheit and kelvin scale.
c) Calculate the Dew point using the temperature and humidity values.

5. After writing the appropriate code, log on to io.adafruit.com to design the cloud server.
   
6. Create feeds for temperature in celsius scale, fahrenheit scale, kelvin scale, humidity, dew point, red led, green led and blue led, so that you can read and write data to them.
   
7. Go to your dashboard so that you create gauges for temperature values.
   
8. Create a gauge for humidity and text display element for dew point temperature as well.
  
9. Create slider elements so that you control the intensity of red, green and blue color in an RGB led.
    
10. write your ssid and password, so that you can connect with the Wifi.

11. Visit the adafruit website to get your username and key, so that you can exchange data with the server.

12. Create the feed objects so that you can subscribe to data from the server

13. Create the feed objects so that you can publish data to the server

14. Subscribe to the feeds from which you want to fetch data

15. After getting the data from the DHT sensor, publish it to the server.

16. Write the appropriate code so that you can subscribe to the slider data from the server and use it to control the brightness of the RGB LED.

17. Once you have completed the code, you can see the output for temperature gauges

18. The output for humidity and dew point will appear

19. By toggling the sliders on the server you can control the color of your RGB LED.
