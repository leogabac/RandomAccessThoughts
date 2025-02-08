---
layout: post
title: "Windows 10 support is ending this year, should you switch to Linux?"
---

Yes, no, well... it depends.

## Windows 10 End of Life

Windows 10, the magnum opus (not really) of Microsoft before they veered into the complete mess that is Windows 11. A combination of aging hardware support, inconsistent design, and, most importantly, the removal of configuration options, the addition of bloat and ads no one asked for, and shameless data collection—no wonder Windows 10 maintained ~60% of the market share. However, Microsoft is finally ending support for it. If you're reading this, chances are you're debating whether to upgrade to Windows 11 or take this opportunity to switch to something else.

So, should you switch to Linux?

## It ain't that simple

I'm a Linux enthusiast. I own a ThinkPad and a MiniPC, I daily-drive Arch Linux, and I wear the most femboy-suggesting programming socks the world has ever seen. Contrary to what many (including my therapist) believe, Arch has given me the most solid desktop experience I've had since the Windows 7 days. Everything I use just works out of the box, and on the rare occasions it doesn’t, the Arch Wiki provides incredibly detailed instructions. As long as I carefully follow the steps, I can get things working in record time.

So, should you use Arch? Well, no. The key to that question lies in when I wrote _everything I use_. While I believe Linux is superior to Windows in many aspects, not everything supports Linux. Windows has dominated the desktop PC market for decades, so most software is primarily developed with Windows in mind, MacOS if the developers feel like it, and Linux only if there's a particularly persistent developer on the team.

If you're thinking about switching to Linux, you need to first consider your use case, the software you rely on, and whether Linux’s philosophy aligns with your workflow.

From my experience, the more _professionally_ you use a computer, the harder it becomes to switch to Linux. Here are a few examples based on people I know:

- **My mother:**
  She uses a browser to check her email occasionally and writes a document in Word maybe once every few months. She also connects an external hard drive to back up photos from her smartphone. Since she started using computers before cloud services existed, she still prefers local backups. She heavily dislikes subscription services and refuses to enter her card details online.

- **My sister:**
  She primarily browses the internet, watches YouTube, and doesn’t even use MS Office—Google Docs is free and more convenient for her. Since all her activities happen in the browser, she doesn’t need specific apps. She only plays games on her phone.

- **Friend A:**
  Digital Artist & Animator. Uses Adobe software and Autodesk Maya for 3D modeling.

- **Friend B:**
  Engineering Student. Works with finite-element modeling tools like COMSOL and ANSYS for his thesis. Also programs in Python and uses LaTeX.

- **Friend C:**
  The GAMER. Plays competitive games and firmly believes in PC gaming supremacy. Makes fun of Apple users.

- **Friend D:**
  The programmer. Uses C/C++ and python for his work. He only needs VSCode and plays single-player games on his free time.

So question for you, who do you think will have an easier time switching to Linux? Exactly, it depends. And the more specific you are, the harder it becomes. I could even put Linux Mint on my Sister's and Mother's laptop, with the same wallpaper and would probably not notice the change. So take into account that at the end of the day, your specific use-case will determine whether you should switch or not, and how difficult that task will be. Additionally, take into account that Linux is NOT Windows, and you should not expect it to be. It is a different OS, and you should have always in mind and there are many things that are not necessarily difficult, they are just different to what you are used to.

From this point onwards, I will assume you already decided to switch.

## The Choice of a Distribution

The truth is… absolutely nobody cares. Just pick something and start using it.

One of the best things about using a Linux-based OS is that there’s a distribution for everything. The worst thing about using a Linux-based OS is that... there’s a distribution for everything. This is both a strength and a curse—it showcases the sheer variety of possibilities, but for newcomers, it quickly becomes their worst nightmare, leading to _choice paralysis_.

When faced with too many options, we naturally want to pick the _best_ one, because choosing one means discarding the other $$n-1$$ alternatives. I’ve seen this a lot with undergraduate students obsessing over _the best book for learning X_ or _the best course for learning Y_. No shame in that—I’ve been there myself. But since I _have_ been there, I can confidently say that the best course of action in these situations is to just pick something and start. No amount of research will ever beat actually putting in the work.

Back to Linux distributions. If you don’t have _very specific_ hardware requirements, and you choose something from one of the major distributions, you’ll be fine. Linux distros generally fall into three categories based on their update cycle:

- **Stable**

Prioritizes reliability over cutting-edge features. Updates are infrequent but well-tested, making it ideal for servers or users who prefer a "set it and forget it" experience. Examples: Debian, Ubuntu LTS.

The popular choice in this category is Linux Mint, an Ubuntu-based distribution that focuses on ease of use, stability, and a familiar desktop experience, making it a great option for users transitioning from Windows. The defaults of Linux Mint make Window users feel _at home_.

- **Rolling release**

Continuously updated with the latest software, meaning you always have the newest features (and sometimes, the newest bugs). Great for enthusiasts who want bleeding-edge software, and good for the latest hardware. Examples: Arch Linux, Endeavour OS, openSUSE Tumbleweed.

The popular choice in this category is usually Arch Linux. However, Arch is typically _not_ for newcomers. Much as I love it, the ISO image greets you with nothing but a black screen and a terminal, expecting you to read the documentation and build your OS (almost) from scratch.

A more user-friendly alternative that I often describe as "prepackaged Arch" is EndeavourOS. It’s essentially Arch with an installer and sensible defaults, making it a great option for those who want the Arch experience without the manual setup.

- **Something in-between**

Balances stability and up-to-date software by providing periodic updates without fully committing to a rolling-release model. Examples: Fedora, Ubuntu (non-LTS), Manjaro.

The popular choice in this category is Fedora. People seem to really like it—I haven't used it myself, but you could give it a try.

> **Takeaway:**\
> If you don’t know what to choose, just try Linux Mint.

There will always be some intense Redditor telling you that Linux Mint isn’t the best choice for every use case and that, based on your specific Bluetooth adapter or graphics card, you’d be better off with _X_ distro. And just like that, we’re back to the paradox of choice.

Stop overthinking it. _At least_ give Linux Mint a try, check that everything works in the live ISO, and actually _use_ it.

> **Note:**\
> If you have a PC with the latest hardware, skip Mint and try Fedora. Its more frequent update cycle means it’s more likely to have better support for newer hardware.

## The Desktop Environment

Something important to distinguish is the difference between the distribution and the desktop environment (DE). The desktop environment determines the graphical aspect of your desktop experience and often includes a set of basic tools. Most distributions come with a default DE but also offer _spins_ or _flavors_ featuring other DEs.

Here are the major desktop environments and some distributions that use them:

- **GNOME**

Best described as MacOS-like. A modern, and touch-friendly DE with a focus on simplicity and workflow efficiency. Used by Fedora, Ubuntu (default), and Debian.

- **KDE Plasma**

By default, very Windows-like. A highly customizable and feature-rich DE that balances aesthetics with performance. Used by KDE Neon, Kubuntu, openSUSE, and Fedora KDE.

- **XFCE**

A lightweight, traditional desktop with low resource usage, making it ideal for older hardware. Found in Xubuntu, Manjaro XFCE, and Debian XFCE.

- **LXQt**

An ultra-lightweight DE that provides a basic but functional experience with minimal resource consumption. Used by Lubuntu and Fedora LXQt Spin.

- **Cinnamon**

A Windows-like DE that provides a familiar and user-friendly interface. The default for Linux Mint, and developed by the same team.

> **Takeaway:**\
> You can install almost any DE on any distro—you don’t need to distro-hop just to try them. The DE is just one part of a distro, not the whole distro.
>
> **Note:**\
> Tiling Window Managers exist, but that is a whole topic on itself that needs a separate discussion.

## The GAMES

For years, gaming on Linux was a joke—if you were serious about playing games, you used Windows. That was just the reality. But things have changed dramatically, and Linux gaming is now in the best state it has ever been.

The biggest game-changer (pun intended) has been _Proton_, a compatibility layer developed by Valve (thanks Gabe) that allows Windows games to run on Linux through Steam. Proton, which is based on Wine, translates Windows API calls into something Linux understands, making thousands of games playable with minimal effort. Thanks to this, you can install and play many games on Linux just as easily as on Windows.

But Proton isn’t the only thing pushing Linux gaming forward. The rise of _Vulkan_, a modern graphics API, has given Linux-native games a performance boost, making them competitive with their Windows counterparts. More studios are supporting Linux directly, and open-source projects like _DXVK_ (which translates DirectX calls to Vulkan) have drastically improved performance for games that don’t have native Linux support.

Another major factor is Valve’s _Steam Deck_, which runs a Linux-based OS (SteamOS). The Deck’s success has encouraged more developers to ensure their games work on Linux, either through native ports or better Proton support. This has had a ripple effect on desktop Linux gaming, improving compatibility across the board.

That said, Linux gaming isn’t perfect. Anti-cheat software like _Easy Anti-Cheat (EAC)_ and _BattlEye_ still causes problems, preventing some competitive multiplayer games from running on Linux. Additionally, while performance is great in many cases, some games still require tweaking to work correctly.

If you mostly play single-player or indie games, Linux is a fantastic option. If you play competitive shooters or niche Windows-only titles, your experience may vary. But with how quickly things are improving, Linux gaming is no longer an afterthought—it’s a real, viable alternative.

> **Note:**\
> Proton needs to be manually enabled in the Steam settings.
> And yes, for those of you wondering. External controllers work out-of-the-box.

## Software

Not all software is available on Linux, and not all software works the same across different distributions. Generally speaking, Free and Open-Source Software (FOSS) is available on most (if not all) distributions, but proprietary software has limited support. At this point, you’ll need to accept that you may have to use alternatives to the software you’re used to—whether it’s an office suite, video editor, drawing tool, photo editor, or PDF reader. Fortunately, there are plenty of options. Here are some alternatives:

- **Office Suite**

  - Alternative: **LibreOffice** (FOSS), **OnlyOffice** (FOSS), **WPS Office** (Freemium)
  - What I use: OnlyOffice. It works most of the time, although I am still mad that it still does not support GIF and Video playback on presentation mode.

- **Video Editing**

  - Alternative: **Kdenlive** (FOSS), **DaVinci Resolve** (Proprietary), **Shotcut** (FOSS)
  - What I use: Kdenlive, I still haven't been able to make DaVinci Resolve work, at this point it feels like a gamble, and works better for NVIDIA cards.

- **Drawing & Illustration**

  - Alternative: **Krita** (FOSS), **Inkscape** (FOSS), **MyPaint** (FOSS)
  - What I use: Krita for drawing and Inkscape for vector graphics.

- **Photo Editing**

  - Alternative: **GIMP** (FOSS), **Darktable** (FOSS), **RawTherapee** (FOSS)
  - What I use: GIMP from time to time.

- **PDF Reader & Editor**

  - Alternative: **Okular** (FOSS), **Evince** (FOSS), **Master PDF Editor** (Freemium)
  - What I use: Evince, it is the default in GNOME, and works great. I also use Zathura for LaTeX.

- **3D Modeling & Animation**

  - Alternative: **Blender** (FOSS), **FreeCAD** (FOSS), **Wings3D** (FOSS)
  - What I use: Blender from time to time.


## Package Managers  

One of the biggest differences between Windows and Linux is how software is installed. On Windows, you typically download `.exe` or `.msi` files from websites, run an installer, press _next_ in desperation until it is installed, and manually update programs. In contrast, Linux distributions use _package managers_—centralized tools that handle installing, updating, and removing software in a more efficient and secure way.  

A package manager pulls software from official repositories (repos) maintained by the distribution. These repos contain precompiled applications, system libraries, and dependencies needed for software to run properly. Instead of hunting for downloads on random websites, you simply run a command or use a graphical tool to install what you need.  

Beyond traditional package managers, there are universal packaging formats that work across different distributions:

* **Flatpak:** A sandboxed system that allows applications to run with all their dependencies, ensuring compatibility across distros. Used heavily by Fedora.
* **Snap:** It is closed-source and people hate it.
* **AppImage:** A portable format that doesn’t require installation—just download and run the file, similar to .exe files on Windows.

## The TERMINAL

For many newcomers, the terminal is the most intimidating part of using Linux and the reason they avoid it. Why on earth should one use a terminal when we spent decades developing graphical tools?  

First, it is not strictly necessary to use a terminal. In major user-friendly distributions, there will always be a graphical tool that accomplishes the same task. However, the more specific you want to be, the more likely it is that you will eventually need to use the terminal, at least for debugging. Furthermore, once you get used to it, you’ll realize it’s an incredibly powerful tool that allows you to do things more efficiently than a graphical interface ever could.  

Also, the terminal eventually becomes a _symbol_ of your unique identity. Terminal customization is one of the ways in which users express themselves, adding a personal touch to their system. Whether it's choosing a minimalist prompt, using a colorful shell like `zsh` with `oh-my-zsh`, or configuring `neofetch` to display system info in style, your terminal setup reflects your workflow and personality.  

## Windows is NOT Linux

Here, I borrowed the title from [this great article](https://linux.oneandoneis2.org/LNW.htm). If you have the time, I really encourage you to read it.  

The key takeaway? **Linux is not a drop-in replacement for Windows**. Many people expect Linux to behave like Windows with just a different UI, but that’s not how it works. The philosophy, system architecture, and software ecosystem are entirely different. If you're switching to Linux, embrace the change instead of fighting it.  

## Do NVIDIA Cards Work?

Mostly, yes.

AMD graphics cards are supported by open-source drivers that are included directly in the Linux kernel. NVIDIA cards, however, use proprietary drivers that need to be manually installed. Yes, they work, but you’ll need to do a little extra setup:  

1. **Google your specific NVIDIA card model** to check for compatibility.  
2. **Find the correct package for your distribution** (usually named something like `nvidia-driver` or `nvidia-utils`).  
3. **Install it** using your distro’s package manager.

In fact, this is basically the same workflow to install ANYTHING on Windows, why are you so worried about it?

If you’re using Linux Mint or Ubuntu, there’s a graphical tool (`Driver Manager`) that can handle this for you.  

For Arch-based distributions, the [Arch Wiki page](https://wiki.archlinux.org/title/NVIDIA) provides detailed instructions on how to set up the drivers properly.  

One major issue with NVIDIA cards on Linux is Wayland support. While AMD GPUs work well with Wayland, NVIDIA’s drivers have historically had poor support, leading many users to stick with X11 for better stability. Recent driver updates have improved Wayland compatibility, but if you run into issues, switching to X11 might be the best workaround.  

## Final remarks

Switching to Linux is a decision that depends entirely on your needs and expectations. If you’re tired of Windows’ aggressive updates, telemetry, and bloat, Linux offers a customizable, privacy-respecting alternative. However, it’s not a drop-in replacement—you’ll need to adapt, learn new workflows, and sometimes troubleshoot issues.  

The good news? Linux has never been more accessible. With distributions like Linux Mint and Fedora offering smooth out-of-the-box experiences, and tools like Proton making gaming viable, there’s never been a better time to try it. If you’re curious, grab a USB stick, boot into a live ISO, and see if it works for you.  

At the end of the day, Linux isn’t for everyone, and that’s okay. The best operating system is the one that lets you work (or game) without frustration. Whether you switch or not, understanding Linux will give you more control over your computing experience—and that alone is worth exploring.


## I Use Arch (btw)

The sacred mantra of Linux users.  

If Arch is difficult, why do I use it? **Because I like it.** I’ve been tweaking computers and using the terminal since I was 12, when I hosted my own Minecraft servers to play with friends. I enjoy "playing" with my system, customizing it, and occasionally reinventing the wheel by making small tools that streamline my workflow. When I’m bored on a Thursday night with some free time, I experiment—not necessarily with Linux, but with IT-related projects in general. More often than not, being on Linux makes these tasks easier.  

For example, the other day I needed to merge two PDFs. I could have used ILovePDF, [Stirling PDF](https://www.stirlingpdf.com), or simply run `pdftk` in the terminal. Instead, I wrote a simple Bash script that launches `yazi` to select PDF files and merges them interactively with `pdftk`. Now, every time I need to do this, I use my script. It’s rustic and imperfect, but I enjoy it __because I made it__ ([here's the code](https://github.com/leogabac/dotfiles/blob/main/leotools/.scripts/tui/pdfmerge_yazi.sh), btw).  

In [another blog post](https://leogabac.github.io/RandomAccessThoughts/finally-neovim-config/), I wrote about making my own Neovim configuration. I even have a simple [Python utility](https://github.com/leogabac/dotfiles/blob/main/leotools/.scripts/pdf_comment_merger.py) that merges comments from multiple sources of the same PDF (useful if you send a manuscript for review to multiple advisors). It color-codes the comments based on their source file. The code is probably garbage, but __it’s my garbage__—and that’s what makes it fun.  

Even this blog—I could have used WordPress, Medium, or some other dedicated blogging platform that makes life easier (usually for a price). In fact, I did start with WordPress, but I wanted to figure out how to host the site using GitHub Pages, set up Jekyll, customize it a bit, and have a functional workflow that used Markdown for writing.  

The same goes for my personal notes. I used [Obsidian](https://obsidian.md) for a year, and while it’s great, I want to move away from it—not because of any major flaws, but simply because I want to self-host a personal wiki, experiment with different setups, and write everything in Markdown using my custom Neovim configuration. I just find a lot of joy in this kind of tinkering. And for people like me, **Arch is a great place to be.**  

On top of being too much of a nerd for my own good, the [Arch Wiki](https://wiki.archlinux.org/title/Main_page) is excellent, with up-to-date documentation for almost everything. `pacman` is a fantastic package manager, and when something isn’t in the official repositories, the [AUR](https://aur.archlinux.org) has you covered. Between the official repos and the AUR, the Arch community ensures you’ll rarely find yourself missing software.  

