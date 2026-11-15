# TalkTrip v2.1.2 — iPhone playback repair

No API calls, no external scripts. All lessons, flashcards and progress from v2.1 remain.

## Install
Upload index.html to the same GitHub Pages repo as your prior version. Export a JSON backup of progress before upgrading. Keep the same domain and browser to retain local saved data.

## iPhone diagnostic sequence
In Safari over HTTPS, go to Me > Audio & learning.
1. Tap Play speaker beep. If no beep, check media volume, Bluetooth routing, and phone output.
2. Tap Test short system voice. If no speech, tap Test selected native voice.
3. Choose an explicit Japanese or Italian voice if desired, then try the third test again.
4. Copy diagnostic report and share the text if still silent.

Note: Safari speech synthesis is provided by iOS. A list of voices does not guarantee audible playback. WebAudio beep isolates speaker output but cannot replace system Japanese/Italian speech. This package was browser-interaction-tested using Chromium emulation, not on a physical iPhone.
