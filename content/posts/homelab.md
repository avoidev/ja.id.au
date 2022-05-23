---
title: "Homelab 💻"
date: 2022-03-30T20:15:29+10:00
draft: false
description: Overall dump of knowledge about my current homelab setups.
---

As I'm mentioned in other spots on this website, I'm an IT guy. Nothing too crazy, currently working a support job however I do like dabbling and actually engaging my brain from time to time. My HomeLab is one of these brain engaging activities I like doing.

The run-down on this is pretty straight forward. I have two boxes running Proxmox, and a cheap $5 VPS from Vultr. Both Proxmox boxes have a VM running ubuntu server and a wireguard VPN, and current connect to the VPS as the main point of contact. However I understand this is a potential issue as if that VPS goes down for whatever reason I'll be stuck without VPN access.

Solution? Well the solution I've setup is that I have cron jobs running that check for VPN access every 30 minute, if the can't ping the internal IP of the VPS (10.8.0.1) then it'll drop the current VPN config, and swap to another that will use DDNS entries to connect to each other. Maybe this is a bit convoluted, but it's a solution I've devised that seems to work (So far). 🤞

No what do I actually use these for, nothing too spectacular both hosts run File Servers that sync to each other nightly, runs a docker host that runs Jellyfin and Plex containers, a PhotoPrism container, Sonarr, Radarr, Jackett and Navidrome containers for my legally obtained media.

Both hosts aren't particularly impressive however I do plan on boosting the storage capacity in the near future. The primary host is an i7-4770, 32GB RAM, 512 SSD and 8TB WD Red. The secondary host is an i5-4690, 16GB RAM, 256GB SSD and a 8TB WD Red.

Ideally I'll upgrade these with another 2x8TB disk each and either use RAID 5 for some parity. However I've also toyed with the idea of dipping my toes into SnapRAID and UnionFS.

Like most of these posts I'll update as I go along :)
