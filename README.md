# Music

My personal mp3 registry. Does this count as piracy? I hope not. This basically just a syncronasation tool.

All music was ripped of youtube using [yt-dlp](https://github.com/yt-dlp/yt-dlp), more specifically like so:

```bash
yt-dlp --extract-audio --audio-format mp3 --embed-metadata <url>
```

It is preferable to download songs that have `Provided to YouTube by ...` or that are available on YouTube Music because those have better metadata.
