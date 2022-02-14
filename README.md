# Chrome Dino enhanced
Chrome Dino, but with enhancement that works for most browsers.

Also check out [Microsoft Edge's *Let's Surf*](https://github.com/yell0wsuit/ms-edge-letssurf), an offline game for Microsoft Edge.

<p align="center">
  <img src="https://i.imgur.com/kIV1YKm.png"/>
  Default night mode for dark-enabled OS
</p>

<p align="center">
  <img src="https://i.imgur.com/krI6KnS.png" />
  Normal day mode
</p>

## Play
Play online: https://yell0wsuit.github.io/html5-games/games/chrome-dino/

Play offline: download or clone this repo, then open ``index.html`` to play.

## Features / Changes

- Preserve highscore. Use ``localStorage`` to save and retrieve high score. No more accidental refresh that wipes your hard work!
   - The original code uses native code from Chrome to retrieve and store score, something that isn't possible for other browsers.
- Reset highscore by clicking/tapping on the HI score twice.
- Arcade mode. The game adapts to the screen width like the Chrome version (chrome://dino). Beneficial to big screens.
- Day & night cycle. Game will start in night cycle if the users choose the dark theme in the OS/browser setting.
   - Fixed the bugs related to invert filter.
   - Also fixed dark mode for Firefox.
- Use other pixelated filters for other browsers so the game looks consistent across browsers.
- Gamepad support (not tested).
- PWA support. You can install this game as an app to play offline.
   - This is useful on mobile platforms since you cannot open ``index.html`` directly like PC.  
   On iOS, you need to use Safari and add the page to the homescreen.
- Fix the game not working on iOS/iPadOS Safari browser.
