---
title: "Try Phobox in less than five minutes"
categories:
  - usage
tags:
  - docker
  - phobox
  - container
  - images
  - virtualization
  - photo storage
---

# Try Phobox in less than five minutes

Interested in a smarter photo store? But you don't have time or knowledge to set it up?
In this article, I'll show you an easy way to start a Phobox in less than 5 minutes without installing it.

The Play-with Docker service is a quick way to try out docker images. I have created a Phobox version with some
create your own photos to create a demo version. To start a demo application, follow these three simple steps.

### Starting phobox

 * You need a Docker ID on dockerhub (It's free and fast created) -> https://hub.docker.com/signup
 * Open [Play with docker](https://labs.play-with-docker.com/) in browser and login
 * Create a new node with pressing "add new instance"
 * Copy the following code and paste it into the Play-with-Docker commandline
   * `docker pull milchreis/phobox:demo && docker run -p 8080:8080 milchreis/phobox:demo`
   * these step could take 1 minutes for starting up the phobox instance
 * Open the phobox by pressing on the "8080" batch in the upper menu.

<video width="320" height="240" controls>
  <source src="https://github.com/phoboxhq/phoboxhq.github.io/raw/master/assets/play-with-docker-example_2.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Using phobox
Now you can try all features of phobox. The system runs dedicated for you for the next 4h. Upload or delete pictures or try out what
yor are looking for. You can not damage anything.

### Adopting phobox
If you are now interessted in phobox and you want to run it for your own than there are multiple possibles for you:

* [Run it on your desktop](https://phoboxhq.github.io/download/)
* [Run it on your Raspberry Pi](https://github.com/phoboxhq/phobox/wiki/Phobox-on-a-Raspberry-Pi)
* [Run it on your Synology](https://github.com/phoboxhq/phobox/wiki/Phobox-on-Synology-NAS)
