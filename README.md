# Convert Videos

Convert videos in the current directory into various formats: .mp4 (h264, h265), webm (vp9), .mkv (.av1).

## Usage

```
$ ./convert_videos
```

The output videos are generated in the subdirectory `cache/`

## Parameters

* `-f/--force`: Force the creation of new videos (remove previous cache).
  * ex. `convert_videos -f`
* `-w/--width N`: Set the resizing of a video for a given width in pixels. 
  * ex. `convert_videos -w 400`.
