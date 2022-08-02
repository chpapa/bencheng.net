+++ 
draft = false
date = 2022-08-02T19:22:07+08:00
title = "Software tools I use personally daily in 2022"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
+++

Recently I found that I have switched almost all software I use daily personally, so thought it would be an interesting idea to share what software I use and why.

Here are what I have switched in a quick glance:

| Type      | 2017                        | 2022            |
| --------- | --------------------------- | --------------- |
| Email     | mutt                        | Superhuman      |
| Notes     | Evernote + Github (me repo) | Obsidian        |
| Task List | Things                      | SkedPal         |
| Browser   | Firefox                     | Arc             |
| Scheduler | x.ai                        | Calendly                |

## Email
In 2017, I used mostly mutt on terminal for email, when I'm on the go I use [termux](termux.dev) for that. It works well especially I have been using Blackberry / [Gemini](https://store.planetcom.co.uk/collections/devices) mostly, keyboard shortcuts makes my daily habit of inbox zero easy.

I think partly due to giving up coding and terminal, I was tempted to try out Superhuman when I saw it online.

TBH it is so overpriced, but it comes with a lot of keyboard shortcut so I can still clean my inbox without my hand leaving the keyboard. There are a few handy features like Snippet (that works 100% with keyboard), check calendar availability automatically, and create calendar event with keyboard shortcut on-the-fly as well.

## Notes
I used Evernote mostly for everything, and maintain a Github repo for my dot files and some textfiles (e.g. work log and daily journal) in 2017 (and a few company high level doc until I moved them to Notion when my company switched from Quip to Notion as knowledge base).

Only until very recently, I learnt about [Obsidian](https://obsidian.md) -- I wasn't impressed at first, even after a few of my [Oursky](https://oursky.com) colleagues show me about it -- I thought it is just another markdown editor.

Only after I played around, I found that the beauty of it is how customisable it is, and the rich ecosystem around it.

For example, I really enjoyed using a few community plugins like:
- `DataView` which can group multiple markdown files with yaml metadata into table view with really flexible query languages
- `AdvancedTable` which is really handy for creating table in markdown languages
- `Excalidraw` which embed a great wireframe / graph editor

I also look forward to try out other plugins like `AdvancedSlides` and used a few minor plugins such as `Relative Line Numbers` (to complement the vim-mode); Obsidian comes with some surprise as well -- e.g. it automatically convert my existing .md file's [mermaid](https://mermaid-js.github.io/) into images at preview.

I also love the `Open daily note on startup` options as well -- so every time I start Obsidian, it show up my daily journal for quick notes jotting etc.

I believe there are a lot for me to explore, e.g. one features I don't particularly get is the knowledge graph and backlinks

## Task Lists
This is where I switch tools most frequently, during my time at CUHK and HKU I was using a notebook daily journal for tasks and planning; Tried dozens of todo software, been using [RTM](https://www.rememberthemilk.com/) (oh god it's still there! Love how bootstrapped, non-VC funded software are way more reliable!), [OmniFocus](https://www.omnigroup.com/omnifocus/), [Todoist](https://todoist.com) (so I can access on-the-go via Android), and [Things](https://culturedcode.com/things/) very briefly lately.

Recently I run into [Skedpal](https://skedpal.com) after trying out Motion for a few weeks, unsatisfied and referred by friends. Skedpal (apparently I'm using V3) is similar to Motion in a way it automatically schedule tasks into your calendar, and have a really nice outline-based tasks editor with reasonablely well "natural language processing" (basically it's like you can use `#Management` to put the tasks under Management heading, or `/30mins` to tag the tasks with my 30 mins work schedule flexible pre-set)

Motion is way better in auto-scheduling (You have to click `Update Schedule` in Skedpal all the time), and have the concept of "Start a task", "Complete a task" so you can stick with it during your day easily (and basically your calendar become a time log of what have you done during the day after a full day of work); however the UX is really screwed up (no keyboard shortcut, I even have a few mins of latency after I check off a task!)

Skedpal seems like a single developer product, and I heard from the developer a similar feature to start / complete tasks and automatically schedule when you complete / missed a tasks is on the backlog (of distinct future... well), looking forward to it.

## Browser
I've been using Firefox -- to support the only alternative to Chrome recent years. This is where I'm not so proud of -- I have been using [Arc](https://thebrowser.company/) lately and kinda enjoy it. Mainly due to two reasons:
1. `Cmd-T` brings up a command prompt and I can do most things on the keyboard (with Chrome extension like vimum)
2. If you fav and pin a tab, it never reload, and you can always jump to them with keyboard shortcut like `Cmd-[1-9]`; I loaded Google Calendar, Skedpal, Basecamp and Notion on it, and it makes my work life wayyy better.
The only problem is, Arc is based on Chrome, that's why I'm not proud of. I might one day invest some time to see how can I customise Firefox into these behaviour.

## Scheduler
I used x.ai to generate a link others can schedule a time slot with me. However x.ai was a failed startups and never monetise (it promises to manage your schedule with AI, yet it failed to deliver and became... yet another calendly); So after x.ai shut down I switched to calendly.
