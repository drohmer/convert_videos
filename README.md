# Convert Videos

Convert videos in the current directory into various formats: .mp4 (h264, h265), webm (vp9), .mkv (.av1).

## Usage

```
$ ./convert_videos
```

The output videos are generated in the subdirectory `cache/`

## Parameters

* `-h/--help`: Display all parameters.
  * ex. `convert_videos --help`
* `-f/--force`: Force the creation of new videos (remove previous cache).
  * ex. `convert_videos -f`
* `-w/--width N`: Set the resizing of a video for a given width in pixels. 
  * ex. `convert_videos -w 400`.
* `-q/--quality`: Set the video quality, 0:loseless, 51:worst, default:30.
  * ex. `convert_videos -q 40`.
* `--av1`: Generate an output in .mkv encoded with av1 codec. The encoding is slow and disabled by default.
  * ex. `convert_videos --av1`.

