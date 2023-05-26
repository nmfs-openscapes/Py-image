![](https://img.shields.io/docker/image-size/openscapes/corn?sort=date)
<a href="https://hub.docker.com/repository/docker/openscapes/corn/tags?page=1&ordering=last_updated"><img src="https://img.shields.io/docker/v/openscapes/corn"></a>

# Py-image 
 
Jupyterhub base image for the [NMFS Openscapes Hub](https://nmds-openscapes.github.io)

## Overview

Read the info on [https://github.com/NASA-Openscapes/corn](https://github.com/NASA-Openscapes/corn). This image is based off of that.

## Testing using Binder

Spinning up the JupyterHub on Binder is slow but at least allows you to test out the configuraton.

* Click the Binder button and wait for the VM to spin up.

It will install all the packages and then use the Docker image which has JupyterLab and RStudio (rocker). Should just open up JLab when done and you can choose R.
