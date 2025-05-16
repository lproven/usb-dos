# DOS live USB images with tools for writers

## What this is

This repo contains [downloads](https://github.com/lproven/usb-dos/releases) of compressed disk images of bootable USB keys.

Version 1 is based on several upstream FOSS projects, plus some ancient DOS freeware applications. The idea is to provide a complete, easy-to-use, distraction-free environment for writers. It is set up for English with provision for US and UK keyboard layouts. If you want other translations, I welcome help! 

To get your work off the key, just insert the key into a computer that's already running any more modern OS than DOS. 

You _cannot_ go online with the keys and there are no Internet tools. There are also no games included. Both are intentional.

## What it contains: SvarDOS plus a menu launcher and a choice of freeware writing tools

The operating system is [SvarDOS](http://svardos.org/), the latest release as of January 2025. For source code for the OS, go to the SvarDOS website.

There **are no build scripts or source code here.** I did not use any. I did not compile anything at all. What I did was take pre-existing compiled code from SvarDOS and other projects, install it, and configure it. Then I worked out [how to make](https://liam-on-linux.livejournal.com/50416.html) bootable media in VMs, imaged those DOS-bootable USB media, and put the downloads here.  

The main writing-tools key has a simple launch menu using the DOSShell menu from PC DOS 2000, which back in 2021 I made into a Virtualbox VM and [published on my tech blog](https://liam-on-linux.livejournal.com/78306.html).

It contains three word processors, two outliners, three plain-text editors, and some other apps. These alls are all explicitly freeware or products from companies that no longer exist.

There is a more complete list of components here:

[What is (and isn't) included and how it works](https://github.com/lproven/usb-dos/wiki/What-is-%28and-isn%27t%29-included-and-how-it-works).

## What you need

1. A PC that is able to boot DOS. ***NOTE:** UEFI-only PCs cannot boot DOS.*
2. A PC that is able to boot from USB\*.
3. *Any* x86-32 processor, and 1MB or more of RAM. This system will run usefully on a 35-year-old PC.

That's all. You _do not need a hard disk._ It will work fine without one, or with a drive that's encrypted or otherwise unreadable.

You do not need any other OS on the target PC.

\* There are ways around that. You can also write the image to a CF card and use that instead of an EIDE hard disk.

More info: [System Requirements](https://github.com/lproven/usb-dos/wiki/System-Requirements)

## How to use it

1. Download it from the [Releases page](https://github.com/lproven/usb-dos/releases), which is in the sidebar on the right. 
2. [Write it to a key](https://github.com/lproven/usb-dos/wiki/How-to-write-the-image-to-a-USB-storage-device).
3. [Boot your computer from the key](https://github.com/lproven/usb-dos/wiki/How-to-boot-from-your-new-DOS-USB-key). 

That's it. There is no installation process.

There are some more instructions in the [USB-DOS wiki](https://github.com/lproven/usb-dos/wiki).

**NOTE** You [*must* have legacy boot enabled](https://github.com/lproven/usb-dos/wiki/System-Requirements) in your firmware.

## Questions, hints, suggestions? 

By all means use Github issues to tell me about problems, make suggestions, etc. You can also find me on [Bluesky](https://bsky.app/profile/lproven.bsky.social), [Mastodon](https://social.vivaldi.net/deck/@lproven/), [~~Twitter~~ X](https://x.com/lproven), [Dreamwidth](https://liam-on-linux.dreamwidth.org/) and [other places](https://about.me/liamproven).

## Espresso your gratitude?

If you like this or find it useful, then by all means please do [Buy Me A Coffee](https://buymeacoffee.com/lproven). Thank you!
