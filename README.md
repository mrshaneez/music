# Groove — Music Player

A music player that runs in the browser as a single HTML file. It has no dependencies and no build step.

## Features
- **Studio (beat maker):** make your own beats with drums, bass and melody on a step grid. You can set the tempo, swing, key and scale, choose sounds, start from a style (Hip-hop, House, Lo-fi, Pop, Trap) or press *Surprise me*, then save the beat as a song in your library. Songs you make can be reopened in the Studio with the pencil button.
- **YouTube & TikTok:** paste a YouTube video, YouTube Short or TikTok video link and it joins your library. It plays in the site's official embedded player and works with play/pause, next, shuffle and repeat.
- **Add from a link:** paste a direct link to an audio or video file and Groove downloads it into your library. If the site doesn't allow downloads, the file is added for online play instead.
- **Audio and video:** plays MP3, M4A, WAV, OGG, FLAC, MP4, WebM, MOV and more. Videos play in the player, with a fullscreen button.
- **Saved library:** everything you add is kept in your browser, so it's still there next time.
- **Save to device:** a download button on each item saves the file to your computer or phone.
- Add files with the **+ Add files** button or by dragging them onto the page
- Play/pause, next/previous, seek, volume and mute
- Shuffle, and repeat (off / all / one)
- A circular visualizer driven by the Web Audio API
- Search and remove songs in the playlist
- Three demo tracks that the browser generates itself, so you can try it right away
- Lock-screen and media-key controls through the Media Session API

## Keyboard shortcuts
| Key | Action |
|-----|--------|
| Space | Play / pause |
| ← / → | Previous / next |
| ↑ / ↓ | Volume |
| S | Shuffle |
| R | Repeat |
| M | Mute |
| F | Fullscreen (video) |

**In the Studio:** Space plays or stops the beat, 1 / 2 / 3 switch between Drums, Bass and Melody, and Esc closes it.

## Run it
Open `index.html` in any modern browser, or turn on **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root).

Your songs and videos stay on your device and are never uploaded.

### About links
- **Direct file links** (`https://example.com/song.mp3`) are downloaded into your library.
- **YouTube and TikTok links** play through the sites' official players. They stream rather than download, since those sites don't allow downloads, so they need internet. Some videos can't play outside YouTube because their owner turned that off.
- **TikTok short links** (`vm.tiktok.com/…`) need to be opened in a browser first. Copy the full address, which contains `/video/` and a long number.
- Spotify, SoundCloud and other streaming sites aren't supported.
