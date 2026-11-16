# TalkTrip v2.3 — Offline Audio Edition

This release preserves v2.2 lessons, games, Ultralearning and local progress.

**Included:** 144 locally synthesized Italian MP3 lesson dialogue lines, embedded in index.html. These are synthetic and may sound robotic. No Japanese audio is bundled: no reliable offline Japanese synthesizer was available in the build environment. Japanese play buttons open a file picker for user-supplied recordings (temporary for the current page session).

**No API or network needed at runtime.** All Italian MP3 audio is embedded directly into index.html. Open the file directly, or deploy index.html to GitHub Pages.

**iPhone:** test Me > Test prerecorded Italian audio. The underlying HTMLAudioElement is different from Safari's silent speechSynthesis engine. Actual iPhone hardware verification was not possible here.

**Limitations:** Not a complete Japanese pack. Japanese imported recordings are not persisted. Original native speech diagnostics remain visible but the normal lesson Play buttons use prerecorded audio. Keep a v2.2 JSON progress backup before updating.
