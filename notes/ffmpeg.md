# ffpmeg

```
# extract audio
ffmpeg -i input.mp4 -vn -acodec copy output.aac

# strip audio
ffmpeg -i input.mp4 -c copy -an output.aac

# convert video
ffmpeg -i input.ext -c copy output.mp4
ffmpeg -i input.ext -vcodec copy -acodec aac output.mp4
```
