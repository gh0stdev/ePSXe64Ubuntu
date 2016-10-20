# ePSXe64Ubuntu - Alpha Release

![](http://i.imgur.com/Ja5u4Dg.png)

Interactive script to install ePSXe and shaders on Ubuntu using built-in core GPU & SPU plugins.

## Installation

```bash
wget https://raw.githubusercontent.com/brandleesee/ePSXe4Ubuntu/master/e4u.sh

bash e64u.sh
```

Enter SUDO password.

ePSXe GUI will open. 

**CLOSE** the ePSXe window to continue with the script. 

![](http://i.imgur.com/p8vMQDt.png)

Folder ` ~/ePSXe ` will be created in Home  ` ~ ` directory.

Hidden folder ` ~/.epsxe ` will also be created in Home  ` ~ ` directory.

` libsdl-ttf2.0-0 ` will be installed.

![](http://i.imgur.com/w4Ua94W.png)
Your permissions may vary.

All downloaded compressed files are removed once set-up is complete.

# Shortcomings from ePSXe & Plugins Developers

* ` Config --> Wizard Guide ` is not present.
* Selecting ` Config --> Plugins --> Video/Audio/etc ` kills ePSXe ([video](https://www.youtube.com/watch?v=Ru49bfyXijw)). This is because Pete's [GPU](http://www.pbernert.com/html/gpu.htm) & [SPU](http://www.pbernert.com/html/spu.htm) plugins are only compiled for x32 architecture. I have so far been unable to get them to work in spite of a multiarch architecture. [More info](http://ngemu.com/threads/v2-0-5-linux-x64.188425/).

## TODO List

- [ ] Lock to Launcher.

## Submitting Issues

**Quote sub-heading(s)** from script ` e64u.sh `.

## Tested on 

* Ubuntu Unity 16.04 x64 multiarch
* Ubuntu Gnome 16.04 x64 multiarch
* Ubuntu Unity 16.10 x64 multiarch
* Ubuntu Gnome 16.10 x64 multiarch
* Ubuntu Gnome x64 devel multiarch

### ePSXe Version

* 2.0.5 Linux x64

## Current Video Settings

![](http://i.imgur.com/MDQabuy.png)
