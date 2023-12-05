---
layout: blog
title: "VirtualBox is collapsing: a n-day story"
tags: binary-exploitation hypervisor-exploitation
comments: true
date: 2023-11-23
---

# VirtualBox is collapsing: a n-day story

Hi everyone! It's been a while :)
This year I've worked on a project for the thesis for my bachelor's degree regarding hypervisor exploitation. 
This was my first time looking at hypervisor exploitation, so I decided to start with a known vulnerability without a public exploit available. 
TL;DR: I managed to write a full exploit for a linux host and a windows host (both using a linux guest OS).

I will present my project at m0leCon 2023 in Turin (December 2nd). [Here](https://m0lecon.it) you can find more details about the conference :)
The talk is going to be recorded, I'll post here the link to the video once it has been released. I can't wait for next week! :)

![Image](/assets/images/molecon.jpg)

## Resources

* [Link to the slides](/assets/blog/2023/Virtualbox-research-1/VirtualBox-m0leCon.pdf)
* [Link to the exploits](https://github.com/LukeGix/CVE-2019-2722_Exploit)
* [Chocolate Milk: E1000 NIC driver](https://youtu.be/imdUGT3tZEU) (by Gamozolabs)
* [E1000 Specification Manual](https://pdos.csail.mit.edu/6.828/2017/readings/hardware/8254x_GBe_SDM.pdf)

## Exploit Demo (Windows Host OS)

<video src="/assets/blog/2023/Virtualbox-research-1/Proc_cont_win.mp4" width="130%" height="130%" controls></video>

## Exploit Demo (Linux Host OS)

<video src="/assets/blog/2023/Virtualbox-research-1/Proc_cont.mp4" width="130%" height="130%" controls></video>
