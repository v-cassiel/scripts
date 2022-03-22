<div align="center">
    <h1>Scripts</h1>
    <p>
        Personal collection of scripts</br>
    </p>
</div>

---

### Scripts

- **setwall**
> Sets wallpaper and lockscreen background through _xwallpaper_ and _betterlockscreen_

- **ytdl**
> Wrapper script for youtube-dl, gets video or audio direcly from the copied Youtube link found in the clipboard at runtime. Requires _xclip_ and assumes that the URL is in the clipboard

- **sysgrade**
> Easy all-in-one full system upgrade script with backup using timeshift and AUR updates using paru [WIP]

### Installation

1. Clone the repository

`git clone https://github.com/VCassiel/scripts`

2. Copy/Move/Link the script(s) to a location included in $PATH

`ln -sr ./scripts/{ytdl,setwall,sysgrade} ~/.local/bin`

3. Enable execute permissions as needed

`chmod +x /path/to/scripts/*`
