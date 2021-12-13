# Album-Splitter
Splits single youtube videos into several mp3s for use with spotify

# Dependencies

Mutagen - `pip install mutagen`

FFMpeg - http://www.ffmpeg.org/

yt-dlp - https://github.com/yt-dlp/yt-dlp

# How To Use

Run python script in directory that you want the have the files in

# Options

`--test` - choose lowest quality youtube video to speed download speed up for testing purposes

`[artist name]` - (REQUIRED TO DOWNLOAD) The artist's name

`[album name]` - (REQUIRED TO DOWNLOAD) The album's name

# Example

`py AlbumSplitter.py https://www.youtube.com/watch?v=Tf1DEI2lEe0 "Mick Gordon" "DOOM Eternal OST"`
