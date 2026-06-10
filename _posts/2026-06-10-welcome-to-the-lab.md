---
title: "Welcome to the Lab"
date: 2026-06-10 18:00:00 -0400
categories: [Homelab, General]
tags: [homelab, proxmox, self-hosted]
description: "First post — what this blog is, what I'm running, and why I bother."
---

Every homelab starts somewhere. Mine started with a single used Dell OptiPlex shoved under a desk running Plex. That was a few years ago. Now it's a full rack, a managed switch, VLANs, a handful of VMs, and a growing list of services I run myself because I can.

This blog is where I document it.

## What I'm Running

The core of the lab right now:

- **Hypervisor:** Proxmox VE on a refurbished Dell PowerEdge
- **Networking:** pfSense for routing, a managed switch with VLANs for segmentation
- **Storage:** TrueNAS for NAS duties, connected via NFS/SMB to the rest of the stack
- **Containers:** Portainer managing a mix of Docker Compose stacks
- **Monitoring:** Grafana + Prometheus, because dashboards are satisfying

## Why Bother

Running your own infrastructure teaches you things that no certification course will. You break something at 11pm and you have to figure out why — not because it's your job, but because you made the problem and you have to live with it.

It also keeps the skills sharp. A lot of what I've learned in the lab has shown up directly in how I approach things at work.

## What's Coming

I'll be writing up specific builds, configs, and the inevitable troubleshooting rabbit holes. If something took me an hour to figure out that should have taken five minutes, it's probably worth writing down.

---

If any of this sounds familiar, stick around.
