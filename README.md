# Aurora Alexa

ESP8266 Client over mqtt for turn on/off all your [aurora](https://github.com/garhul/aurora) devices with Alexa.

# Demo

[![aurora demo video](https://img.youtube.com/vi/mX4hph_eGeM/0.jpg)](http://www.youtube.com/watch?v=mX4hph_eGeM)

## Install

This project is done on [platformio](https://platformio.org/), Follow the doc in there it's pretty straightforward.

With Platformio working is just a simple build & upload of the project.
Before do it so just make sure to change config values to your in 'main.cpp'

## Related Projects:

- [aurora](https://github.com/garhul/aurora) - Light's effects/animations for ws2812, ws2811, ws2813 led strips
- [rc-aurora](https://github.com/sfabrizio/rc-aurora) - Control Aurora devices from an RC control
- [aurora-mqtt-server](https://github.com/sfabrizio/aurora-mqtt-server) - Simple mqtt broker/pub/sub over nodeJS

## TODO:

- code segregation, it's everything in the main.cpp now.
- find a way to send effects and more parameters from Alexa. Now it's just an on/off with a hardcode effect.

Thanks to [@garhul](https://github.com/garhul)!
