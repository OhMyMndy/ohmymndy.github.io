+++
date = '2025-03-17T15:20:20+01:00'
draft = true
title = 'C states and my AMD RX580'
+++

I am running an **AMD Ryzen 9 5900X** CPU with **AMD RX580** GPU on an Aorus motherboard, for about three years now in my desktop.
For the longest time I was using Windows, because I mainly used it for audio production and gaming.

In October 2024, I installed Fedora 41 on the machine, which was working flawlessly, beside waking up from sleep.
I thought the problem had to do with a specific new kernel version which had some changes to the AMD driver for my system, causing the kernel to panic and my system to reboot when I tried to wake the machine up.

Fast forward to early February 2025, I installed Ubuntu 24.04 on the machine, in the hope that it would solve the issue, as it seems to point to the kernel being the problem.
But unfortunately, the same problems...

I tried updating the bios, to no avail. A while later it struck me, maybe c states have something to do with it.

So I enabled c-states in the Bios, are now working flawlessly!