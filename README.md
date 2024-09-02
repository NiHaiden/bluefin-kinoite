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

Find all the downloads on the official website!

[Aurora Website](https://getaurora.dev)
