---
layout: post
title:  "Starting a personal blog"
description: "Why I choose github pages to host my personal blog, some setup steps and tips"
date:   2024-11-16 00:00:00 -0800
categories: blog
comments: true
---
Decisions that went into starting a blog on github, how to start quickly and tips.

## Why

I was having a hard time to track personal notes on OneNote. It's a mixture of very specific, day to day activities as well as a need-to-know information blob of text that I may use infrequently. I also have friends asking me a lot about the latter, and so I decided to formalize them into a blog and purge them to keep my personal notes sane. 

I intend to write more about software engineering and tech as well. There's a lot of wheel reinvention that happens unknowingly and writing some of the daily experiences, new finds interesting, and comments insightful. 

It's a great bonus if it helps anyone. :) 

## Github Pages v. Medium v. Wordpress

These are the top 3 platforms that came up when I was researching about best places to host a blog for free. I'm writing this after the fact but I'll try to capture as much as I remember while trying to compare them. 

### Wordpress

I was getting everything would need or envision needing in the future in the paid section from Github Pages. 

I don't care much for the customizations and theming much, so I'm ok to forgo that. 

### Medium

I've been a reader on Medium for a few years now. There used to be some great articles and I'm sure there are great ones coming up even right now. But lately I've grown increasingly frustrated with the quality of content and the click-bait titled articles. This has to be with the monetization scheme. I find myself almost never going on Medium any more, and I've heard the same from others.

### Github Pages

- Flexibility
    
    Although we can only have static pages, it's great to have control over the underlying code. GitHub Pages allows us to push the limits with what we can do. 
    
- Version Control
    
    This is less of a blog and more a library of notes for me. I'd love to see how my thoughts about topics evolve over time, and this is a key feature for me. 
    
- Full control
    
    I own all the rights to the notes I publish.
    

### Comparison

Links

- [artsy.github.io/blog/2019/01/30/why-we-run-our-blog/](https://artsy.github.io/blog/2019/01/30/why-we-run-our-blog/)
- [signalvnoise.com/signal-v-noise-exits-medium/](https://m.signalvnoise.com/signal-v-noise-exits-medium/)

## Setting up

I’m publishing this really old note much later, so the original links I used to set this up are long obsolete, but the official guide seems to have everything that’s needed: [Setting up Github Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)

### Debugging locally

```
$ bundle exec jekyll serve
```

Links: 
* [docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

## Tips

### Saving drafts

Notion uses markdown-esque language to represent its notes. You could copy and paste into the `.markdown` files that Github Pages needs directly from Notion. So if I’m starting a new note, I start writing it on Notion or for an old one, I move it from OneNote to Notion, edit and stylize it there first, and then copy it over when I want to actually publish a note.
