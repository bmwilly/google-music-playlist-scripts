# Google Music Playlist Scripts

Some quick scripts for editing Google Music playlists.

Uses the unofficial Google Music Api by [simon weber](https://github.com/simon-weber).

## Setup

Install the necessary library

```
pip install gmusicapi
```

and set the environment variables `GOOGLE_USER` and `GOOGLE_PW`.

## Usage

### delete_dups_from_playlists

- This script deletes the duplicate songs from within each individual playlist. The tracks must be identical (ie. the same track id and song file) to be deleted.

### add_last_songs_to_top_of_playlist

- This script provides a way to move the last N songs of a playlist to be the first N songs. Run it without arguments to see the usage.

### Warning

- Neither script prompts you before making changes to your playlists.
