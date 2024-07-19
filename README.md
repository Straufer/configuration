<div align="center">
  <h1>I3WM Arch Preview</h1>
</div>

<div align="center">
  <h3>Border Off</h3>
  <p><img src="https://github.com/asfung/configuration/blob/main/image/i3wm-no-border.png?raw=true" /></p>
</div>

<div align="center">
  <h3>Border On</h3>
  <p><img src="https://github.com/asfung/configuration/blob/main/image/i3wm-border.png?raw=true" /></p>
</div>


### Bar,Compositor,Tiling Window Manager, Fonts, Etc
- [Polybar](https://github.com/polybar/polybar)
- [Rofi](https://github.com/davatorium/rofi)
- [Picom](https://github.com/yshui/picom)
- [i3-gaps](https://i3wm.org/docs/userguide.html), [i3-lock](https://github.com/i3/i3lock)
- [Fish Shell](https://fishshell.com)
- [Nerd Font](https://nerdfonts.com), [Font Awesome](https://fontawesome.com/download), [JetBrains NF](https://www.nerdfonts.com/font-downloads)
- [Wallpapers](https://github.com/asfung/configuration/tree/main/i3wm/wallpapers)

<h2 align="center">Lock Preview</h2> 
<p><img src="https://github.com/asfung/configuration/blob/main/image/i3wm-lock.png?raw=true" /></p>

- Theme Lock by [dracula](https://draculatheme.com/i3lock-color)


## Tmux Preview
<p><img src="https://github.com/asfung/configuration/blob/main/image/image_1.png?raw=true" /></p>
*require tpm for that one*

#### Requirement for Tmux 
- [TPM (Tmux Plugin Manager)](https://github.com/tmux-plugins/tpm) (no needed for rn)

## Neovim setup here man
[Click Here](https://github.com/asfung/configuration/tree/main/nvim)

### Requirements for Nvim Setup
- [Neovim](https://neovim.io/) >= v9.0+ 
- [Maven3.XX.X+](https://maven.apache.org) & [JDK17.XX.X+](https://www.oracle.com/id/java/technologies/downloads/)
- C/C++ Compiler (use [mingGW](https://github.com/niXman/mingw-builds-binaries/releases)/[MYSYS2](https://www.msys2.org) if using windows)
- [CMake](https://cmake.org) (recommended to install if on windows)
- [NPM](https://nodejs.org/en/download/package-manager) (for mason plugin)

- <b>Has been tested on Ubuntu and Arch(available on Unix,GNU/Linux, also WSL)</b>


### Getting Started Nvim Setup 
```bash
# get the setup file
$ wget https://raw.githubusercontent.com/asfung/configuration/main/setup_nvim.sh
# give it  access premission 
$ chmod +x setup_nvim.sh
# execute the setup file
$ ./setup_nvim.sh # Recommended with superuser
# execute the nvim and waiting the plugins installed 
$ nvim 
```
<!-- now u ready to lit it up man🔥🔥-->




