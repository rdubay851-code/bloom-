# Add your music

Put your audio file in the `assets` folder and name it exactly:

`bloom-ambient.mp3`

Example:

bloom-site/
  index.html
  app.js
  style.css
  assets/
    bloom-ambient.mp3

Then refresh Bloom and press the `♪` button.

For best browser compatibility use MP3 (AAC/M4A also works in many browsers). The site starts audio only after the user taps the sound button because browsers block autoplay with sound.

If you want a different filename, edit this line in `app.js`:

`const src=get('bloomMusic','assets/bloom-ambient.mp3');`
