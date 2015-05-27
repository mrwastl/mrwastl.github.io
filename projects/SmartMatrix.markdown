---
layout     : project
title      : SmartMatrix
category   : fork
giturl     : https://github.com/mrwastl/SmartMatrix
origurl    : https://github.com/pixelmatix/SmartMatrix
origauthor : pixelmatix
description: Teensy 3.x library for HUB75-compliant RGB matrix LED panels
---

[{{page.title}}]({{page.giturl}})
===========

Description
-----------
{{ page.description }}

* **Location on github**: [mrwastl/{{page.title}}]({{page.giturl}})
* **Fork** of  [{{page.origauthor}}/{{page.title}}]({{page.origurl}})
* **Documentation**: [README.md]({{page.giturl}}/blob/master/README.md)

Differences to original version
-------------------------------
* Support for chained panels (multi-panel support)
* Foreground functions can be disabled to save memory
* Other colour spaces than RGB888 to save memory
* Clock example for internal RTC

History
-------
* `2015-04-18` : Support added for colour spaces with smaller memory requirement
* `2015-04-06` : Foreground support for chained panels, clock example for internal RTC
* `2014-12-08` : Added flag to disables foreground functionality (to save memory)
* `2014-11-15` : Added support for c-shape chaining of panels
* `2014-11-14` : First publishing of fork (multi-panel, z-shape chaining)

