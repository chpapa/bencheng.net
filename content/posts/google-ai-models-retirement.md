+++ 
draft = false
date = 2025-12-20T19:16:25+08:00
title = "Rant: The way Google handles the retirement of AI models is disappointing"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
+++
The way Google handles the retirement of AI models is disappointing.  
  
While I enjoy using Gemini 3 personally, the production workload of AI Agents requires stability, and model changes often lead to lower accuracy or broken workflows.  
  
We have a lot of production workload on Gemini 2.0 -- and I just got an email it will be retire by Mar 2026  
  
This means we will need to re-run evaluations for all production AI Agents and perform necessary prompt tuning to prevent issues in edge cases. With just three months left, and the holiday season of Christmas and Chinese New Year in between, this timeline is challenging.  
  
In contrast, Azure managed the retirement of GPT 3.5 only a few months ago with a more measured approach.  
  
While many vendors may not prioritize these transitions and simply switch to the next model, finger-crossed and hope everything works -- this can lead to significant disruptions on edge cases in production loading. (Our ongoing evaluations have shown that changes can indeed break existing workflows.)  
  
For those who care about maintaining stability, next year, as we celebrate the launch of Gemini 4, we will also be focused on re-running evaluations and prompt tuning for our Gemini 3 workloads [1].  
  
BTW, here are how I think GCP could have done better:  
  
1. Commit to a longer time frame API availability, you can stop people from creating new endpoint, but commit to support existing endpoint.  
  
2. If you plan to make it so short (like < 2 years), make it clear as you launch, roughly when it will be shutdown.  
  
3. If you're shutting down existing endpoint, provide a viable alternatives. Sorry to say that -- it's ridiculous to recommend an upgrade to 2.5-flash when 2.5 flash shutdown is just 3 months after 2.0 (Jun 2026!)  
  
4. Don't shutdown existing models when upgrades are NOT stable (GA) yet -- so if I don't want to upgrade to 2.5 Flash which will be deprecated 3 months, what are the current alternatives? 3 Flash, Pro are all in Preview -- by preview it meant NOT PRODUCTION READY right?  
  
Wait til you have 3.0 Flash Lite in stable (GA) models to deprecate 2.0 is way more reasonable.

[1] No official annoucement of when Gemini 3 will be deprecated yet ([https://lnkd.in/e26QCaNx](https://lnkd.in/e26QCaNx)); Yet historically it is around 1 year.
