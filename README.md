# Docker-Ubuntu-latest-LTS

Docker image based on the official Canonical cloud repository, available at : https://partner-images.canonical.com/core/xenial/current/

This Docker image is pushed to docker.io/codecoaster/docker-ubuntu-latest-lts
It's the Docker base image used in Ghostbuntu : https://github.com/codecoaster/Ghostbuntu/

Include it in your projects, as a basic Docker image, using the FROM statement inside your Dockerfile <br />:
<code>
FROM codecoaster/docker-ubuntu-latest-lts:latest
</code>

To run the image in standalone mode, there is no need to download this git repository.  Instead, <a href="https://docs.docker.com/engine/installation/">install Docker</a> and do : 

<code>docker run codecoaster/docker-ubuntu-latest-lts</code>

...or simply use <a href="https://kitematic.com/">Kitematic</a> if you are under Windows, or OsX.
