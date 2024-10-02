
![example](https://github.com/longtermfree/oscc/blob/main/example.jpg)


Based on the original [osc](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua)

Compatible with [thumbfast](https://github.com/po5/thumbfast)

## How to install
Make sure you already have or created `mpv.conf` file, `scripts`, `script-opts` and `fonts` folders in your mpv directory

[oscc.lua](https://github.com/longtermfree/oscc/blob/main/oscc.lua) into `scripts`

[oscc.ttf](https://github.com/longtermfree/oscc/blob/main/oscc.ttf) into `fonts`

In `mpv.conf` put:

```
osc=no
cursor-autohide=3500         #synchronized with hidetimeout
osd-bar=no
```
Volume slider could be disabled in `osc.conf` which is in `script-opts`
```
volseekbar=no
```




