---
layout: post
title:  "Laptop as a 'home server'"
description: "Why I'm using my laptop (macbook) as a personal home server to run local services for my house"
date:   2024-11-17 00:00:00 -0800
categories: blog
comments: true
---
Why am I using a laptop as an always-on, always-connected server for personal use.

### Why not a cloud machine

I want a machine to locally control my smart home appliances and devices in the fastest possible way, rather than relying on cloud services. This requires having a programmable local machine in my house, which also keeps my cost at $0 (assuming I don't count the cost of the personal computer I already own).

It's worth noting some obvious downsides: there's no backup, so if the machine fails, the server fails (which I'm fine with, as this is just for my personal use). Additionally, this setup can't handle much load, but since I'm the only user, that's not a concern.

### Won’t a desktop be better for this?

Ideally, I should use a desktop machine for an always-on server. The main reason people avoid using laptops as always-running servers is the impact on battery life. Keeping a laptop constantly plugged in at 100% charge can lead to battery swelling and damage. However, I've found tools that can set an upper limit on battery charging. Setting this limit to 70% can actually extend the life of both the battery and the laptop.

I appreciate the flexibility of using a laptop, which I can use anywhere, rather than investing in a separate desktop machine. The main drawback of this approach is that my "server" becomes unavailable if I take my laptop outside my home Wi-Fi network—though this rarely happens.

## Laptop Setup

I use a MacBook, so the instructions below are with respect to MacOS.

### Battery Impact

To minimize battery wear, I use [AlDente](https://apphousekitchen.com), which limits the battery charge to 70%. This allows me to keep my laptop plugged in continuously, just like a desktop computer.

### Keep MacBook running on lid-close

To prevent the MacBook from sleeping after closing the lid, I followed the following steps, coming from this [stack overflow](https://apple.stackexchange.com/questions/361384/prevent-mac-from-sleeping-when-lid-closed-on-mojave-catalina/361398#361398) article.

Stop sleep:

`$ sudo pmset -a disablesleep 1`

re-enable sleeping:

`sudo pmset -a disablesleep 0`

## Servers

These are the following services/servers I wish to run on my local server setup:

### Home Assistant

[Home Assistant](https://www.home-assistant.io) was the main reason I wanted a home server. It's an excellent open-source solution for home automation that aims to do everything locally without relying on the cloud. Home Assistant already boasts great integrations across popular home automation manufacturers. Its [Reddit community](https://www.reddit.com/r/homeassistant/) is active, with users sharing tons of custom dashboards and scripts they've set up. 

My goal with this project is to gain the flexibility to programmatically create complex automations as I gradually introduce more smart devices and controls to my home. I will most likely have a follow-up note dedicated to setting up Home Assistant for myself.

### VPN

While I don't personally see a need for a VPN, I find it frustrating when traveling outside the US. Often, I'm automatically redirected to a local country's webpage when searching online, which isn't typically what I'm looking for. I’d love to have the ability to VPN into my home, so that the content is always local to my home region. 

I’m looking to set this up soon.

### AdGuard for Home

Initially, I planned to set up an ad-blocking server for all devices in my home to ping, eliminating the need for individual browser plugins. However, after reading online reviews, I learned that these servers often don't work as effectively or look as visually appealing as browser plugins. Consequently, I've decided against using this approach for now.
