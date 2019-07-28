---
layout: post
title: Enter Proxmox
---

My goal from the beginning with this computer was to make a virtualization server. I figured that I could try and use what was popular in industry, that being VMWare's ESXi solution. I had seen that several people who had built their own homelabs had been able to get ESXi to work on Threadripper architecture, and I got a license free from my school, so I gave it a shot. 

Now you've probably noticed the title of this post is "Enter Proxmox" not "Enter ESXi" and that is because I was unable to install ESXi. I believe it is an issue with the motherboard compatability, but after being stuck building this server for a couple months, I really just wanted the fastest path to actually using it I could find. 

So instead, I chose to go with [Proxmox](https://www.proxmox.com/en/), the open source virtualization server software. I have used it several times in school so I was familiar with the web interface, but I had never tried to install it. The process was relatively painless (at least after I figured out that the thumb drive I was booting from needed to be formatted as Fat32). It even recognized my additional storage without me really needing to do anything.

The only issue I really ran into was that the networking was not set up correctly initially. I took most of the default settings at installation, and the gateway was set to be 127.0.0.1, which was not correct for my current apartment internet obviously. So instead I changed it to be the address of my router, and I was able to log reach the web interface for Proxmox.

![Proxmox Dashboard](/images/ProxmoxDashboard.jpg "Proxmox Dashboard")

I knew the first system I wanted to build was a CentOS 7 running Nagios Core to monitor all my future boxes. 

I found it significantly easy to add ISO files to build from, which makes my goal of having a diverse network running many different operating systems feasible. 

I do not have any experience with other virtualization software, but for beginner homelab builders, I think Proxmox is as painless as it can be to install and use. 