# yt-snip

Snip youtube videos locally

1. Downloads a video from Youtube
2. Caches it locally
3. Crops the video at the given interval
4. Outputs the video at `./snip.mp4`, overwrites automatically
5. Plays it with `mplayer` right away to see what has been snipped

```sh
$ yt-snip
Usage: yt-snip <youtube_url> <start_time> <end_time>

$ yt-snip https://www.youtube.com/watch?v=wJ2Y4yQzuqE 00:00:13.6 00:00:20.14
```

## Dependencies

yt-dlp, ffmpeg, mplayer
