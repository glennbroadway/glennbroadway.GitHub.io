---
layout: post
title: Using an ISO-UK Vortex Race 3 on a Mac
---

When I saw the Vortex Race 3 mechanical keyboard I knew it was time for me to make the switch away from Apple's weird, flat little things that they ship with their Macs. I live in the UK so am used to a big Enter/Return key, and luckily Vortex do make a variety of layouts, including ISO-UK. It is not the same layout as the Apple Extended Keyboard though - Apple have their own keyboard layout which is a sort of mix of the US (ANSI) layout and the UK (ISO).

![Vortex Race 3]({{ site.baseurl }}/images/VortexRace3.jpg)

![UK vs US Keyboard Layout]({{ site.baseurl }}/images/UKvsUSKeyboard.png)
These are the main differences between ISO and ANSI.

![Apple's UK Magic Keyboard]({{ site.baseurl }}/images/appleUKMagic.jpg)
Apple's UK Magic Keyboard (formerly the Extended Keyboard I think).

So why am I writing this post? Well, it wasn't exactly easy getting the Vortex Race 3 working on my MacBook. It worked out of the box, to a degree, but I wanted the same symbol appearing on screen as is printed upon the key I press. If you compare the actual Apple keyboard above to the UK ISO layout above that, you can see that some keys are in non-standard places (the \| key for example, which is relocated nearer to the Enter/Return key by Apple). As you can see from the picture at the start of this article I switched out some of the keys for the multi-coloured alternatives that are supplied in the box, and I also installed the command ⌘ key and swapped its position with the Alt key's default location.

The Vortex Race 3 has an Apple mode (Fn+M) and whilst it does switch the position of cmd and Alt it also changes the behaviour of the Function keys. F1 to F6 have volume and media controls printed on them and I decided that I wanted to have all the keys perform the function that was printed upon them rather than having to remember the location of some symbols and functions. Here's how I managed to get it working.

## 1. Don't put the keyboard in Mac mode.

This ensures the media and volume keys do what's printed on them.

## 2. In System Preferences, under Keyboard, on the Input Sources tab add (and select) British - PC.

This fixes a few things, but not all of them. The #~ key (next to the Enter/Return key) now behaves as expected. But the \| key (to the left of the Z) key is swapped with the `¬ key (which is just below the Esc key).

## 3. Install and set up Karabiner Elements to fix the remaining issues

Why not just reprogram the keys using the built in functionality of the keyboard? Good luck with that. Maybe it was my ineptitude but I just couldn't get it to work. Anyway, to reprogram the keys you need to switch to Layer 1, 2 or 3, which means having a red, green or blue LED on under one side of the space bar. I didn't like this, so opted to go the software route.

I used Karabiner Elements to reprogram these keys:

![Karabiner Elements]({{ site.baseurl }}/images/karabinerElements.png)

It's important to select the correct keyboard from the _Target Device:_ dropdown at the top of the _Simple Modifications tab._ The last keys that needed swapping were _grave_accent_and_tilde_ and _non_us_backslash_. I also used Karabiner to swap _left_command_ with _left_option_, and to change _right_command_ to _right_option_.

## 4. Remap 1Password shortcut keys

I use 1Password to manage my passwords and it's set up for an Apple keyboard layout by default (I think). I made cmd+# the access key shortcut rather than cmd+\ which is awkward to type on an ISO keyboard.

## In Conclusion

I really like the Vortex Race 3. The 75% layout is perfect for me and the build quality is exquisite. I also love the design (although I think I prefer the older keycaps which had the symbols one above the other rather than at an angle). I've got Cherry MX Browns, but I think I'd like to try Clears at some point. I just never realised that buying a UK keyboard would mean so much research and work if you wanted to use it on a Mac. I'm sure there are mechanical keyboards designed specifically for the Mac, but I will occasionally use this on a Windows machine as well so I am happy.

Someone on Reddit described the Vortex Race 3 as looking like a keyboard out of school science lab from the 1970s - which is exactly why I like it.
