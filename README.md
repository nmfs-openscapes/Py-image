# corn 🌽
 
Jupyterhub base image for the [NMFS Openscapes Hub](https://nmfs-openscapes.github.io/2023-Cloud-Hackathon/)

![](https://img.shields.io/docker/image-size/openscapes/python?sort=date)
<a href="https://hub.docker.com/repository/docker/openscapes/python/tags?page=1&ordering=last_updated"><img src="https://img.shields.io/docker/v/openscapes/python"></a> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nmfs-openscapes/corn/HEAD)


## Overview

Read the info on [https://github.com/NASA-Openscapes/corn](https://github.com/NASA-Openscapes/corn). This image is based off of that.

## Testing using Binder

Spinning up the JupyterHub on Binder is slow but at least allows you to test out the configuraton.

* Click the Binder button and wait for the VM to spin up.

It will install all the packages and then use the Docker image which has JupyterLab and RStudio (rocker). Should just open up JLab when done and you can choose R.
