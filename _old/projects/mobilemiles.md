---
layout: page
title: MobileMiles
permalink: /projects/mobilemiles
---

A simple web app tracking vehicle maintenance and fill-up statistics. A completely reimagined version 2.0 is now under development. Expect big things!



Overview
--------

MobileMiles is simple web app for tracking fuel mileage and other statistics
straight from your mobile device. Every time you fill up, simply enter the
number of gallons pumped and the unit price, tap submit and you're set! The
legacy version is available at [gas.randomland.net](http://gas.randomland.net).
The in-development 2.0 version is available at [mobilemiles-ui.herokuapp.com](http://mobilemiles-ui.herokuapp.com).



Ok, what does it do for me?
---------------------------

MobileMiles provides a simple HTML interface to a "fill-up" list (version 1.0
stores this in a Google Drive spreadsheet, version 2.0 uses a database). The
following stats are viewable from the web interface:

- fuel mileage
- trip distance
- fill-up location
- fill-up date and time
- fill-up notes

The "stats" sheet gives you a historical look, calculating these at 30- and
60-day intervals as well as an "all-time" column. These advanced stats are
calculated, but not currently displayed:

- pump-price accuracy
- days between fill-ups
- cost per day
- cost per mile

The entry form will autofill most of the form for you with "guesses", saving
you time at the pump. The autofilled fields are:

- date and time of fill-up
- "favorite" location (most frequently occuring text value)
- odometer reading estimate (based on last mileage + average trip distance)
- price-per-gallon estimate (uses last fill-up's value)



Links
-----

- [New web app (live)](http://mobilemiles-ui.herokuapp.com)
- [Back-end source code](https://github.com/zourtney/mobilemiles)
- [Front-end source code](https://github.com/zourtney/mobilemiles-ui)
- [Legacy web app (live)](http://gas.randomland.net)