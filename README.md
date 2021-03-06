# ![icon](https://raw.github.com/punker76/simple-music-player/master/icon/Gramaphone48x48.png) Simple Music Player

[![Gitter chat](https://badges.gitter.im/punker76/simple-music-player.png)](https://gitter.im/punker76/simple-music-player)  

[![Build status](https://img.shields.io/appveyor/ci/punker76/simple-music-player/master.svg?style=flat-square)](https://ci.appveyor.com/project/punker76/simple-music-player/branch/master)
[![Twitter](https://img.shields.io/badge/twitter-%40punker76-55acee.svg?style=flat-square)](https://twitter.com/punker76)

This is the next version of my simple music player ([SimpleMP](http://jkarger.de/simple-music-player/))

**SimpleMP** or **Simple Music Player** is a simple and easy to use music player for free. It plays the most common music files (mp3, ogg, wma, wav) in a very simple way, just drag&drop your files or folders on the main screen and start push play...

Why another music player? When I decided to make my first player back in 2005, the Winamp 3 player was to buggy and very slow! I stopped developing in 2007.
I used my favorite programming language Delphi 5 and I learned a lot of new stuff. It was a great time and a few people in the Delphi community honored my work :-)
Unfortunately, the interface of the FMOD sound library was no longer supported for Delphi and I decided to stop working on it.

So after long time, it's time to make a new one!

It's not perfect and many function not yet implemented.

***Use it with your own risk!***

## First simple functions

+ Plays **mp3**, **ogg**, **wma** and **wav** files (should be enough... or not?)
+ Drag&Drop your files or directories into the player (on the play list)
+ Drag&Drop files within the playlist
+ Add directories to the medialib (not yet finished)
+ Simple 10 band equalizer
+ Simple volume fade in and out (5 sec per default, can be changed in the settings file)
+ Shortcut keys if the player is on top and has the focus
	+ **[Space]** play or pause current file (if none is playing, the first selected file starts)
	+ **[Enter]** play selected files
	+ **[Del]** delete selected files from current playlist
	+ **[j]** play next file
	+ **[k]** play previuos file
	+ **[s]** shuffle mode on / off
	+ **[r]** repeat play list on / off
	+ **[m]** mute player on / off
	+ **[e]** show the equalizer
	+ **[l]** show the medialib
+ Flexible, responsive UI (different views for different window sizes)
+ You can link with the supported files (open with...)
+ Working as single instance, that means
	+ if you try start the player twice you get always the first started player
	+ if you link with supported media files, the player loads the new files and play the first file from the added files
+ Tooltip on playlist files

## Releases

- [v1.9.2](https://github.com/punker76/simple-music-player/releases/tag/v1.9.2)
- [v1.9.1](https://github.com/punker76/simple-music-player/releases/tag/v1.9.1)
- [v1.9.0.14](https://github.com/punker76/simple-music-player/releases/tag/v1.9.0.14)
- [v1.9.0.13](https://github.com/punker76/simple-music-player/releases/tag/v1.9.0.13)
- [v1.1.7.2](http://jkarger.de/simple-music-player/)

## Awesome libs that I use

- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro)
- [MaterialDesignInXamlToolkit](https://github.com/ButchersBoy/MaterialDesignInXamlToolkit) Google Material Design in XAML & WPF, for C# & VB.Net from @ButchersBoy
- [gong-wpf-dragdrop](https://github.com/punker76/gong-wpf-dragdrop)
- [Font-Awesome-WPF](https://github.com/charri/Font-Awesome-WPF) FontAwesome controls for WPF from @charri
- [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)
- [NLog](https://github.com/NLog/NLog)
- [QuickIO.NET](http://quickio.azurewebsites.net/)
- [ReactiveUI](https://github.com/reactiveui/ReactiveUI)
- [Rx (Reactive Extensions)](http://rx.codeplex.com/)
- [Splat](https://github.com/paulcbetts/splat)
- [TinyIoC](https://github.com/grumpydev/TinyIoC)
- [xunit](https://github.com/xunit/xunit)

## Icons

Most Icons are taken (inspired) from (thx @Templarian)

- [Windows Icons](https://github.com/Templarian/WindowsIcons) -> [modernuiicons](http://modernuiicons.com)
- [Material Design](https://github.com/Templarian/MaterialDesign) -> [materialdesignicons.com](http://materialdesignicons.com/)
- [Metrize Icons](http://www.alessioatzeni.com/metrize-icons/) by [Alessio Atzeni](https://twitter.com/Bluxart) @Bluxart

## License

### Simple Music Player

[MIT License](http://opensource.org/licenses/MIT/)

Copyright (c) 2012 - 2017 Jan Karger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### FMOD API

[FMOD](http://www.fmod.org) is not distributed under the MIT license. You must agree to this [EULA](LICENSE_FMOD) if you compile the source or use any compiled release of Simple Music Player, otherwise you must download [FMOD](http://www.fmod.org) by yourself.

## Screen shots (milestones)

![very early screenshot 20](https://raw.github.com/punker76/simple-music-player/master/screenshots/2015-10-20_23h51_14.png)  

![very early screenshot 19](https://raw.github.com/punker76/simple-music-player/master/screenshots/2015-10-20_23h50_59.png)  

![very early screenshot 18](https://raw.github.com/punker76/simple-music-player/master/screenshots/2015-10-20_23h50_51.png)  

![very early screenshot 17](https://raw.github.com/punker76/simple-music-player/master/screenshots/2015-07-19_22h18_51.png)  

![very early screenshot 16](https://raw.github.com/punker76/simple-music-player/master/screenshots/2015-07-19_22h19_10.png)  

![very early screenshot 15](https://raw.github.com/punker76/simple-music-player/master/screenshots/2014-11-02_12h11_31.png)  

![very early screenshot 14](https://raw.github.com/punker76/simple-music-player/master/screenshots/2014-07-14_22h42_19.png)  

![very early screenshot 13](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-11-26_20h58_04.png)  

![very early screenshot 12](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-11-26_20h58_17.png)  

![very early screenshot 11](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-11-10_23h42_10.png)  

![very early screenshot 10](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-11-10_23h42_24.png)  

![very early screenshot 09](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-09-16_09h40_08.png)  

![very early screenshot 08](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-09-16_09h40_02.png)  

![very early screenshot 07](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-02-07_22h49_52.png)  

![very early screenshot 06](https://raw.github.com/punker76/simple-music-player/master/screenshots/2013-01-05_23h26_18.png)  

![very early screenshot 05](https://raw.github.com/punker76/simple-music-player/master/screenshots/2012-12-19_21h55_18.png)  

![very early screenshot 04](https://raw.github.com/punker76/simple-music-player/master/screenshots/2012-12-19_21h54_53.png)  

![very early screenshot 03](https://raw.github.com/punker76/simple-music-player/master/screenshots/2012-12-19_14h48_05.png)  

![very early screenshot 02](https://raw.github.com/punker76/simple-music-player/master/screenshots/2012-12-16_17h14_57.png)  

![very early screenshot 01](https://raw.github.com/punker76/simple-music-player/master/screenshots/2012-12-13_23h14_25.png)  
