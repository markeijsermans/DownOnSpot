<div align="center">

# DownOnSpot

### A Spotify downloader written in Rust

<img src="assets/icon.svg" alt="drawing" width="500"/>
</div>

## Disclaimer

```text
DownOnSpot was not developed for piracy, but educational and private usage.
It may be illegal to use this in your country!
I am not responsible in any way for the usage of this app.
```

## Features

- Multi-threaded
- Download 320 kbit/s audio from spotify, directly
- Download playlists and albums
- Convert to mp3
- Simple usage over CLI

## Building

To build this project you will need `Nightly Rust`. You can install it by following [rustup.rs](https://rustup.rs) instructions.

```bash
git clone https://github.com/oSumAtrIX/DownOnSpot.git
cd DownOnSpot
cargo build --release
```

If you get a linker error, you might need to download the [standard libmp3lame](https://www.rarewares.org/mp3-lame-libraries.php#libmp3lame) library.

## Usage/Examples

To install and use DownOnSpot, edit the configuration file which is being created in the same directory as your shell on first launch.

```bash
$ down_on_spot.exe
Settings could not be loaded, because of the following error: IO: NotFound No such file or directory. (os error 2)...
..but default settings have been created successfully. Edit them and run the program again.

$ down_on_spot.exe
Usage:
down_on_spot.exe (track_url | album_url | playlist_url)
```

## Authors

- [@oSumAtrIX](https://osumatrix.me/#github)
- [@exttex](https://git.freezer.life/exttex)

## License

[GPL3](https://choosealicense.com/licenses/agpl-3.0/)
