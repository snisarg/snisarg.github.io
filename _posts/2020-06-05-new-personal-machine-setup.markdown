---
layout: post
title:    "New Personal Machine Setup"
description: "Installations and configurations to get up and running on a new machine." 
date:     2020-06-05 12:00:00 -0800
categories: blog
comments: true
---

*Handy guide to set up a new machine so everything is as is.*

# MacOS

1. Deleted unwanted preinstalled apps 
1. Install all OS updates
1. From the App Store, install:
    * Toggl
    * OneNote
    * Messenger
    * WhatsApp
    * If they ever release a good desktop app, Pocket and Feedly
    * XCode
1. From default browser, install:
    * Chrome
    * iTerm2
    * OneDrive for Mac
    * Google Drive File Stream
    * Sublime Text
1. Chrome
    * Sync Gmail and other accounts as separate profiles
    * Plugins should be pulled with the accounts:
        1. LastPass
        1. DarkReader
        1. Pocket plugin
    * Create Chrome shortcuts for: 
	    1. Daily Log on Google Docs
	    1. Google Keep
	    1. Pocket (if they still don't have a good MacOS app)
	    1. Feedly (if they still don't have a good MacOS app)
	    1. Toggl Summary view, set to 'today'
1. In System Preferences:
    * General
        * Appearance: Dark
        * Show scroll bars: When scrolling
        * Default Web Browser: Chrome
        * Uncheck Close windws when quitting an app
        * Recent items: 20
    * Desktop & Screen Saver 
        * Screen Saver > Word of the Day
    * Dock
	    * Position on screen: Left
        * Uncheck Minimize windws into application icon
    * Mission Control
        * Uncheck Automatically rearrange Spaces based on most recent use
    * Internet Accounts
        * Add all accounts for email, calendar
    * Touch ID
        * set it up
    * Bluetooth
        * Check Show Bluetooth in menu bar
    * Sound
        * Check Show volume in menu bar
    * Keyboard
        * Keyboard Shortcuts
            * Mission Control Tab | Mission Control > turn on all "Switch to Desktop X" from 1 to 10"
            * Keyboard Tab | Update "Move focus to active or next window" to Cmd + Esc
    * Trackpad
        * Point & Click
            * Check Tap to click
            * Click slider set to Light
            * Tracking speed set to Fast
        * More Gestures
            * Check App Expose
    * Displays
        * Display
            * Resolution set to "more space"
            * Uncheck Show mirroring options in the menu bar when available.
        * Night Shift
            * From 3.31 AM to 3.30 AM.
    * (Potentially automate in the future)
1. More hidden system preferences:
    * Update Screenshot image drop destination from Desktop to Downloads folder:
        * `$ defaults write com.apple.screencapture location ~/Downloads`
1. Get your dotfiles from github.com/snisarg/dotfiles
    * `$ cd /tmp && git clone https://github.com/snisarg/dotfiles.git && rm -rf dotfiles/.git && cp dotfiles/.* ~` 

### Application specific preferences 

1. Finder
    * Preferences 
        * Sidebar
            * Check your username so `/Users/username` directory is visible in finder
            * Uncheck iCloud Drive if you're not using it.
    * Toolbar > View
        * Click on Show Path Bar
1. iTerm2
    * Open iTerm2
    * Toolbar > iTerm2 > 
        * Make iTerm2 Default Term
        * Install Shell Integrations 
