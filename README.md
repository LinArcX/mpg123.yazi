# mpg123.yazi
audio-preview for yazi using [mpg123](https://www.mpg123.de/). To add this plugin, just download `init.lua` and add it to: `~/.config/yazi/mpg123.yazi`. 
Then add this line to your `yazi.toml`:

```
prepend_previewers = [
  { mime = "audio/*", exec = "mpg123" },
]
```
