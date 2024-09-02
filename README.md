# Project Aurora

# BIG Announcement

## Aurora got added to the official Bluefin repo!

Hello pro-stargazers. As some of you might have already seen, Aurora got added to the official [Bluefin](https://github.com/ublue-os/bluefin) Repo in a big rework by the fantastic @m2giles. The images now build out of this repository, including new :40 tags that include Plasma 6. Making this drastic but necessary change makes Aurora and Bluefin coexist more peacefully next to each other as it makes maintenance work a whole lot easier. This also means Aurora and Bluefin now get features equally fast when they get added to the image. 


## Rebasing to the new shiny images

As a precaution you should always pin your last working deployment. 
`sudo ostree admin pin 0`

This also means the images that live in my personal account are now bascially deprecated but still available. 
To rebase to the new images, please use the following command **(adjust accordingly to your current image that you're running, e.g. aurora-dx-asus-nvidia)**: 

Use the `:40`  tag for the new shiny Fedora 40 images or the `:latest` tag to get the latest stable release.

**To get Aurora Stable (from a working Ublue-Image-Install):** 

`rpm-ostree rebase ostree-image-signed:docker://ghcr.io/ublue-os/aurora:stable`

**To get Aurora DX Stable (from a working Ublue-Image-Install):** 

`rpm-ostree rebase ostree-image-signed:docker://ghcr.io/ublue-os/aurora-dx:stable`


Please test out these images and give us feedback on how they are working out. New ISOs coming soon!

Don't like Gnome but want the all the goodies the awesome Bluefin Image provides? Aurora is a Bluefin fork which utilizes the KDE Desktop environment instead of Gnome, while keeping the core things that make Bluefin awesome the same. 

![This is the Aurora Banner.](./banner.jpg)

# **This image is considered Beta!** 

We're going to the stars! Aurora is getting it's first ever logo.

# Downloads

[Aurora Offline ISO Download](https://dl.getaurora.dev/aurora-latest.iso)

[Aurora-DX Offline ISO Download](https://dl.getaurora.dev/aurora-dx-latest.iso)

[Aurora Nvidia Offline ISO Download](https://dl.getaurora.dev/aurora-nvidia-latest.iso)

[Aurora-DX Nvidia Offline ISO Download](https://dl.getaurora.dev/aurora-dx-nvidia-latest.iso)

[Aurora Surface ISO Download](https://dl.getaurora.dev/aurora-surface-latest.iso)

[Aurora-DX Surface Offline ISO Download](https://dl.getaurora.dev/aurora-dx-surface-latest.iso)

[Aurora Framework ISO Download](https://dl.getaurora.dev/aurora-framework-latest.iso)

[Aurora-DX Framework Offline ISO Download](https://dl.getaurora.dev/aurora-dx-framework-latest.iso)

# What is Aurora anyway?
Aurora is a brand-new, customized and fine-tuned KDE experience that gears towards power users and developers alike. The images contain many useful scripts and tools, all derived from the awesome Bluefin project by the Universal-Blue Team. It combines these nice things with the KDE desktop environment which is a beautiful, modern and sleek desktop experience packed with features. 

Under the hood we use Fedora, Universal-Blue and other great technologies to deliver this rock-stable desktop experience. 

## What images are there? 
We have two kinds of images, each with support for different hardware types. 

- Aurora: A customized experience with the focus on powerusers, including the Prompt terminal and other useful things like fonts. 
- Aurora-DX: The developer experience. Comes with several features, including preinstalled Cloud-Native tools, container tools and runtimes and so much more, including preinstalled VS Code and scripts for getting your favorite Jetbrains IDE setup in a matter of seconds (depending on your internet speed) 🫡.

Each image is available in a Surface, Framework, Asus and Nvidia Version to support every exotic hardware out there. 

At the end I want to give a big shoutout to [The Universal Blue Project](https://github.com/ublue-os) because without these guys, Aurora would have never been possible. Thanks so much. 

Peace out. ✌️
