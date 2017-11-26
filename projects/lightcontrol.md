---
layout: page
title: LightControl
permalink: /projects/lightcontrol
---


An ever-expanding suite of RaspberryPi home-automation projects.


Overview
--------

Have you ever wanted to turn your lights off with a simple tap on your
smartphone? Come on, admit it, it's an enticing idea. This open source
RaspberryPi home automation project seeks to give do-it-yourselfers with a
launchpad for internet-controlled GPIO switching. Start by programmatically
switching some living rooms lamps -- chances are you'll be dreaming up complex
electrical systems management in no time :-)


Server Software
---------------

The basis of the backend software is a Python web server [Flask](http://flask.pocoo.org)
running on a RaspberryPi that directly drives the GPIO pins. RESTful JSON APIs
are exposed for:

- Single pin manipulation
- Batch pin manipulation
- Scheduling via cron


Client Software
---------------

A very simple web interface has been built into the web server. Currently it
assumes and is limited to administering four GPIO pins.

There is a simple [WindowsPhone app](http://www.windowsphone.com/en-us/store/app/lightcontrol/76eaf03e-8970-4957-bcca-d59486d2475f)
that provides individual and batch pin manipulation, as well as schedule
viewing. This app also assumes and is limited to manipulation of four pins.


Links
-----

* [Server-side code on GitHub](https://github.com/zourtney/lightcontrol)
* [WindowsPhone 8 app](http://www.windowsphone.com/en-us/store/app/lightcontrol/76eaf03e-8970-4957-bcca-d59486d2475f)
* [Hardware builds](https://plus.google.com/118263545785118510462/posts/KqVU4rRTmtw)
* [gpiocrust - a Pythonic, object-oriented wrapper around the RaspberryPi's RPi.GPIO library](https://github.com/zourtney/gpiocrust)