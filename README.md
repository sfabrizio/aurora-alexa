# Aurora Alexa

ESP8266 Client over mqtt for turn on/off all your [aurora](https://github.com/garhul/aurora) devices with Alexa.


## Install

This project is done on [platformio](https://platformio.org/), Follow the doc in there it's pretty straightforward.

With Platformio working is just a simple build & upload of the project. 
Before do it so just make sure to change config values to your in 'main.cpp'

#Related Projects:

- (https://github.com/garhul/aurora)[aurora]
- (https://github.com/sfabrizio/aurora-mqtt-server)[aurora-mqtt-server]


## TODO:
- code segregation, it's everything in the main.cpp now.
- find a way to send effects and more parameters from Alexa. Now it's just an on/off with a hardcode effect. 


Thanks to @garhul for (https://github.com/garhul/aurora)[aurora]