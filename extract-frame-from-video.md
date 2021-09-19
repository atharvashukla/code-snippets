## Using ffprobe to get width and height of a video

```
ffprobe -v error -select_streams v -show_entries stream=width,height -of csv=p=0:s=x video_file.mp4
```

## Using the dimentions to extract a the first frame from the video as an image

```
ffmpeg -i BaiZe.mp4 -r 1 -s 1000x1000 -f image2 BaiZe.png
```

