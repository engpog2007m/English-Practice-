# English Speaking Practice for Afaan Oromoo Speakers
*Haasaa Ingiliffaa: Afaan Ingiliffaa dubbachuu shaakali.*

A free, single-page web app that helps Oromo speakers practice
spoken English. Tap a sentence to hear it, say it out loud, and
see which words the browser recognized.

**Live demo:** https://yourusername.github.io/english-speaking-practice

## Features
- 26 everyday sentences, each with its Afaan Oromoo meaning
- Listen at normal or slow speed; tap any word to hear it alone
- Speak & check: green/red word feedback and a score
- Record your voice and play it back
- Afaan Oromoo / English interface toggle
- Progress saved on your own device (no accounts, no tracking)

## How it works
Plain HTML, CSS and JavaScript, no build step or dependencies.
Uses the browser's Web Speech API (speech synthesis and
recognition) and MediaRecorder. Scoring matches the target
sentence against the recognized words (longest common subsequence).

## Browser support
| Feature | Chrome (Android/desktop) | Safari (iOS) | Firefox |
|---|---|---|---|
| Listen | Yes | Yes | Yes |
| Speak & check | Yes | Partial | No |
| Record | Yes | Yes | Yes |
Needs https and microphone permission. Speech checking needs internet.

## Limitations
Scoring depends on the browser's speech recognition and may
mis-hear accented speech. Treat it as a guide, not a grade.

## Contributing
Corrections to the Afaan Oromoo text are very welcome; open an
issue or a pull request. Sentences live in the `S` array in index.html.

## License
MIT
