---
title: "Overtinkering"
date: 2026-06-10 18:00:00 -0400
categories: [Homelab, General]
tags: [homelab, proxmox, self-hosted]
description: "First post — what this blog is, what I'm running, and why I bother."
---

I tend to overthink things. Give me a simple problem and I'll find the system hiding inside it, the dependencies, the edge cases, the "well, what happens when this fails at 2am." It's not always efficient, but it's how my brain works, and eventually it turns into something useful.

That tendency is what built this. A few years ago it was a decommissioned 2012 Mac Mini running ESXi and a handful of VMs. Now it's a small Proxmox cluster, a growing pile of containers, and a list of services I run myself because the alternative, leaving a problem half-solved, isn't really an option for me. Nothing like the feeling of closing an open loop.

This blog is where I document it.

## What I'm Running

The core of it right now:

- **Hypervisor:** Proxmox cluster on two HP EliteDesks
- **Networking:** A modest UniFi stack, and a bunch of VLANs
- **Storage:** An aging Synology from 2019, but it still works
- **3D Printer:** a Prusa MK3S+, a real workhorse. Bought it used to replace my Ender 3 V2, which replaced my Monoprice Mini V2. Been 3D printing a long time. Hoping to get a multicolor system at some point.
- **Smarthome:** Currently running Hubitat C7, forwarding all devices to Home Assistant OS running on a VM for dashboards and the few automations Hubitat can't do. Coming from SmartThings, going all-in on Hubitat made sense.

Different hobbies, same itch — build the system, then keep improving it.

## Why Bother

Running your own infrastructure teaches you things no certification course will. You break something and you have to figure out why, not because it's your job, but because you made the problem and now you live with it.

It also keeps the skills sharp. A lot of what I've learned here has shown up directly in how I approach things at work.

## Learning in Public

Most recently, that meant Ansible. I spent several weeks turning a manually managed pile of containers into something automated and repeatable: provisioning, DNS, updates, backups, all of it.

I'm also working toward the Okta Certified Professional exam, since it keeps showing up in the kind of roles I'm targeting. I may also pursue the SC-300 Microsoft Identity and Access Administrator cert. This would be my first formal IT certification in my 15-year career.

## What's Coming

Specific builds, configs, and the inevitable troubleshooting rabbit holes. If something took me an hour to figure out that should have taken five minutes, it's probably worth writing down.

---
