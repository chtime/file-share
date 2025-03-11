# File Sharing

This is a super basic image running Pythons built-in HTTP server, serving the `app/web` directory.

This image has two purposes: one, allow simple file sharing by creating new images (or updating a running container); two, to be easily deployable in a Kubernetes environment. 

Whenever this repository is pushed to and is hosted on Github, a new build is triggered by Github Actions, publishing this image at `ghcr.io`. See this repositories packages for more details.
