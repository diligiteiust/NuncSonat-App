# Lyrics

Lyrics are a Premium feature. The playlist button on the menu and the mini player cycles to the lyrics panel. Without a license that button stays visible and shows a lock.

## Where lyrics come from

Nunc Sonat looks in this order:

1. Lyrics the Apple TV already sent with the song.
2. A file in the lyrics folder you choose.
3. Lyrics stored on the song in the Music library.
4. An online lookup, when **Fetch lyrics online** is on. A timed online result is used instead of untimed Music-library lyrics.

A match is remembered in `~/Music/lyrics`. Settings → Lyrics shows how many songs are cached, and **Clear** removes that cache.

## Your own files

Settings → Lyrics → **Lyrics folder** chooses a folder of `.lrc` and `.txt` files.

- `.lrc` is timed. Lines follow the playhead.
- `.txt` is the words without times.

Name the file so the title (and, when you can, the artist) is in the file name or in the file’s tags. The folder is only read.

Turn **Fetch lyrics online** off if you only want the Apple TV, your folder, and the Music library.
