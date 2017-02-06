[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/dendrite.svg)](https://hub.docker.com/r/rubygem/dendrite/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/dendrite.svg)](https://hub.docker.com/r/rubygem/dendrite/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/dendrite.svg)](https://hub.docker.com/r/rubygem/dendrite/)
[![Gem Downloads](https://img.shields.io/gem/dt/dendrite.svg)](https://rubygems.org/gems/dendrite/)
# dendrite

Auto-Generated Docker image for dendrite to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/dendrite`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/dendrite`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/dendrite`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/dendrite/)
