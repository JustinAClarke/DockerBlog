---
layout: post
title:  "Getting started with Docker on the pi3"
date:   2017-02-05 12:44:58 +1100
---
Docker is a containerisation software designe to assist in the development and implementation of applications, or programs.  

From my interpertations of Docker, it follows the following rules
 * Do not modify a container in progress.
 * Understand that all data in a container will be erased at the drop of a hat.
 * Frequently update containers, either by re building or, just restarting.  If you require the constant uptime, run something similar to a cluster.

---

I plan to create a colection of docker containers  

 * Blog for Docker (this blog)
 * Nextcloud (personal instance)
 * Photo storage and sharing (Lychee)

---

The difficult part of what I am planning, is to run this on a collection of Raspberry Pi 3's.  
Generaly you can just download an existing container, such as `indiehosters/nextcloud` for nextcloud.  
The only problem is that container is built for an x86_64 not for the armhf that the Raspberry Pi requires.  

My plan is to use the `armhf/debian` base container for creating these containers.  
My original thought was to use arch liunx, as that is what I am most farmilar with,  
But that will require additional development.

This Blog will be my story of this developemnt


