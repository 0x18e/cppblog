---
layout: default
title: "2D Pixel Physics Using SDL"
date: 2025-12-28
---

## Intro
I've always been interested in how games like <a href="https://store.steampowered.com/app/881100/Noita/">*Noita*</a> are able to create such beautiful physics interactions. While looking into the engine behind the game hoping to understand how these systems were designed to behave this way. I found out that their engine is entirely custom made! The Falling Everything engine they called it. Their very own custom built 2D pixel physics simulation engine. I became curious enough to recreate the foundations of this engine using only <a href="https://www.libsdl.org/">SDL</a> as best as I can.
<br>
<br>
The physics interactions in *Noita* are absolutely phenomenal, creating interactions between each pixel really elevates the experience when it all comes together. Nothing feels more satisfying then watching the world burn around a monster trapped in an oil pit as you set off an spark in there.

<img src="{{ site.baseurl }}/assets/images/oil.gif">

