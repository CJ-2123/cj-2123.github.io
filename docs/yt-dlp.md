# yt-dlp

<a href="https://github.com/yt-dlp/yt-dlp">yt-dlp</a> - audio/video downloader

mp4 command requires <a href="https://github.com/yt-dlp/FFmpeg-Builds">FFmpeg</a>

## my commands

**download mp4**

```
yt-dlp -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best" --merge-output-format mp4 --postprocessor-args "ffmpeg:-r 60 -vsync cfr" URL
```

converts to a clean CFR (in 60fps) file to fix missing frames issue in DaVinci Resolve.

**download mp3**

```
yt-dlp -x --audio-format mp3 URL
```

**download sections of video**

```
yt-dlp --download-sections "*2:00-3:00" "URL"
```

example to download video from 2:00 to 3:00

**download multiple urls**

```
yt-dlp -f "bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best" --merge-output-format mp4 --postprocessor-args "ffmpeg:-r 60 -vsync cfr" -a urls.txt
yt-dlp -x --audio-format mp3 -a urls.txt
```

urls.txt must be formatted as follows:

```
# Music videos
https://youtube.com/watch?v=...
https://youtube.com/watch?v=...

# Tutorials
https://youtube.com/watch?v=...
```

one line per url. blank lines are ignored. lines starting with '#' are considered comments and are ignored
