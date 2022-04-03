**Candelabra** is a browser-based time tracker capable of tracking time on
multiple projects and providing for quick switching between which timer
is running.

![screenshot](https://raw.github.com/hiddn/candelabra/master/screenshot1.png)

This version is a fork of jtauber's candelabra, with new features:
* Modify times (if you forgot to start or stop the clock)
* Archive projects
* Show dates and duration for each time the clock was on
* Show interesting weekly stats for all projects

![screenshot](https://raw.github.com/hiddn/candelabra/master/screenshot2.png)


It is a single HTML file (using hosted versions of jQuery)
that uses localStorage for persisting logs between browser refreshes but
it is not intended for long-running time recording. The expected use case
is that times would be logged to some other system occasionally and cleared
from Candelabra.

You can run it directly from http://hiddn.github.io/candelabra/candelabra.html

For maximum enjoyment, make your browser as narrow as possible and turn off
as much chrome as you can (toolbar, status bar, etc).

**NOTE**: time resolution is in minutes so don't expect the timer to change
until a minute has passed.

As of version 0.2, Candelabra has been tested on Safari, Chrome and Firefox.

## Authors

- James Tauber
- Luke Hatcher
- Hidden (hiddn on github)

## Change Log

### 0.1

- initial release

### 0.2

- removed external Bootstrap dependency
- added gradient to project block
- fixed scrolling issues when projects extend too far
- added support for mobile devices
- added iOS application mode when saved to home screen

### 0.3
- modify times (if you forgot to start or stop the clock)
- archive projects
- show dates and duration for each time the clock was on
- show interesting weekly stats for all projects
- using https for jquery source
- color in red the project and the clock when the clock is ticking
