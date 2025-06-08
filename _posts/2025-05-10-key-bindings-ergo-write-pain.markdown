---
layout: post
title:  "Wrist Pain, Keyboards and Key Bindings"
description: "Getting started with key modifiers, trying different ergo keyboards for wrist pain"
date:   2025-05-10 00:00:00 -0800
categories: blog
comments: true
---
My journey dealing with wrist pain using ergo keyboards and more recently, key modifiers.

## 2017: A good keyboard + keyboard shortcuts for everything

The simplest suggestion to prevent write pain is to use an Ergonomic keyboard. These are simply keyboards that are split and raised from the middle which is a more natural way to position our hands.

I’ve been using [Microsoft Sculpt keyboard](https://www.incase.com/products/sculpt-ergonomic-keyboard) which I liked a lot. There are a lot of others in the market so choose what makes most sense. To make using this Windows keyboard more natural for Mac and for me to not remap my brain as I juggle between the laptop keyboard and Sculpt on my office or home desk, I change the `modifier keys` from Mac Settings and swap `options` to map to `command` and `command` to map to `options` .

I consciously choose to learn keyboard shortcuts for everything I use, reducing the need to use my mouse. This prevents constantly lifting my right hand to reach for the mouse and then back. 

Another change that I am guessing helped me is switching to a more chunky mouse, the popular Logitch MX Master and then later Logitech MX Vertical.

Just with this change and being more conscious in general about my posture, my wrist pain pretty much vanished. 

## May 2025: Using the CAPS LOCK key

I tried my colleague’s [Logitech MX Mechanical](https://www.logitech.com/en-us/shop/p/mx-mechanical-mini) keyboard and enjoyed the experience. With Microsoft stopping the production of the Sculpt keyboard, I started looking for ‘split mechanical keyboards’. 

Looking at the popular ones from ZSA and popular custom Mechanical keyboards, I realized such ergonomic keyboards simply do not have all the keys I’d need, especially for coding: symbol keys, function keys, even `control` and `option` keys. I accidentally stumbled about [this video](https://www.youtube.com/watch?v=XuQVbZ0wENE) that talks about using the CAPS LOCK key as something more useful and it made so much sense to me. 

Instead of buying an expensive keyboard, I decided to customize the standard keyboard keys to see if I like the idea, and can quickly learn these combos without a productivity hit.

My digging around led me to [Karabiner](https://karabiner-elements.pqrs.org/), an open-source keyboard modifier software. This let me modify standard keyboards as I please, test out some of the custom key modifiers. To get started quickly, I used https://hannahswainlovik.eu/2024/02/05/caps-lock-as-a-layer-key-or-arrows-under-your-fingertips/ article talking about exactly what I wanted to try out in the first go. Installing from their link was super easy. I hated to reposition my right hand to use the arrow keys, so this seemed like something I would use.

Within 2 days, I also added `control`, `option` and `command` to `a`, `s` and `d` .

## May 2025 (also): Home Row Mods

I'm already hooked and have started using the new keybindings well. I added using 'tap and hold' modifiers to override the behavior of basic keys. I had a hard time setting this up, but what worked for me was using the conf from https://github.com/Erlendms/karabiner-actions/blob/main/actions/home_row_mods-s_ct_o_c.json

I've assigned the following 'tap and hold' behavior: 
`a` or `;` = `shift`
`s` or `l` = `control`
`d` or `k` = `option`
`f` or `j` = `command`

## June 2025: Tap and hold TAB as HYPER key

It didn't take me as much time as I anticipated to adopt to the new system. I added home row mod (press and hold) for the TAB key. The current behavior launches the most popular apps I use, for example my note taking app and my daily log with just TAB + "char_key". Before this, I would use cmd + space to launch Spotlight Search and then type the first 3 characters of the app I was looking for and then hit enter.

The HYPER key is popular coded to fire `command` + `control` + `option` together, so it doesn't conflict with any other keyboard shortcut, opening users to define any custom shortcut they please. However, I used the `variable` feature in Karabiner to code this up instead, which was significantly easier to set up. I was also able to use ChatGPT for the configurations which saved me a lot of time.

## Current Plan

I'm going to monitor how long I take to adopt these keys, and if it truly makes a difference in my everyday productivity.
My Karabiner config is at https://github.com/snisarg/dotfiles/blob/master/.config/karabiner/karabiner.json
