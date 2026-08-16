---
title: Making a Custom MIDI Controller
description: ""
date: 2026-08-13T22:22:54.277Z
preview: ""
draft: true
tags:
    - Technical
    - MIDI
---

I made a custom midi controller.

https://github.com/AdriandeLima/Midi-Controller

Things I would do differently:

Get a more bespoke project box or case, the wooden job didn't work out well, could be more ergonomic

Figure out a better mounting system for the project boards

Use a rotary encoder instead of a cd motor (more accurate)
Make it usb c

Improvements to the firmware:
Everything relies on MIDI CC, which isn't that reliable (especially for scrolling, there's probably a better way to do this using HID)