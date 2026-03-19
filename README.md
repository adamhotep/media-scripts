# media-scripts
Media-related scripts, mostly for the GNU/linux command line.

## acoustid
Identify audio files by their [AcoustID](https://acoustid.org/) fingerprints
(requires fpcalc from libchromaprint-tools).

## audacious-songchange
Command triggers for audacious/beep/xmms2/xmms on changing songs
(originally called xmms-songchange),
ideal for stopping after the current song completes.

## bitrate
Get bitrate stats on given media files
(requires [MediaInfo](https://mediaarea.net/MediaInfo)
and [jq](https://jqlang.github.io/jq)).

## chapters
List chapters in a given file or contents given a list of files.

## convert2opus
Converts audio files to Opus.

## exifname
Rename, re-date, and optionally shrink/convert images given EXIF information
(requires [exiftool](https://exiftool.org/)).

## ffconcat
Concatenate movies with chapters marking the original files.

## framerate
Reads or calculates and then displays the frames per second
for each stream in given movie(s)
(requires [FFmpeg](https://ffmpeg.org/)).

## handbrakex
A command-line wrapper around
[HandBrake](https://github.com/HandBrake/HandBrake)
with advanced preset handling
(requires HandBrakeCLI from handbrake-cli).

## img2clipboard
Cpoy an image to the clipboard (requires xclip).

## isosuck
Copy and verify a DVD image to a file named for its title
(requires isoinfo from genisoimage or cdrkit).

## jpg2mp4
Extract Google Motion Photo content from filename.MP.jpg
and save it to filename.mp4.

## kodi-remote
Command-line interface for Kodi allowing you to pass
simple commands, methods, and even JSON.

## media2opus
Convert given media files to audio-only opus in OGG containers
(requires [FFmpeg](https://ffmpeg.org/)).

## mpvssh
Stream a video over SSH and play locally with mpv
(requires [mpv](https://mpv.io/)).

## vcf2img
Dump images from VCARD data to files in the current directory.
