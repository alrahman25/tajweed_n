# Audio assets

The interface is ready to use recorded audio without text-to-speech.

- Rule readings: `rules/izhar.mp3`, `rules/idgham.mp3`, `rules/iqlab.mp3`, `rules/ikhfa.mp3`
- Example readings: one MP3 per `audioSrc` declared in `script.js`
- Effects: `sfx/correct.mp3`, `sfx/wrong.mp3`, `sfx/applause.mp3`, `sfx/level-complete.mp3`, `sfx/click.mp3`

Until recordings are supplied, missing rule/example files show a friendly notice and the activity remains usable. Missing effects fall back to short generated tones. No text-to-speech is used.
