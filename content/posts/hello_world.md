---
date: '2025-09-25T19:57:40+08:00'
draft: true
title: 'Hello_world'
cover: 
    image: "/img/hello_world.png"
    #relative: true
    hidden: false
---
Special thanks to John Schulman for a lot of super valuable feedback and direct edits on this post.

Test time compute (Graves et al. 2016, Ling, et al. 2017, Cobbe et al. 2021) and Chain-of-thought (CoT) (Wei et al. 2022, Nye et al. 2021), have led to significant improvements in model performance, while raising many research questions. This post aims to review recent developments in how to effectively use test-time compute (i.e. “thinking time”) and why it helps.

# Motivation
Enabling models to think for longer can be motivated in a few different ways.