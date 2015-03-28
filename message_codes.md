Message codes
===================

The SD module pools other modules every period. It then stores the code on the SD card.


### GPS related codes (1xx)

* 100 - OK

### AccidentDetection related codes (2xx)

* 200 - OK
* 201 - Back distance sensor reacted. There is an object in the back. 
* 202 - Front distance sensor reacted. There is an object in the front.
* 203 - Both distance sensors reacted. There are objects in the front and back.
* 204 - Gyroscope reacted, but there are no objects around the vehicle.
* 205 - Gyroscope + Back distance sensor = Hit from back.
* 206 - Gyroscope + Front distance sensor = Hit in front.
* 207 - Gyroscope + Both sensors = Hit while surrounded.

### Network related codes (3xx)

* 300 - OK
* 301 - Message sent
* 302 - DHCP Lookup failed
* 303 - Server contact failed
* 304 - Wrong API key

### SD related codes (4xx)

* 400 - OK
* 401 - Storage low
* 402 - Unable to make communication with the sensors (time-out error)
* 403 - Data pin isn't connected correctly
* 404 - Data pin connected to GND or very low voltage
* 405 - Data pin connected to high voltage (+3.3V or greater)
* 410 - Unknown error
