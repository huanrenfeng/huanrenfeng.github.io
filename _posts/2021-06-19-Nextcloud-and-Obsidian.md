---
title: "Nextcloud and Obsidian"
date: 2021-06-19
tags: [diary]
---


I was working with nextcloud and obsidian these days.

I want to utilize my VPS. Because my old VPS server's port's restriction got removed for unknown reasons. So I have two VPS.
And I always have some complains about **OneNote** that I use. The syncing process is slow and sometimes unstable on IOS or Android apps.

First thing I touched is **Owncloud**, but after I've installed it, I started to realize that **Nextcloud** is much better than Owncloud, in terms of Note taking. You see the **Nextcloud Notes** app in the Google play store only supports Nextcloud account. 

I was confused before because I thought nextcloud and owncloud can be used interchangeably. It's true for the base protocol. For example I can use nextcloud account in the **Solid Explorer** App's Owncloud protocol. But the Nextcloud App is strictly fixed on the Nextcloud account and once I logged into an owncloud account the only view I got was a html web view, without actually logging into the account.

Why is that important? Why can't I just simply migrate to Nextcloud? Because the installation step is too complex. You see both cloud's tutorial only provide tutorials for **ubuntu** system. But what I'm using is **Debian** or **Centos8**. It's true that I can use **docker** for either cloud, but it's only for 80 port, meaning that it's not going to encrypt the files during transfer. 

I learned how to map 80 to 443 after, but that's too late, and docker have it's limits after all. I did some research on how the docker starts up and realized that I can't set the https support  from inside the docker that easily.

The manual installation took about 30 minutes ~ 1 hour. I repeated this for Nextcloud on Centos8. And that's not just it. I got various problems. The webpage is loading too slowly, downloading speed is slow and so on. I spent the entire day to fine tune the server, including setting up the **SSLCryptoDevice**, **Http2**, **BBR**, https based on **Let's Encrypt's ACME** instead of self signed certificate and so on.

Next I started leanring about "**QOwnnotes**" and Nextcloud Notes app. After a while, another app was brought to my eyes: **Obsidian**. It's way better than QOwnnotes. They all deal with markdown files locally, bt **Obsidian** is way better.

Next I just started to looking for apps on IPad that can support either Nextcloud or **WebDav**. First I used **Notebooks**, but it's not that good. Next I used **1Writer**. It's way better, and cheaper. 

So I got my solution for self host VPS note taking: **Nextcloud + Nextcloud Notes + Obsidian + 1Writer**.

The day after that, I learned about a new app: **Zettlr**. In many ways, it's even better than Obsidian. However, everytime Nextcloud updates a file, Zettlr get a glitch. It's a fatal problem that makes me stick to Obsidian.

About android apps, I did notice Joplin, and used it. Not better than Nexcloud Notes or 1Writer in terms of appearance. And the syncing method doesn't support self signed certificate in the IOS app. Also, it seems that it creates a lot of unknown files in the directory, and doesn't present my original notes. I don't know if it's problematic or I was using it in a wrong way. Anyway it's not a prefered app.
