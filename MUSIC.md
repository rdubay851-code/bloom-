# Bloom ambient music

This version includes three tiny original ambient WAV loops:

- `assets/soft-light.wav` — warm/gentle
- `assets/night-blue.wav` — quiet/deep
- `assets/morning-mist.wav` — airy/morning

Bloom automatically selects the track that matches the chosen mood and keeps the volume very low.

## Replace them with your own music

Keep the same filenames and replace the WAV files, or edit `musicByMood` in `app.js` to point to MP3 files such as:

```js
const musicByMood={
  soft:'assets/soft-light.mp3',
  night:'assets/night-blue.mp3',
  mist:'assets/morning-mist.mp3'
};
```

## Important browser rule

Desktop and mobile browsers can block audible autoplay until the visitor interacts with the page. Bloom tries to start automatically, and if the browser blocks it, the first tap/click/key press starts the music automatically. This is a browser security rule and cannot reliably be bypassed by JavaScript.
