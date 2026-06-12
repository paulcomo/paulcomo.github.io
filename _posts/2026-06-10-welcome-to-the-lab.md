---
title: "Overtinkering"
date: 2026-06-10 18:00:00 -0400
categories: [Homelab, General]
tags: [homelab, proxmox, self-hosted]
description: "Why this blog exists and why I can't seem to leave well enough alone."

------------------------------------------------------------------------------------

I tend to overthink things.

Give me a simple problem and I'll usually find the system hiding inside it: the dependencies, the edge cases, the failure modes, and the one thing that's going to break at 2am if I ignore it today.

That isn't always efficient, but it's how my brain works.

It's also why this site is called **The OverTinkerer**.

My projects rarely stay finished. A simple file server becomes backups, then monitoring, then automation. A smart home becomes network segmentation so IoT devices can't talk to my trusted devices and my camera system can't talk to strangers. A 3D printer starts making cable clips and ends up producing custom rack mounts because nothing off the shelf fits quite right.

The same thing happened with my homelab.

It began as a retired Mac mini from work running a handful of virtual machines. Over the years it grew into a Proxmox cluster hosting roughly thirty containers and virtual machines that run everything from media services and photo management to automation workflows and infrastructure that supports the rest of my house.

Like many homelabs, it evolved one project at a time.

And like many homelabs, much of it originally lived in my head.

Configuration happened manually. Notes were scattered across text files and sticky notes. Updates happened whenever I remembered. If something broke, I could usually fix it, but I couldn't always explain exactly how I had built it in the first place.  I am thankfull for the history command.

Eventually I realized that wasn't sustainable.

Rather than treat the homelab as a collection of experiments, I started treating it like production infrastructure. That meant documentation, repeatability, backups, automation, and designing systems that I could rebuild instead of simply maintaining.

This blog exists for the same reason.

I'm not trying to claim that I've invented anything new. Most of what I've learned came from documentation, forum posts, GitHub issues, Reddit threads, YouTube videos, and people generous enough to write down their own experiences.

Hopefully I'll add a few useful pages to that pile.

If I have to solve the same problem twice, it probably belongs on this blog.


---
