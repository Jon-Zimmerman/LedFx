As the team behind this project is unable to continue, I am working on a version to minimize the lag between the LEDs and the Raspberry Pi. The initial setup used an ESP8266 chip over wifi. Some routers have too much delay with other network traffic that the LEDs drop samples. Currently I am working on integrating the python server code into the code required to run the LED strip off of GPIO12.






LedFx
=================================================================================
|Build Status| |License| |Discord|

WARNING: This project is in early development, so expect to encounter minor issues along the way. If you have issues either join the discord or open an issue.

LedFx is a network based LED effect controller with support for advanced real-time audio effects! LedFx can control multiple devices and works great with cheap ESP8266 nodes allowing for cost effectvice syncronized effects across your entire house!

For installation instructions see the `documentation <https://ahodges9.github.io/LedFx/>`__.

Demos
---------

We are actively adding and perfecting the effects, but here is a quick demo of LedFx running three different effects synced across three different ESP8266 devices:

.. image:: https://raw.githubusercontent.com/ahodges9/LedFx/master/demos/ledfx_demo.gif

.. |Build Status| image:: https://travis-ci.org/ahodges9/LedFx.svg?branch=master
   :target: https://travis-ci.org/ahodges9/LedFx
.. |License| image:: https://img.shields.io/badge/license-MIT-blue.svg
.. |Discord| image:: https://img.shields.io/badge/chat-on%20discord-7289da.svg
   :target: https://discord.gg/wJ755dY
