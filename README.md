# Lt. Danny Cruz Retirement Slideshow

A Hartford Fire Department themed slideshow celebrating Lt. Danny Cruz's retirement.
Open `index.html` in a browser, or view the deployed site.

## Using it at the party
- The show starts on its own and loops.
- **F** or the corner button: full screen. The controls fade out after a few seconds.
- **Left / Right arrows**: previous / next photo. **Space**: pause or play.
- On a phone or tablet, swipe left or right.
- **Play music** (top right) or **M**: start or pause the background music. Browsers only allow sound
  after a click, so press it once when the show starts. The jukebox panel has previous/next song buttons.

## Editing
Everything you would want to change is at the top of the `<script>` in `index.html`:
- `HONOREE`: the name shown on the title and closing slides.
- `OPENING` and `CLOSING`: the messages on the first and last slides.
- `PHOTOS`: the photo order, chapter labels and captions. To add a photo, upload
  it to the `DCRUZ PHOTOS` folder and add a line with its file name.
- `SECONDS_PER_PHOTO`: how long each photo stays up.
- `SONGS`: the playlist. Each song lists a few YouTube video IDs (the part after `watch?v=` in a
  YouTube link). If a video can't be played on other websites, the player tries the next ID, then
  skips to the next song. `MUSIC_VOLUME` sets the starting volume.
