<!-- EWW Widgets -->
This is a for of <a href="https://github.com/adi1090x/">Aditya Shakya</a>'s EWW config named <a href="https://github.com/adi1090x/widgets">widgets</a>. I do not plan on ever submitting a pull request, in respect of the original creator's wishes.

# Warning

I'm using spt to interface with Spotify. As it uses the spotify API, I do not recommend increasing the update frequency.

# Widgets


<p align="left">Few widgets for <a href="https://github.com/elkowar/eww">EWW</a>, Elkowar’s Wacky Widgets.</p>


---

## Arin

<p align="center">
  <img src="previews/arin.png">
</p>

## Dashboard

<p align="center">
  <img src="previews/dashboard.png">
</p>

### Installation

- Install Elkowar’s Wacky Widgets - [Instructions](https://elkowar.github.io/eww)
- Install spotifyd - [Instructions](https://docs.spotifyd.rs/) - Available on Pacman
- Install spt - [Instructions](https://github.com/Rigellute/spotify-tui#installation) - Available on AUR
- Clone this repository
```
$ git clone --depth=1 https://github.com/adi1090x/widgets.git
```
- Create eww config directory : **`~/.config/eww`**
- Copy everything from `eww` directory to **`~/.config/eww`**
- Install the required fonts from **`fonts`** directory

### Tips

- Put `eww` executable in your PATH (/bin, /usr/bin, etc).
- The `launch_dashboard` scripts works like a toggle, Perfect for key-bindings.
- You can use cron jobs to update weather and mail scripts.
- Get you own [weather key](https://openweathermap.org/api) from `openweathermap`, It's free.
- Edit `mails` script and add your credentials to get unread mails.

### FYI

- Don't use <a href="https://github.com/adi1090x/">the original creator's</a> black picture for your profile. 
- (Currently) Made for 1920x1080 displays only.

### Credit

- [The upstream repo](https://github.com/adi1090x/widgets) - Absolutely great work by <a href="https://github.com/adi1090x/">Aditya Shakya</a>.
- [Spotify TUI](https://github.com/Rigellute/spotify-tui) - The interface for Spotifyd
- [Spotifyd](https://github.com/Spotifyd/spotifyd) - A Spotify Daemon used to listen to music from Spotify.
### Todo

- [x] Change the music info scripts to use spt
- [x] Change Arin to use spt
- [x] Change the Dashboard to use spt
- [x] Original repo music widget functionality parity
- [ ] Add support for 2560 x 1080 Displays (My resolution)
- [ ] Add a sptlrx module. Toggleable? (Spotify lyrics)
