<p align="center">
  <br>
  <img alt="Logo" src="media/logo.png">
  <br><br>
  <a href="https://github.com/yourusername/eDEX-UI-NEXT"><img alt="Maintained" src="https://img.shields.io/badge/maintained-yes-brightgreen"></a>
  <a href="https://github.com/yourusername/eDEX-UI-NEXT/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/release/yourusername/eDEX-UI-NEXT.svg?style=popout"></a>
  <a href="https://github.com/yourusername/eDEX-UI-NEXT/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/yourusername/eDEX-UI-NEXT.svg?style=popout"></a>
  <br>
  <!-- Update or add your own download badges here -->
  <br>
  <a href="https://github.com/GitSquared/edex-ui/releases/tag/v2.2.8"><strong><i>(Original project archived Oct. 18th 2021)</i></strong></a>
  <br><br><br>
</p>

> **:rocket: Welcome to eDEX-UI-NEXT!**
>
> **Project status:** _Actively maintained and improved in 2025. Now fully compatible with modern Linux (Debian/Ubuntu 2025+), and with major performance improvements—lower CPU & memory usage!_
>
> eDEX-UI-NEXT is a community-powered fork of the legendary [eDEX-UI](https://github.com/GitSquared/edex-ui), bringing the sci-fi terminal into the future. See below for what’s new!

---

eDEX-UI-NEXT is a fullscreen, cross-platform terminal emulator and system monitor that looks and feels like a sci-fi computer interface.

---

<a href="https://youtu.be/BGeY1rK19zA">
  <img align="right" width="400" alt="Demo on YouTube" src="media/youtube-demo-teaser.gif">
</a>

Heavily inspired by the [TRON Legacy movie effects](https://web.archive.org/web/20170511000410/http://jtnimoy.com/blogs/projects/14881671) (especially the [Board Room sequence](https://gmunk.com/TRON-Board-Room)), the original eDEX-UI project was meant to be *"[DEX-UI](https://github.com/seenaburns/dex-ui) with less « art » and more « distributable software »"*.

While keeping a futuristic look and feel, it strives to maintain a certain level of functionality and to be usable in real-life scenarios, with the larger goal of bringing science-fiction UXs to the mainstream.

<br>

It might or might not be a joke taken too seriously.

---

<p align="center">
  <em>Jump to: <br><a href="#whats-new-in-this-fork-">What's New</a> — <a href="#features">Features</a> — <a href="#screenshots">Screenshots</a> — <a href="#qa">Questions & Answers</a> — <strong><a href="#how-do-i-get-it">Download</a></strong> — <a href="#featured-in">Featured In</a> — <a href="#useful-commands-for-the-nerds">Contributor Instructions</a> — <a href="#credits">Credits</a></em>
</p>

---

## What's New in eDEX-UI-NEXT? 🚀

- **2025 Compatibility:** Runs flawlessly on the latest Debian/Ubuntu and other modern Linux systems.
- **Performance Boost:** Optimized to consume less CPU and memory.
- **Actively Maintained:** Open to issues, pull requests, and new features.
- **More improvements coming—your contributions are welcome!**

_See [CHANGELOG.md](./CHANGELOG.md) for full technical details._

---

## Features

- Fully featured terminal emulator with tabs, colors, mouse events, and support for `curses` and `curses`-like applications.
- Real-time system (CPU, RAM, swap, processes) and network (GeoIP, active connections, transfer rates) monitoring.
- Full support for touch-enabled displays, including an on-screen keyboard.
- Directory viewer that follows the CWD (current working directory) of the terminal.
- Automatically pauses monitoring modules when the window loses focus and resumes when focus returns.
- Advanced customization using themes, on-screen keyboard layouts, CSS injections. See the [wiki](https://github.com/GitSquared/edex-ui/wiki) for more info.
- Optional sound effects made by a talented sound designer for maximum Hollywood hacking vibe.

---

## Screenshots

![Default screenshot](media/screenshot_default.png)
_[neofetch](https://github.com/dylanaraps/neofetch) on eDEX-UI with the default "tron" theme & QWERTY keyboard_

![Blade screenshot](media/screenshot_blade.png)
_Checking out available themes in [eDEX's config dir](https://github.com/GitSquared/edex-ui/wiki/userData) with [`ranger`](https://github.com/ranger/ranger) and the "blade" theme_

![Disrupted screenshot](media/screenshot_disrupted.png)
_[cmatrix](https://github.com/abishekvashok/cmatrix) with the experimental "tron-disrupted" theme, and the user-contributed DVORAK keyboard_

![Horizon screenshot](media/screenshot_horizon.png)
_Editing eDEX-UI source code with `nvim` and the custom [`horizon-full`](https://github.com/GitSquared/horizon-edex-theme) theme_

---

## Q&A

#### How do I get it?
Check the badges at the top, visit the [Releases](https://github.com/yourusername/eDEX-UI-NEXT/releases) tab, or download via [repositories](https://repology.org/project/edex-ui/versions) (Homebrew, AUR, etc).

Public release binaries are unsigned ([why](https://gaby.dev/posts/code-signing)). On Linux, you will need to `chmod +x` the AppImage file in order to run it.

#### I have a problem!
Search through the [Issues](https://github.com/yourusername/eDEX-UI-NEXT/issues) to see if yours has already been reported. If not, open a new issue!

#### Can you disable the keyboard/the filesystem display?
You can't disable them (yet) but you can hide them. See the `tron-notype` theme.

#### Why is the file browser saying that "Tracking Failed"? (Windows only)
On Linux and macOS, eDEX tracks where you're going in your terminal tab to display the content of the current folder on-screen.  
On Windows, this isn't possible yet, so the file browser runs in "detached" mode. You can still browse files & directories and click files to input their path in the terminal.

#### Can this run on a Raspberry Pi / ARM device?
We provide prebuilt arm64 builds. For other platforms, see [this issue comment](https://github.com/GitSquared/edex-ui/issues/313#issuecomment-443465345), and the thread on issue [#818](https://github.com/GitSquared/edex-ui/issues/818).

#### Is this repo actively maintained?
**Yes! eDEX-UI-NEXT is a modern, maintained fork as of 2025, bringing eDEX-UI to the latest Linux distributions and improving performance.**  
See [What's New](#whats-new-in-edex-ui-next-) above.

#### How did you make this?
Glad you're interested! See [#272](https://github.com/GitSquared/edex-ui/issues/272).

---

## Featured in...

- [Linux Uprising Blog](https://www.linuxuprising.com/2018/11/edex-ui-fully-functioning-sci-fi.html)
- [My post on r/unixporn](https://www.reddit.com/r/unixporn/comments/9ysbx7/oc_a_little_project_that_ive_been_working_on/)
- [Korben article (in french)](https://korben.info/une-interface-futuriste-pour-vos-ecrans-tactiles.html)
- [Hacker News](https://news.ycombinator.com/item?id=18509828)
- [This tweet that made me smile](https://twitter.com/mikemaccana/status/1065615451940667396)
- [BoingBoing article](https://boingboing.net/2018/11/23/simulacrum-sf.html) - Apparently I'm a "French hacker"
- [OReilly 4 short links](https://www.oreilly.com/ideas/four-short-links-23-november-2018)
- [Hackaday](https://hackaday.com/2018/11/23/look-like-a-movie-hacker/)
- [Developpez.com (another french link)](https://www.developpez.com/actu/234808/Une-application-de-bureau-ressemble-a-une-interface-d-ordinateur-de-science-fiction-inspiree-des-effets-du-film-TRON-Legacy/)
- [GitHub Blog's Release Radar November 2018](https://blog.github.com/2018-12-21-release-radar-november-2018/)
- [opensource.com Productive Tools for 2019](https://opensource.com/article/19/1/productivity-tool-edex-ui)
- [O'Reilly 4 short links (again)](https://www.oreilly.com/radar/four-short-links-7-july-2020/)
- [LinuxLinks](https://www.linuxlinks.com/linux-candy-edex-ui-sci-fi-computer-terminal-emulator-system-monitor/)
- [Linux For Everyone (Youtube)](https://www.youtube.com/watch?v=gbzqCAjm--g)
- [BestOfJS Rising Stars 2020](https://risingstars.js.org/2020/en#edex-ui)
- [The Geek Freaks (Youtube/German)](https://youtu.be/TSjMIeLG0Sk)
- [JSNation Open Source Awards 2021](https://osawards.com/javascript/#nominees) (Nominee - Fun Side Project of the Year)

---

## Useful commands for the nerds

**IMPORTANT NOTE:** The following instructions are for running eDEX-UI-NEXT from source (unoptimized/development). For stable software, see [How do I get it?](#how-do-i-get-it).

#### Starting from source:
On *nix systems (You'll need Xcode command line tools on macOS):

- clone the repository
- `npm run install-linux`
- `npm run start`

On Windows:

- start cmd or PowerShell **as administrator**
- clone the repository
- `npm run install-windows`
- `npm run start`

#### Building
Note: Due to native modules, you can only build for the host OS.

- `npm install` (NOT `install-linux` or `install-windows`)
- `npm run build-linux` or `build-windows` or `build-darwin`

The script will minify, recompile, and create distributable assets in the `dist` folder.

#### Getting the bleeding edge
For the latest development binaries, visit [GitHub Actions](https://github.com/GitSquared/edex-ui/actions), click the latest commit, and download the artifacts for your OS.

---

## Credits

Original eDEX-UI by [Squared](https://github.com/GitSquared).  
[PixelyIon](https://github.com/PixelyIon) helped with Windows compatibility and early advice.  
[IceWolf](https://soundcloud.com/iamicewolf) composed the sound effects on v2.1.x and above.

---

## Thanks

Special thanks to [Seena](https://github.com/seenaburns) and the r/unixporn community.  
Also to the developers of [xterm.js](https://github.com/xtermjs/xterm.js), [systeminformation](https://github.com/sebhildebrandt/systeminformation), [SmoothieCharts](https://github.com/joewalnes/smoothie), and [Rob "Arscan" Scanlon](https://github.com/arscan) for [ENCOM Globe](https://github.com/arscan/encom-globe).

---

## Licensing

Licensed under the [GPLv3.0](https://github.com/GitSquared/edex-ui/blob/master/LICENSE).
