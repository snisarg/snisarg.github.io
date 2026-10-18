---
layout: post
title:  "Multi-Screen, Multi-Task"
description: "How I organize macOS workspaces by task, using AltTab and Control + number shortcuts to keep context switching intentional."
date:   2026-10-18 00:00:00 -0700
categories: blog
comments: true
---
I often work on multiple projects in parallel. With windows from every task open together, context switching becomes difficult. I don’t just want to switch apps—I want to “move” from one task to another and have only the relevant windows in front of me.

So I organize my Mac around tasks, not apps.

Each task gets its own workspace: a Chrome window with the relevant tabs, plus whatever other windows the work needs. By “screen,” I mean a macOS virtual desktop—not necessarily a separate monitor.

## Two levels of switching

**Within a task, I switch windows.** I use [AltTab](https://github.com/lwouis/alt-tab-macos), configured to show only windows in the current workspace. Think Command + backtick, but across all the apps supporting that task—not just windows of one app.

My browser, editor, and terminal are different applications, but they belong to the same activity. Switching between them shouldn’t pull me into unrelated work.

**Between tasks, I switch workspaces using Control + a number.** The numbers become a rough priority order: Control + 1 takes me to my main task, Control + 2 to the next, and so on. I’m choosing the task I want to focus on, not hunting for an application.

### Setting up direct jumps on macOS

1. Open Mission Control with **Control + Up Arrow**, then use the **+** button to create the desktops you need.
2. Go to **System Settings → Keyboard → Keyboard Shortcuts → Mission Control**. Expand the Mission Control group and enable **“Switch to Desktop 1,” “Switch to Desktop 2,”** and the others you need, using **Control + the corresponding number**.
3. Under **System Settings → Desktop & Dock → Mission Control**, turn off **“Automatically rearrange Spaces based on most recent use.”** This keeps the ordering predictable.

## A change of scene

Moving to another workspace gives me both a mental and a visual context switch. The previous task disappears from view. The next one has its own tabs, tools, and arrangement.

Sometimes I need a break from one problem. Other times, another task becomes more important. Either way, I can leave the first task in place and return to it later.

I call this **multi-screen, multi-task**. It isn’t about doing everything at once. It’s about giving each task a place—and focusing on the place I’m in.
