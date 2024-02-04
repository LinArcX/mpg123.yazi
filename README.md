# mpg123.yazi
Play audio files in yazi using [mpg123](https://www.mpg123.de/). To add this plugin, download `init.lua` and add it to: `~/.config/yazi/mpg123.yazi`. 
Then add this line to `yazi.toml`:

```
prepend_previewers = [
  { mime = "audio/*", exec = "mpg123" },
]
```
