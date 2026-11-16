# TalkTrip v2.2 — Ultralearning Studio

A single-file, mobile-first Japanese (A2) and Italian (A1) travel-speaking trainer. No AI service, API key, login, CDN, external scripts or third-party requests are used by the app.

## Install or use

- **Standalone HTML:** open `TalkTrip_Ultralearning_v2_2.html` in a compatible browser on your device.
- **GitHub Pages:** upload `index.html` to the root of a public GitHub Pages repository and enable Pages. Open the HTTPS Pages URL on your iPhone in Safari. In Safari, Share → Add to Home Screen for quick access.
- To upgrade from v1 / v2 / v2.1 / v2.1.2, use the **same domain and browser profile** if possible. Export a JSON backup first from **Me → Export**. If you change origin/site, use **Me → Import** with that backup.
- No installation or network connection is required when opening the standalone HTML from local files, but microphone recording typically requires a secure context (HTTPS or localhost) and the user's permission. iPhone file opening may be less reliable than GitHub Pages.

## What's new

Go to **Practice → Ultralearning Studio**, or choose the featured Ultralearning card from **Today**.

1. **Metalearning / goal map:** select a travel scene, project length (2 / 4 / 8 weeks), focus block (10 / 15 / 20 / 30 minutes), and your bottleneck.
2. **Focus:** an adjustable, pausable session timer.
3. **Directness:** answer a real travel exchange aloud before revealing the model phrase.
4. **Drill:** isolate your weakest area across three relevant sample exchanges: retrieval, reading comprehension, sentence construction, pronunciation self-comparison, polite/casual register, or follow-up questions.
5. **Retrieval:** produce the answer from a cue instead of picking from options.
6. **Feedback:** compare your answer with a model and self-assess your performance; typing exercise offers an *exact wording match* (which is not the same as correctness of all natural alternatives).
7. **Retention:** missed phrases go to the existing spaced-review deck.
8. **Intuition:** explain in your own words why a phrase or register is appropriate.
9. **Experimentation:** modify the response style and deliver another version.

A selectable four-week roadmap offers suggested situations for each language. Recent sessions, strengths/weaknesses and self-ratings are stored locally and included in JSON backups.

## iPhone audio limitation

**This version does not claim to fix Safari's silent text-to-speech bug.** If your phone plays a beep but Japanese/Italian synthesized voices remain silent, the existing speechSynthesis path may still fail. Ultralearning exercises are designed to be usable from textual prompts and optional microphone recording without voice playback. Automatic speech recognition and automatic pronunciation grading are deliberately not included. A future no-API solution would bundle native-speaker MP3/M4A audio clips with the app and play them as ordinary audio instead of relying on Safari text-to-speech. This release does not contain a native-speaker audio pack.

## Privacy and backups

Lesson content is bundled in HTML. Progress and notes are stored using browser localStorage on your device. Voice recordings are temporary browser objects kept for a session and are neither uploaded nor included in the backup. Exported JSON backups are not encrypted, so keep them private. Clearing browser site data may erase progress.

## Testing

- Ran syntax and no-external-request static checks.
- Ran browser-based simulated phone tests at widths **320, 375, 390, 430 and 768 px** for the core four-step practice loop, saved progress, and page overflow.
- Exercised **all six drill types** in both Japanese and Italian, including sentence-typing feedback and polite/casual cards.
- Checked loading older progress data without an Ultralearning record.
- Browser rendering tests do not guarantee real iPhone audio output or permissions.

## Attribution

The practice design is our own adaptation inspired by the nine learning principles discussed in *Ultralearning* by Scott H. Young. It is not affiliated with or endorsed by the author or publisher, and contains no reproduced sections of the book.
