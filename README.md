# convert2mp4 - Use ffmpeg to convert movie file to x264/MP4

## Installation

### Manual

Copy the file `convert2mp4` from this repository and put it in a directory of
your choice (preferably one on your `PATH`).


### Homebrew

```sh
brew tap infogrind/homebrew-tap
brew install convert2mp4
```

## Usage

```sh
convert2mp4 <file>
```

This converts the given video file (it must be one that `ffmpeg` recognizes) to
an `mp4` file with `x264` video and `aac` audio encoding.
