---
title: Using RX with melodic instruments
description: An article detailing cleaning up audio for melodic instruments (namely strings)
date: 2026-08-13T21:30:01.748Z
preview: ""
draft: true
tags:
    - Technical
    - Tutorial
    - Theory
---

Ideally you'd manage to get a good recording of a soloist during your recording session, but this isn't always possible (especially if you're recording a live event).

Fortunately, software like [Melodyne]() and [RX]() exist to help clean up audio in post. As you'll hear in the examples, it's never quite a perfect fix, so don't rely on "fixing it in post", but it's always good to have a backup plan.

This article will be covering some of the techniques I've used to clean up violin playing using RX's **spectral repair** tools. While I've worked mostly with piano/violin, I imagine these techniques can be applied to any instrument. I've focused on instruments here because most tutorials out there are created with vocals, or a full band (which is excellent at hiding issues that become apparent in solo music) in mind.

## Fixing Click/Pops

<iframe width="100%" height="100" scrolling="no" frameborder="no" allow="autoplay; encrypted-media" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/soundcloud%3Atracks%3A2381336271%3Fsecret_token%3Ds-YHkZF1Hspx3&color=%238700ff&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/adrian-de-lima-664572410" title="Adrian de Lima" target="_blank" style="color: #cccccc; text-decoration: none;">Adrian de Lima</a> · <a href="https://soundcloud.com/adrian-de-lima-664572410/click-example-4/s-YHkZF1Hspx3" title="Click example" target="_blank" style="color: #cccccc; text-decoration: none;">Click example</a></div>


fixed

<iframe width="100%" height="100" scrolling="no" frameborder="no" allow="autoplay; encrypted-media" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/soundcloud%3Atracks%3A2381336280%3Fsecret_token%3Ds-cYei8BAK22J&color=%238700ff&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/adrian-de-lima-664572410" title="Adrian de Lima" target="_blank" style="color: #cccccc; text-decoration: none;">Adrian de Lima</a> · <a href="https://soundcloud.com/adrian-de-lima-664572410/click-example-fixed-3/s-cYei8BAK22J" title="Click example fixed" target="_blank" style="color: #cccccc; text-decoration: none;">Click example fixed</a></div>
## Fixing Buzzes

Buzzing can occur for a couple reasons. Ground loop hum is a common one, and the easiest to remove.
INSERT SOMETHING ABOUT REMOVING GROUND LOOP HUM

A harder issue to diagnose and remove is when either your instrument randomly buzzes (I've had this often with loose finetuners on my violin), or digital artifacts introduced by other editing (I'm looking at you Melodyne!).

<iframe width="100%" height="100" scrolling="no" frameborder="no" allow="autoplay; encrypted-media" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/soundcloud%3Atracks%3A2381336274%3Fsecret_token%3Ds-coEekl5Thqv&color=%238700ff&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/adrian-de-lima-664572410" title="Adrian de Lima" target="_blank" style="color: #cccccc; text-decoration: none;">Adrian de Lima</a> · <a href="https://soundcloud.com/adrian-de-lima-664572410/buzz-example-1/s-coEekl5Thqv" title="Buzz example" target="_blank" style="color: #cccccc; text-decoration: none;">Buzz example</a></div>


Fixed

<iframe width="100%" height="100" scrolling="no" frameborder="no" allow="autoplay; encrypted-media" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/soundcloud%3Atracks%3A2381336277%3Fsecret_token%3Ds-bCucrk2GHeK&color=%238700ff&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/adrian-de-lima-664572410" title="Adrian de Lima" target="_blank" style="color: #cccccc; text-decoration: none;">Adrian de Lima</a> · <a href="https://soundcloud.com/adrian-de-lima-664572410/buzz-example-fixed-2/s-bCucrk2GHeK" title="Buzz example fixed" target="_blank" style="color: #cccccc; text-decoration: none;">Buzz example fixed</a></div>

## Fixing Scratches

Hard
Need Example

## Removing Background Noise
Need Example
## Removing Breaths
Need Example
## How to Tastefully Cut

It's very tempting, especially when listening to a track repeatedly and in isolation, to try and remove **every single blemish**. This actually isn't necessary, and can often end up making things sound worse. Less is more.

I focus on removing blemishes that take you out of the music as your listening, such as squeaks, clicks, pops and buzzes. Some background noise, or instrumental noise is necessary to keep the music sounding "human", so don't get too obsessive with cleaning.

Don't always remove breaths. My rule of thumb, if it's at the beginning of a phrase, or somewhere where it makes sense to breath, leave it in. If it sounds weird or out of place (usually from comping in a take without its context), feel free to remove it.

I tend to leave bow/finger noise in, but remove things like piano stool creaks, because one is part of the performance and music, and the other is a failing of the furniture. I would consider a page turn to be in the same vein as a piano stool creak.