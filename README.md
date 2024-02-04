# mpg123.yazi
Play audio files in yazi using [mpg123](https://www.mpg123.de/). To add this plugin, clone this repo into: `~/.config/yazi/mpg123.yazi` and add this to `yazi.toml`:

```
prepend_previewers = [
  { mime = "audio/*", exec = "mpg123" },
]
```
