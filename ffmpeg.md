if you encounter an error:

``RuntimeWarning: Couldn't find ffmpeg or avconv - defaulting to ffmpeg, but may not work
  warn("Couldn't find ffmpeg or avconv - defaulting to ffmpeg, but may not work", RuntimeWarning``

  it means your ffmpeg was not installed properly.

  run the following commands to install via 3rd party:

  ``brew tap homebrew-ffmpeg/ffmpeg``

  then

  ``brew install homebrew-ffmpeg/ffmpeg/ffmpeg``

  alternatively, i found a helpful tutorial by [phoenix NAP](https://phoenixnap.com/kb/ffmpeg-mac).
  