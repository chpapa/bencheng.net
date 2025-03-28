+++ 
draft = false
date = 2025-03-28T19:16:25+08:00
title = "How Software Engineering will be like post-Transformer AI"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
series = []
+++

## Will AI Replace Software Developers? My take on the 2026 Landscape

Scrolling through social media, it's hard to miss the debate: will AI make software developers obsolete in the next 5 years? As someone who's spent over two decades in software engineering, developing AI/ML applications, I find the discussion fascinating, and frankly, a bit funny sometimes.

Nobody has a crystal ball, but I wanted to share my perspective on how things _might_ shake out, based on what I see today (early 2025) and where I'm trying to guide my own team. Take this with a grain of salt – I'm probably wrong, but here's my best guess for the near future.

### Software Engineering Today (The 2024 Baseline)

First, let's quickly recap the typical software development process, which hasn't fundamentally changed much over the last decade:

1. **Requirements & Planning:** Product Managers (PMs) or Business Analysts (BAs) gather needs, write specifications, create simple wireframes, user stories, acceptance criteria, etc. (The specific artifacts depend on the methodology).
2. **Design:** Designers (UI/UX) translate these high-level documents into detailed mockups, perhaps even interactive prototypes.
3. **Review & Approval:** Stakeholders review the designs/prototypes. User testing might happen here. A "go" decision is made to build the feature.
4. **Development:** Engineers write the code based on the approved designs, possibly involving technical planning, architecture reviews, security checks, and more.
5. **Quality Assurance (QA):** QA engineers design test cases, execute tests, and decide how the feature impacts existing test suites and regression testing.

### My Take: Will AI Replace Developers?

It's not a simple "yes" or "no".

I believe AI _will_ automate the creation of simpler software. Think basic websites, straightforward internal enterprise apps – the kind of things currently built with low-code/no-code platforms like PowerApps, Outsystems, or UIPath. We'll likely see new AI tools that allow for "vibe-coding": describing what you want, perhaps iteratively, and getting functional, safe code out. The users of these tools might be a new breed of "vibe-coder," blending skills from product management, design, and development.

However, for complex, reliable, large-scale systems, I don't see AI replacing experienced engineers soon. Current AI models (like transformers) still struggle with hallucinations, have significant error rates, and lack genuine reasoning capabilities (let's be honest, terms like "reasoning" or "chain of thought" are often marketing spin right now, I still prefer "test-time compute" personally). Building robust systems requires judgment and deep understanding that AI doesn't possess. We'll still need senior engineers, though they'll undoubtedly use powerful AI coding assistants, potentially reducing the need for as many junior developers on certain tasks.

### Software Engineering in 2026 (My Best Guess)

Given the above, how might that typical 5-step process change by 2026?

1. **Requirements & Prototyping (Merged):** PMs/BAs stop writing detailed specs or sketches of wireframe. Instead, they could use "vibe-coding" tools to directly create _interactive_ prototypes. This is huge! It allows for showing, telling, and getting stakeholder/user feedback right at the beginning, much earlier than the traditional mockup review stage. My team has already started experimenting with this.
2. **Design (Evolving Role):** This is where I'm less certain. If Step 1 produces a functional, interactive prototype showing the workflow, what's the primary role of the dedicated UX designer? Perhaps more designers will shift into product management roles. Or maybe their focus becomes refining the AI-generated UI/UX, which is often still rough. The lines between PM and Designer could blur significantly.
3. **Review & Code Handoff (The Integration Challenge):** With interactive prototypes and feedback happening in Step 1, the traditional Step 3 review might become less critical, except in very rigid processes. The _bigger_ challenge is making the AI-generated code from Steps 1 & 2 truly production-ready. I suspect this problem will be maybe 70% solved. Meaning, perhaps 95% of the generated code is usable, but engineers still need to spend significant time (say, 30% of the total effort compared to starting from scratch) fixing, refining those 5% code. Even if developers hate debugging AI code, the overall time savings will likely make it worthwhile.
4. **Development (AI-Assisted):** Development will be heavily AI-assisted. Think advanced code editors, LLM bots specialized in security vulnerability detection, architecture pattern suggestions, etc. A major open question is how we'll hire and train junior developers in this environment. The industry will likely be experimenting and learning here for the next 5+ years, maybe until AGI and singularity :)
5. **Quality Assurance (AI-Powered):** QA will also leverage AI, with tools assisting in test case generation and potentially enabling fully automated, self-healing end-to-end UI tests.

### Exciting Times Ahead
It's clear we're standing on the cusp of a significant transformation, watching as our whole industry potentially goes **upside down** in the next few years – and honestly, **what an incredibly exciting time to be part of it!** While the exact path isn't mapped out, the potential for AI to reshape our world is undeniable. Navigating this massive shift is the challenge and opportunity ahead, a journey **we shall all explore and learn from together.**
