# TalkTrip — Japanese A2 + Italian A1 · Mobile Travel Speaking Coach

TalkTrip is a mobile-friendly, dependency-free single-file HTML learning app. All lesson content and its interface are bundled into `index.html`.

## Included

- **Japanese (A2):** 18 travel and social conversation scenes, 144 dialogue lines, 144 vocabulary entries, Japanese kana reading toggle, polite and casual speech in context.
- **Italian (A1):** 18 scenes, 144 dialogue lines, 144 vocabulary entries, beginner-friendly conversational patterns.
- **Modes:** Listen & repeat, audio-only comprehension quiz, speaking/typing practice, guided scripted dialogues, words and phrasebook.
- **Listening:** Device/browser text-to-speech with selectable speed and supported device voices.
- **Speaking:** Browser speech recognition where supported; recognized text is compared against a model phrase. This is **not** a validated pronunciation/accent score. A separate voice recorder lets you listen to your own speech, where supported.
- **Memory:** Saved word/phrase deck, simplified spaced repetition, missed-response cards, daily habit counters, separate progress per language.
- **Storage:** Browser localStorage. Export/import JSON backups. No sign-in, no external JavaScript or paid API.

## Open on your phone (recommended)

### Option A: Publish to GitHub Pages

1. Create a repository on GitHub (public or on a plan that supports the visibility you need).
2. Upload the included `index.html` to the root of the repository.
3. Under **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Open your GitHub Pages HTTPS address on your phone and use **Add to Home Screen** in the browser menu.

HTTPS is recommended for microphone features. Changes to the HTML file do not normally erase progress on the same website address and browser, but clearing site data or switching domains can. Export progress JSON before changes to be safe.

### Option B: Open HTML directly

Open `index.html` in a compatible browser, if your phone/file manager allows local HTML files. Listening may work, but voice recording/recognition and local storage can be restricted in local-file mode. Hosting via HTTPS is more reliable.

## How to study (8–12 minutes each day)

1. **Listening:** Open a scene, choose **Listen quiz**, play the phrase and answer three questions.
2. **Speaking:** Switch to **Speak**, answer three English prompts aloud, then listen and repeat the model phrase. Use recording and replay when available.
3. **Memory:** Open **Review**, test five due cards. Choose Again, Hard, Good or Easy honestly.
4. **Conversation:** Once or twice a week, finish a **Dialogue** without revealing every response.

Start with **When you don't understand**, **Meeting local people**, **Everyday small talk**, **Making plans with friends**, and the scenarios related to your upcoming travel.

## Browser and privacy notes

- The text-to-speech voices depend on your operating system and browser. Install Japanese and Italian voice packages if playback uses the wrong voice.
- Speech recognition availability varies by browser, HTTPS context, network and permissions. Some browsers send speech for recognition to an external speech service. No audio is intentionally uploaded by TalkTrip itself.
- Voice recording is stored only temporarily in your tab and is not exported with progress.
- If the microphone is unavailable, you can type answers and play audio examples instead.
- Dialogues follow fixed scripted lines, not an unrestricted AI conversation with free-form responses.
- Travel and health phrases are educational examples, not a substitute for live professional advice where needed.
- Progress is stored locally in your browser. Use **Me → Export progress** and **Me → Import saved progress** to move devices or keep backups.

## Run without changing code

Open `index.html` to start. All styles, curated lessons and JavaScript are included in the file. No build, npm installation or API key is required.
