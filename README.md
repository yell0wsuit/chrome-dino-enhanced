# Chrome Dino enhanced
Chrome Dino, but with enhancement that works for most browsers.

## Play
Play online: https://yell0wsuit.github.io/html5-games/games/chrome-dino/

Play offline: download or clone this repo, then open ``index.html`` to play.

## Features / Changes

- Preserve highscore. Use ``localStorage`` to save and retrieve high score. No more accidental refresh that wipes your hard work!
   - The original code uses native code from Chrome to retrieve and store score, something that isn't possible for other browsers.
   - Highscore reset will be implemented later.
- Arcade mode. The game adapts to the screen width like the Chrome version (chrome://dino). Beneficial to big screens.
- Day & night cycle. Game will start in night cycle if the users choose the dark theme in the OS/browser setting.
   - Fixed the bugs related to invert filter.
   - Also fixed dark mode for Firefox.
- Use other pixelated filters for other browsers so the game looks consistent across browsers.
- Gamepad support (not tested).
- PWA support. You can install this game as an app to play offline.
   - This is useful on mobile platforms since you cannot open ``index.html`` directly like PC.
- Fix the game not working on iOS/iPadOS Safari browser.
