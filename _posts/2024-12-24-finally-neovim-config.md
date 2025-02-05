---
layout: post
title: "I Finally Made My Neovim Configuration—After Updates Tried to Destroy It"
---

In the everlasting battle of terminal text editors between the Emacs gang and the Vim gang, I firmly stand with the Vim side—well, Neovim, to be precise. Switching to Neovim felt like diving headfirst into a deep rabbit hole of endless possibilities: learning Vim bindings and configuring almost everything from scratch.

Before Neovim, I was a VSCode enthusiast. And before VSCode, I used Atom as my go-to IDE. I had grown accustomed to editors that came preloaded with features I didn’t even think about—syntax highlighting, file trees, LSP integration, and code snippets. Neovim, by default, is none of that; it’s simply a text editor.

Following a suggestion from The Primeagen, I decided to test the waters by enabling Vim mode in VSCode to get familiar with the keybindings before committing fully. That experiment, however, turned out to be a disaster. The experience was sluggish and unresponsive. The slight delay in typing was maddening, making an already challenging adjustment even worse.

After about five minutes of frustration, I had an epiphany: why not just go all in? Instead of struggling with a subpar imitation, I decided to fully embrace Neovim. It was a leap of faith, but one that quickly paid off.

## The choice of a distribution

Since I had no idea how to set up Neovim from scratch, I decided to start with a distribution. My first choice was [NvChad](https://nvchad.com/), which came highly recommended for beginners. Unfortunately, my experience was far from smooth. On a fresh install—just cloning the repo—I was greeted with a flood of Lua errors.

It wasn’t a _me_ problem, a friend who had also just started with Neovim encountered the exact same issues. After spending way too much time trying to figure it out, I finally gave up. It was usable, and I used NvChad for like a month, but I got tired of being greeted with errors. I hope these are fixed by now.

That’s when I decided to try [LazyVim](http://www.lazyvim.org/) instead. It felt like a breath of fresh air—a smoother experience that just worked out of the box. LazyVim was great—a joy to use and, with minimal setup, it completely replaced VSCode for me. Everything just worked, and it allowed me to focus on coding rather than fighting with configurations.

However, there was one issue: the Python LSP setup was way too opinionated. I’m sorry, but I really don’t give an f about the absurd number of style warnings that pycodestyle insists on throwing at me. Sure, I get that it’s meant to be helpful, but as an opinionated programmer myself, I’m not here for that level of nitpicking.

For reference, I’m not a software developer—I’m a computational physicist. I write code in various languages to solve physical problems, and 95% of the time, I’m the only one who has to deal with it later. While I try to follow good practices, like keeping my code organized and documented, my focus is on producing scientific results.

Anyhow, everything was going smoothly with LazyVim until I decided to use LaTeX—a tool I like and use a lot. It had been a while since I last worked with it; for personal notes, I mostly use markdown. But now I needed to write a paper, and that meant it was time to set up LaTeX inside Neovim.

## LaTeX, my best (and worst) companion
The process of setting up LaTeX in Neovim is pretty straightforward… if you have a minimal idea of what you’re doing and actually Read The Fucking Manual (RTFM) for LazyVim. I installed [vimtex](https://github.com/lervag/vimtex), which provides several useful features. At its core, it enables document compilation directly within Neovim.

For most people, this setup would be sufficient. But with a little extra effort, you can take things further. By setting up snippets and autocompletion, you can streamline common tasks like managing references or inserting frequently used code blocks. These small improvements make working with LaTeX feel less tedious and significantly more efficient.

At the time, LazyVim used [nvim-cmp](https://github.com/hrsh7th/nvim-cmp) for autocompletion, so I added the corresponding plugins to use vimtex as a source. On top of that, I set up [LuaSnip](https://github.com/L3MON4D3/LuaSnip) as my snippet engine, anticipating that I’d want to create custom snippets in the future. This setup is fairly simple—once you know what you’re doing. Unfortunately, I didn’t. I wasted quite a bit of time fumbling around because I hadn’t bothered to properly RTFM. Lesson learned: a little upfront reading can save a lot of troubleshooting later.

## Updates: The Gift that Keeps on Giving… Chaos
With a new [LazyVim release](https://github.com/LazyVim/LazyVim/releases/tag/v14.0.0) came a bunch of breaking changes. To summarize, they made blink.cmp the default autocompletion engine and moved nvim-cmp to the Extras section. This change completely broke my LaTeX setup.

If you’re not a moron and actually read the breaking changes when updating—along with the documentation for [LazyExtras](http://www.lazyvim.org/extras)—you’ll find that it’s not such a big deal. The maintainers provided clear ways to revert back to nvim-cmp and restore the functionality of everything that was moved.

Unfortunately for me, I didn’t read the release notes right away, which led to unnecessary confusion. It’s another reminder of why **RTFM** is always sound advice when working with tools like this.

## The epiphany
But then I asked myself: Do I really want to keep fixing my editor because of someone else’s decisions? Sure, the LazyVim devs have their reasons for making changes, but I didn’t want to be forced into dealing with those decisions unless I actively chose to. After all, I’ve wanted to create my own Neovim configuration for a long time. Perhaps now was the time to make that leap.

It wasn’t trivial, but it wasn’t particularly difficult either. I followed [Henry’s tutorial](https://www.youtube.com/watch?v=KYDG3AHgYEs), and it was absolutely fabulous. He did an excellent job explaining how lazy.nvim (the plugin manager) works and how to assemble all the pieces.

Once I completed the tutorial, I had a pretty functional setup. From there, I modified keymaps, added my LaTeX setup, configured LSP for the languages I use, and explored LazyVim’s GitHub repository to see what features I might have missed. I left out many features that weren’t necessary for me, focusing only on what I needed and enjoyed.

This entire setup process took me about a day. It may seem like a lot of effort, but it was totally worth it. Now, I truly know my editor because I built it from the ground up. Along the way, I learned a lot and, in fact, I appreciate LazyVim even more now that I understand how it works.

When the time comes to add/remove/update features, it will be much easier because I know exactly how every piece of my setup fits together.

If you’re hesitating like I did, don’t. Just do it. It’s worth your time.
