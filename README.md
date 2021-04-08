# ESP8266 based  HomeKit Weather Sensor
ESP8266 based  HomeKit Weather Station using Bosch BME280 temperature, humidity, barometric pressure sensor and 1.3" OLED screen

------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-New-Eve-Weather/total?color=green)](https://github.com/HomeKidd/ESP8266-HomeKit-New-Eve-Weather/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-New-Eve-Weather?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-New-Eve-Weather/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>


For **Usage** please read the [Build Instructions](https://github.com/HomeKidd/ESP8266-HomeKit-New-Eve-Weather/wiki/Build-Instructions) Wiki page!<br/><br/>


**This HomeKit enabled sensor works the same as the new [Elgato EVE Weather](https://www.evehome.com/en/eve-weather)!** 



**Features:**

* Temperature Sensor accessory
* Humidity Sensor accessory
* Barometric Sensor accessory _(requires Eve app)_
* Characteristic for detecting your altitude _(used for proper barometric calculation, requires Eve app)_
* **12 hour [Weather Forecast](https://github.com/HomeKidd/ESP8266-HomeKit-New-Eve-Weather/wiki/Weather-Forecast)**  _(requires Eve app)_
* **[SSD1306 OLED screen](https://s.click.aliexpress.com/e/_d7Bj0V3)** 
* Switching Temperature Display Units between Celsius and Fahrenheit  _(requires Eve app)_
* Downloadable User Manual  _(requires Eve app)_
* Reset button 
* ~~Data history~~ (not reliable enough, so its beta)


<br/>
<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-New-Eve-Weather/raw/main/images/weather_main2.PNG" class="center" width="450"/>

<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2021 Apple Inc. All rights reserved.
