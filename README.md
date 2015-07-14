# packer-docker
Tiny core linux based packer container for easily getting packer binaries on your box

## Using the image

`docker run --rm -ti -v `pwd`:/cwd packer inspect test-template.json`

## Credits
I pretty much redid the following image but with tinycore and the official packer download URL.

https://registry.hub.docker.com/u/sequenceiq/packer/

They also provide the following example that should work with this image as well:

`$ alias packer='docker run -it --rm -v $(pwd):/cwd -w /cwd cameronbrunner/packer'`
