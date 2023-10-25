# Open-Source-Software
chb's list of preferred open source software

# Operating Systems

On operating systems, I like either super-reliable, never breaks, never crashes.... or something that's great to tinker with. I don't really care for the in-between options so much.

## Debian Linux - https://www.debian.org/
Debian is one of the very first Linux distributions, and features EXHAUSTIVE testing and amazing stability. If I had to provision a server, Debian would be my first choice.

## Linux Mint https://linuxmint.com/
Mint is derived from Debian via Unbuntu. It's not quite as stable as Debian, but that's like saying quartz isn't as hard as diamond. If a personal machine needs to be up and available to work on, I'd recommend Mint every time.

## EndeavourOS https://endeavouros.com/ 
Endeavour is *currently* my daily driver simply because it occupies a sweet-spot of ease of use and tinkerability. It's derived from Arch Linux and uses the fantastic pacman/libalpm package-manager, which includes mkpkg.

## Arch Linux https://archlinux.org/
Despite all the memes to the contrary, Arch Linux is not the *cool* Linux OS. It's a great OS for learning what the individual parts do and how to configure them to get exactly what you want. Importantly, the Arch Wiki is one of the single best resources for Linux configuration available: https://wiki.archlinux.org/ (Also, check the Gentoo wiki: https://wiki.gentoo.org/wiki/Main_Page )

## Artix Linux https://artixlinux.org/
Artix Linux is a rolling-release distribution, based on Arch Linux. 
>It uses real init systems, because PID1 must be simple, secure and stable.
>
Artix is an Arch-based distribution that eschews the popular systemd init system in favor of less complex systems like runit and s6. Like Arch, it's got great tinkerability.

## OpenWRT https://openwrt.org
OpenWRT is aimed at embedded devices, and, in particular, ARM-based routers and firewalls. It's fantastically configurable, but also rock-solid stable. If you use the internet, you NEED a firewall, and it probably needs to be running OpenWRT.

## Cinnamon Desktop Environment - https://github.com/linuxmint/cinnamon
>Cinnamon is a Linux desktop that provides advanced innovative features and a traditional user experience. The desktop layout is similar to Gnome 2 with underlying technology forked from Gnome Shell. Cinnamon makes users feel at home with an easy-to-use and comfortable desktop experience.

(chb's notes: Desktop preference is a very charged topic, almost as much as preferred text editor. Cinnamon is not perfect, but, for me, it's the only Linux GUI DE that doesn't make me want to rip my hair out. Before Cinnamon, I worked with Linux at the command prompt, period. It works intuitively and allows for reasonable customization. Cinnamon comes by default with the excellent Nemo file manager.)

# Media

## gThumb - https://wiki.gnome.org/Apps/Gthumb
gThumb is an image viewer and browser for gtk environments with robust organization and image management features. It was originally a fork of Geeqie (https://www.geeqie.org/)

## Inkscape - https://inkscape.org/
>Inkscape is a Free and open source vector graphics editor for GNU/Linux, Windows and macOS. It offers a rich set of features and is widely used for both artistic and technical illustrations such as cartoons, clip art, logos, typography, diagramming and flowcharting. It uses vector graphics to allow for sharp printouts and renderings at unlimited resolution and is not bound to a fixed number of pixels like raster graphics. Inkscape uses the standardized SVG file format as its main format, which is supported by many other applications including web browsers.

(chb's notes: Inkscape is one of those 'Best of Breed' applications that all other open source applications should look up to since it blows similar closed apps out of the water. Inkscape does one thing, vector drawing, and does it blindingly well.)

## MComix - https://sourceforge.net/p/mcomix/wiki/Home/
>MComix is a user-friendly, customizable image viewer. It is specifically designed to handle comic books (both Western comics and manga) and supports a variety of container formats (including CBR, CBZ, CB7, CBT, LHA and PDF)

## mpv - https://mpv.io/
>mpv is a free (as in freedom) media player for the command line. It supports a wide variety of media file formats, audio and video codecs, and subtitle types.

## yt-dlp - https://github.com/yt-dlp/yt-dlp
>yt-dlp is a youtube-dl fork based on the now inactive youtube-dlc. The main focus of this project is adding new features and patches while also keeping up to date with the original project.

(chb's notes: If you weren't familiar with yt-dlp or youtube-dl, it's a command-line utility to download videos from YT and MANY other sites. GUI front ends exist, but I use it primarily from the command-line and as an add-on for mpv. I download music and videos for later viewing because who knows when your internet is going to go out, or those videos just *disappear* forever.)

## gallery-dl - https://github.com/mikf/gallery-dl
>gallery-dl is a command-line program to download image galleries and collections from several image hosting sites. It is a cross-platform tool with many configuration options and powerful filenaming capabilities.

# Intertubes

## Librewolf - https://librewolf.net/
>This project is a custom and independent version of Firefox, with the primary goals of privacy, security and user freedom. LibreWolf is designed to increase protection against tracking and fingerprinting techniques, while also including a few security improvements. This is achieved through our privacy and security oriented settings and patches. LibreWolf also aims to remove all the telemetry, data collection and annoyances, as well as disabling anti-freedom features like DRM.

# Gaming

## Retroarch - https://www.retroarch.com/
>RetroArch is a frontend for emulators, game engines and media players. It enables you to run classic games on a wide range of computers and consoles through its slick graphical interface. Settings are also unified so configuration is done once and for all.

(chb's notes: Retroarch's setup and config is a PAIN. It's playlist-based console ROM selection is very counter-intuitive. However, once you do get it set up and configured, it's pretty amazing. If there's an emulator available for whatever console game you want to play, Retroarch will absolutely handle it.)

## Utilities

## Baobob - https://apps.gnome.org/app/org.gnome.baobab/
> A simple application to keep your disk usage and available space under control. Disk Usage Analyzer can scan specific folders, storage devices and online accounts. It provides both a tree and a graphical representation showing the size of each folder, making it easy to identify where disk space is wasted.

(chb's notes: Baobob is already part of many default GTK-based Linux installs. If you see a 'Disk Usage Analyzer' in your launcher, it's probably Baobob.)

## Bulky - https://github.com/linuxmint/bulky
>Bulky is used to rename files and directories.

Bulky is a bulk file renamer from the Linux Mint team. It allows you to rename multiple files based on several different conditions and with different patterns. It's very useful for, say, managing media collections, photographs, or the like.

## Gnome Disk Utility - https://wiki.gnome.org/Apps/Disks
>A GNOME utility for dealing with storage devices. 

Gnome Disk Utility, often installed by default as 'Disks' in many Linux distributions, is an application for handling physical disks and disk images. It can be used to mount disks, format, create disk images, or otherwise maintain any of the above.

(chb's notes: This is the best piece of software ever ripped off from Apple.) 


## GtkHash https://github.com/tristanheaven/gtkhash
>GtkHash is a desktop utility for computing message digests or checksums. Most well-known hash functions are supported, including MD5, SHA1, SHA2 (SHA256/SHA512), SHA3 and BLAKE2.

(chb's notes: An important part of the Linux ecosystem is the fact that we can verify the authenticity and correctness of downloads and any other file on our system with cryptographic hashes. Most of the time, with your package manager, this happens automatically. Sometimes you need to do it manually. GtkHash is what I use for that. Additionally, it integrates pretty seamlessly into Nemo and other GTK-based file managers.)

## kitty - https://sw.kovidgoyal.net/kitty/
kitty is a feature-rich terminal emulator that takes advantage of OpenGL hardware video acceleration. It's capable of displaying images, 32-bit color, Unicode emojis and a lot more.

## alacritty - https://alacritty.org/
alacritty is a very fast terminal emulator written in Rust.

## htop - https://htop.dev/
htop is a cross-platform, interactive process viewer. It is a text-mode application for consoles or terminals. 

## btop++ - https://github.com/aristocratos/btop
btop++, like htop, is a text-mode, interactive process viewer with a highly configurable interface and an aesthetic user interface.

(chb's notes: btop is *pretty* bloat!)

## Qalculate! - https://qalculate.github.io/
>Qalculate! is a multi-purpose cross-platform desktop calculator. It is simple to use but provides power and versatility normally reserved for complicated math packages, as well as useful tools for everyday needs (such as currency conversion and percent calculation).

(chb's notes: Qualculate! comes in command-line, GTK, and Qt versions. You'd want to use the Qt version if you're also using KDE. I find myself having bound a lot of features to command-line aliases and using it there more than via the GUI.)

# Fonts

## Iosevka - https://typeof.net/Iosevka/
>Iosevka is an open-source typeface family, designed for writing code, using in terminals, and preparing technical documents.

## Comfortaa - https://fonts.google.com/specimen/Comfortaa
>Comfortaa is a rounded, geometric, sans-serif type design intended for large sizes. It is absolutely free, both for personal and commercial use.

(chb's notes: As the name suggests, Comforta's rounded glyphs are very low-stress and comforting. It's very comfy.)

## Raleway - https://fonts.google.com/specimen/Raleway
>Raleway is an elegant sans-serif typeface family. Initially designed by Matt McInerney as a single thin weight, it was expanded into a 9 weight family by Pablo Impallari and Rodrigo Fuenzalida in 2012 and iKerned by Igino Marini. A thorough review and italic was added in 2016. 

## Rowdies  - https://fonts.google.com/specimen/Rowdies
>Rowdies is a Latin display typeface inspired by the rough & tough Indian action cinema. Roughness and oddness of each individual letter contribute collectively as a typeface to the fantasy of being bold, fearless and strong. Designed by Jaikishan Patel for action, drama, adventure, thriller, noir & crime genres of storytelling.

(chb's notes: Rowdies is AESTHETIC. I use it for game splash text.)

# System

## VirtualBox - https://www.virtualbox.org/
>VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.

## QEMU- https://www.qemu.org/
>QEMU is a generic and open source machine emulator and virtualizer.

(chb's notes: VirtualBox vs. Qemu. Yeah. This is a charged subject. When it comes to actual virtualization, Qemu does a better job. VirtualBox's config is FANTASTICALLY better, IMO, especially when it comes to Network handling. If you use Qemu, get ready to install some drivers and hunt for cryptic configs if you need the niceties.)

## ufw & gufw - https://gufw.org/
ufw is the uncomplicated firewall interface for iptables, allowing quick firewall administration on Linux. gufw is ufw's graphical front-end

## s6 - https://skarnet.org/software/s6/ & https://www.skarnet.org/software/s6-linux-init/
>s6 is a small suite of programs for UNIX, designed to allow process supervision (a.k.a service supervision), in the line of daemontools and runit, as well as various operations on processes and daemons. It is meant to be a toolbox for low-level process and service administration, providing different sets of independent tools that can be used within or without the framework, and that can be assembled together to achieve powerful functionality with a very small amount of code.

(chb's notes: It's a good idea to use s6 as part of a Linux distribution that has already integrated it, such as Artix Linux: https://artixlinux.org/ . I don't recommend using this on distributions that use systemd)


# Programming

## Ruby - https://www.ruby-lang.org/en/
>Ruby is a dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write. Ruby is an interpreted language with duck typing (https://en.wikipedia.org/wiki/Duck_typing).

## Crystal - https://crystal-lang.org/
>Crystal is a statically typed (https://en.wikipedia.org/wiki/Type_system#Static_type_checking), compiled programming language with syntax heavily inspired by Ruby’s, so it feels natural to read and easy to write, and has the added benefit of a lower learning curve for experienced Ruby devs.
