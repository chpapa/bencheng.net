+++
draft = false
date = 2026-01-22T19:23:22+08:00
title = "Why AI Agents Might Finally Solve the Data Ownership Problem"
description = ""
slug = ""
tags = []
categories = []
externalLink = ""
series = []
mastodonToot = "https://oursky.social/@bencheng/115955667266094026"
+++

# Why AI Agents Might Finally Solve the Data Ownership Problem

Digital rights advocates have fought for data ownership for over thirty years. From proprietary file formats in the 1990s to SaaS platforms storing everything on remote servers, the pattern repeats: users create data, companies control it.

This matters beyond convenience. For businesses, operations become hostage to vendors who may raise prices, stagnate, or disappear. For individuals, personal information, creative work, and digital life sit on servers outside their control.

Solutions exist. Open file formats. Local-first architectures. The Data Centric Manifesto's clear principles. Yet despite decades of advocacy, the best software experiences still come from cloud services that lock data away.

I think this is about to change. Not through technical breakthrough, but because AI agents are shifting economic incentives. For the first time, building software that lets users own their data is becoming economically viable.

## A Brief History of the Data Ownership Fight

The fight for data ownership has gone through phases.

In the 1990s, the battleground was file formats. Microsoft Office, Adobe, proprietary databases. Data lived on your computer but was locked in formats only specific software could read. The open formats movement pushed back with ODF and open standards.

That fight made progress. By the 2010s, SaaS changed everything. Documents lived in Google Docs, notes in Evernote, company wikis in Confluence. Data sat on someone else's servers, exportable only if they allowed it.

Self-hosting, once the default, became rare, then unavailable. The direction was clear: your data belongs in their cloud.

## The Personal Cost of Lock-In

I've lived this pattern twice.

For years I kept personal notes in Evernote. Best tool for the job at the time. Then the company stagnated. No new features, rising prices. Years of notes sat trapped in a service that no longer served me. I eventually moved to Obsidian. The migration was painful, but now my notes are actually mine.

At my company Oursky, we built internal documentation in Quip. Then Salesforce acquired Quip, development stalled, bugs piled up. We migrated to Notion. Six months of team coordination, document review, manual format fixes. Six months just to move our own data.

And I can already see the same pattern forming with Notion.

This isn't about bad actors. Even well-intentioned companies shift priorities when investors demand returns, or simply shut down. When data lives in their system, their fate becomes your problem.

## Why SaaS Economics Work Against Users

The problem isn't malice. It's incentives.

In traditional SaaS, your data is the moat. The harder it is to leave, the more defensible the business. Lock-in isn't a bug. It's the model.

FusionAuth, a deliberately bootstrapped company, has [written about this](https://fusionauth.io/blog/fusionauth-vc-free): VC-backed companies run at losses to hit growth targets. When growth stalls or funding dries up, users bear the consequences.

Even companies that want to do right by users face pressure. Features that increase lock-in get built. Export tools sit at the bottom of the backlog.

Few companies choose a different path. Obsidian is one, staying small, bootstrapped, building a great tool on plain local files. But this means walking away from profit-maximizing strategies. Most won't.

## The Efforts That Haven't Won (Yet)

Digital rights advocates and technologists have built alternatives for years.

The [Data Centric Manifesto](https://datacentricmanifesto.org) articulates clear principles: data should be self-describing, expressed in open formats, independent of any application for meaning. Applications should visit the data, not own it.

[Local First Software](https://www.inkandswitch.com/local-first) essay makes the case for software that works offline, syncs across devices, and keeps data under user control. They've built working technology too. CRDTs that enable real-time collaboration without central servers.

These ideas are sound. The technical foundations exist. Yet the best user experiences still come from traditional SaaS. Why?

Partly because the technical challenges remain hard. Implementing CRDTs is genuinely difficult. But the deeper problem is economics. There's no strong incentive to build this way. Why invest in portability when lock-in protects revenue?

## AI Agents Change the Economics

In a [previous post](https://bencheng.net/posts/ai-agents-are-a-new-form-of-software/), I argued AI agents are becoming a new form of software. This has implications for data ownership.

AI agents shift who holds the power. Data remains valuable, but users can now build and customize their own logic and workflows using natural language. You no longer need to accept whatever features the vendor prioritizes. You can shape the system yourself.

This changes what customers demand. When users can easily build on top of their own data, portability becomes almost mandatory. Why choose a platform that locks data away when an open alternative lets AI agents work freely across your information? "We let you own your data" stops being an idealistic pitch and becomes a competitive advantage.

Imagine workspaces where AI agents share context, work on files in open formats, and evolve through conversation rather than vendor release cycles. Agents provide intelligence. You keep the data. When a better agent comes along, you switch. Your data stays.

## Early Signs

I'm already experiencing this with Obsidian and Claude Code. My notes are plain markdown files. Claude Code runs AI agents on top for email processing, planning, and workflows. If something better comes along, Codex or whatever's next, I switch agents. The data stays.

## Conclusion

The data ownership fight has lasted decades. The principles were sound. The technical solutions existed. What was missing was economic incentive.

If AI agents become a new form of software, as I argued in my previous post, this may finally change. When users can build their own workflows, when intelligence becomes the product and data can stay open, lock-in strategies lose their edge. Portability shifts from idealistic demand to market expectation.

The vision digital rights advocates have long fought for, data that users truly own, applications that visit rather than capture, might finally go mainstream. Not through activism alone, but because the economics finally make sense.
