# Playlist To Names

This bash script allows to extract video names from a YouTube playlist.

# Dependencies
The script requires [wget](https://www.gnu.org/software/wget/) or [curl](http://curl.haxx.se/).

# Usage
./playlist2links 123CODEOFPLAYLIST
... or
./playlist2links 123CODEOFPLAYLIST withnames

The list of YouTube playlist's links is now saved in `playlist_123CODEOFPLAYLIST.txt`.

If the `withnames` argument is used, then each link will be preceeded by the video's name.
