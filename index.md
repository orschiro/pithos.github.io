---
layout: default
title: Pandora Radio Client
---

Pithos is a native [Pandora Radio](http://pandora.com) client for Linux. It's much more lightweight
than the Pandora.com web client, and integrates with desktop features such as media
keys, notifications, and the sound menu.

## News

**Pithos 1.1.2 released!** This is another bug fix release that fixes
the SSL error when using Pandora One. There are also a few plugin
improvements including fixing the tray on KDE 5.

**Pithos 1.1.1 released!** This is a bug fix release that fixes occasional
erratic buffering behavior.
Pithos 1.1.1 requires GTK 3.14+ (Ubuntu 15.04, Fedora 21). See
[below](#install) for installation instructions.

**Pithos 1.0.3 released!** This is a bug fix release that fixes occasional
erratic buffering behavior for the 1.0.x series (GTK 3.10 compatible),
for those of you using Fedora <= 20 and Ubuntu <= 14.10.
<hr/>
**We are happy to announce the release of Pithos 1.1.0!** There are
many new features, including a redesigned preferences dialog.
Pithos 1.1.0 requires GTK 3.14+ (Ubuntu 15.04, Fedora 21). See
[below](#install) for installation instructions.

**Pithos 1.0.2 bug fix release!** We have also released a bug fix release
for the 1.0.x series (GTK 3.10 compatible), for those of you using Fedora 
<= 20 and Ubuntu <= 14.10. 1.0.2 fixes a critical bug where Pithos would
freeze up under certain deadlock conditions.

## Screenshot

![Pithos screenshot](img/screenshot1.0.png)

## Links

- [Installation](#install)
- [Changelog](changelog.html)
- [Source](https://github.com/pithos/pithos)
- [Source Downloads](https://github.com/pithos/pithos/releases)
- [Binary Downloads](binaries.html)
- [Bug reports](https://github.com/pithos/pithos/issues)
- [Wiki](https://github.com/pithos/pithos/wiki)
- [IRC](ircs://chat.freenode.net/pithos)

## Features

- Play / Pause / Next Song
- Switching stations
- Remembering user name and password
- Cover Art
- Thumbs Up / Thumbs Down / Tired of this song
- Notification popup with song info
- Launching pandora.com song info page and station page
- Reconnecting when pandora session times out
- Editing QuickMix
- Creating stations
- Media Key support
- Proxy support
- Last.fm scrobbling

## <a name="install">Install</a>

### Installing on Ubuntu

    sudo add-apt-repository ppa:pithos/ppa
    sudo apt-get update
    sudo apt-get install pithos

### Installing on Fedora

First add the [RPMFusion](http://rpmfusion.org/Configuration) repos. Then:

    sudo yum install pithos
    
### Installing from source

Please read the [wiki](https://github.com/pithos/pithos/wiki/Installing-from-Source)
for information on installing from source.
  
## FAQ

### Why the name "Pithos?"

The original Pandora myth used the word "[pithos](http://en.wikipedia.org/wiki/Pithos),"
which was mistranslated to "box." Similarly, a flash applet is a
mistranslation to the Linux platform.
 
### What does Pithos mean for Pandora?

To support Pandora Media Inc. and enjoy higher quality audio, we recommend
subscribing to [Pandora One](http://pandora.com/one).
