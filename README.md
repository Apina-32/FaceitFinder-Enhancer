# FaceitFinder-Enhancer
Fetches and displays cs:go competitive and Esportal ranks in faceitfinder.com

The code is in desprate need of refactoring, since this started as a proof of concept and still is that.

There are some not so optimal practices used due to the nature of this script and due to the original sites implementation.

### Features
- Adds matchmaking and esportal ranks to faceitfinder.com. Uses csgostats.gg or convars.com for getting the matchmaking rank and other data for players.
- Latest faceit match is acquired from faceit api.
- Esportal rank is acquired from Esportal api.

The script also adds some QOL improvements to the site.

This has been tested to work with Tampermonkey and Violentmonkey on Chromium(Edge & Chrome) and Firefox.

### [Install userscript](https://github.com/Apina-32/FaceitFinder-Enhancer/raw/main/userscript.user.js)
