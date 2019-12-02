+++ 
draft = false
date = 2018-05-20T19:05:34+08:00
title = "Review after two weeks with Gemini Phone"
description = "Supporting crowdfunded PDA phones in 2018"
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
+++

So it is two weeks after using the [Gemini Phone](https://www.indiegogo.com/projects/gemini-pda-android-linux-keyboard-mobile-device--2) as my work phone and I would love to write a review on what it’s like using a PDA phone in 2018.

Gemini is an Android phone with the [Psion 5](https://en.m.wikipedia.org/wiki/Psion_Series_5) keyboard (at least that was how it marketed). As a keyboard lover (I used the Palm Treo for a long time, loved the Blackberry Passport and have been using Blackberry Keyone as my work phone until last year) I couldn’t resist backing the Indiegogo project.

{{< figure src="/posts/images/gemini-mutt.webp" caption="Mutt on Termux">}}

## How do I use a work phone?

Before I list out my feelings about the Gemini, I want to explain a bit about how I use my work phone to give some background on why I might love/hate something.

* I thumb-type a lot on the road. I zero my inbox when I am walking from home to work, when I am on the commute, etc.
* I use my work phone mostly for: Email > Whatsapp/Telegram/Slack > Google Docs/Google Sheets/Quip/Trello/Basecamp > Post Tweets > Web Browsing
* I almost never talk over the phone, so essentially what I need is a 4G PDA

## So how I feel about it?

* I can type on table everywhere with it finally — I do have an iPad Pro with a Smart Keyboard, but it is still too large, so I tend not to bring it on the road. Gemini is always in my pocket so I can put it on my meeting tables, breakfast table, etc. Plus I actually read more on the Gemini (work phone) than my iPhone X (play phone) now as I can read during my breakfast time without holding one phone with my hand. Gemini does obsolete my iPad Pro since now I either bring along my MacBook Pro if I expect to work a lot on the road, or I am good with using Gemini both as phone and my mini-tablet.
* The hardware is solid (for an Indiegogo project) — my experience with crowdfunded electronics projects is terrible: father.io was no fun at all. XStylus Touch is the worst stylus I ever had. Hydradock doesn’t work for 4K video and was unreliable. Remix is a really slow unusable computer. Darts Connect software doesn’t work. My Textblades still haven’t shipped… Credit to Planet Computer for delivering my first crowdfunded electronics project which is actually usable.
* I thought MediaTek X27 would be too slow. I thought that only charging from one side of the USB port would drive me nuts. It turns out the Android is fast enough for everyday use, and the battery survives over a day for me which means I don’t need to do the kind of charging at only one of the two USB-C port.
* The keyboard feels great to type on — I am typing this review on Gemini. Frankly, the keyboard feedback feels even better than my MacBook Pro with Touch bar (sigh!), having said that…
* My first problem with Gemini is the keyboard layout, I still can’t remember the symbols positions (many of them require Fn+X key combinations). That’s the thing I miss Blackberry Keyone and Passport the most. For some reason, I could memorize and touch type on both phones within a few days of practice but can’t on the Gemini. I didn’t realize how much work Blackberry put into optimizing the keyboard layout until now.
* I hate the built-in App Bar. It is a good idea except it pops up every time I open the phone, so I uninstalled it.
* Thumb typing is far from perfect. The device is too big for thumb typing, it is possible, but not very comfortable.
* Gemini only supports Pump Express for fast charging, and can only charge from a USB-A to USB-C cable, which is really annoying. I already got so many USB-C to C charger and cables, and now they can’t be used with the Gemini.
* The on-boarding experience is tricky, you need to learn how to set the keyboard layout before typing is a big sign of “this device is not for the average user.” My experience with Android was either Google Pixel/Nexus and Blackberry is that both have excellent default software and settings that I can use. With Gemini, I actually had to learn a lot about Launcher and Keyboard software (More below)
* The space bar doesn’t register the click when it is not tapped in the center
* Android apps don’t always work in landscape mode.

Now here are a few things I really hope they will fix in a Gemini 2 (if there is one) :

* Don’t use MediaTek SoC, it is known to be full of malware. For example, there is a mtklogger running on the phone which is basically a keylogger. Come on…
* Support one of the biometric authentications such as fingerprint. It is really troubling to type a long password for things like Password Manager. (However with MediaTek SoC on Gemini I didn’t dare to install my password manager on the phone anyway)
* Either improve the keyboard layout or backlight. Usually, I don’t care about keyboard backlight, I get familiar with keyboard layout quickly so even on a flight I can type with backlight switched off. Gemini is the first keyboard I have trouble typing in a dark environment.

Something people might care about, but I don’t:

* Secondary screen to show who is calling,.I don’t care as I don’t make calls. Being able to customize the color of the LED will be good enough.
* Better camera. I don’t take photos at work, so the front-facing camera is enough.

## Software Tweeks

My previous experience of Android was either stock image from Google Pixel or Nexus or Blackberry. Surprisingly even Blackberry has excellent default software, so I never bother with the built-in Launcher and keyboards. With Gemini I had to experiment myself and here is what I found:

* Nova Launcher is great. The default Launcher in Gemini won’t even let me remove the Google search bar. Nova is customizable for the right density.
* SwiftKey is a great keyboard. It has shortcuts key to switch between English and Chinese input. I also love how the Changjei(Quick) Chinese input supports continuous input of code, and it will try to guess the words and sentences, which I thought was unique on Blackberry.
* Built-in and Google Calendar doesn’t work well with landscape mode in week view. Turns out [Business Calendar](https://play.google.com/store/apps/details?id=com.appgenix.bizcal) is a great app for that.

Here are some things I strongly suggest other Gemini owners to tweak:

* Change the screen DPI, the default one is too large and doesn’t show enough information on its horizontal screen. I changed the smallest width to 423dp under the Developer Option.
* Hide the default navigation bar. It doesn’t work as a good keyboard shortcut of Esc (back), Fn+D (home) and Fn+A (switch apps) and gives you more screen space.
* Use a firewall software to block the Android system and MediaTek system process from access to the Internet.
