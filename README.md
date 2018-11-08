A Docker image for Ruby, which is same as official Ruby image (see below), but based on official CentOS image.

* Same Ruby install path.
* Same environment variables.
* Same installed softwares.

[![License X11](https://img.shields.io/badge/license-X11-blue.svg)](https://raw.githubusercontent.com/nishidayuya/docker-centos-ruby/master/LICENSE.txt)
[![Docker Pulls](https://img.shields.io/docker/pulls/nishidayuya/centos-ruby.svg)](https://hub.docker.com/r/nishidayuya/centos-ruby/)
[![Docker Automated build](https://img.shields.io/docker/automated/nishidayuya/centos-ruby.svg)](https://hub.docker.com/r/nishidayuya/centos-ruby/)

# Supported tags and respective `Dockerfile` links

* [`2.6.0-preview2-centos7`, `2.6-rc-centos7`, `rc-centos7` (*2.6-rc/centos7/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.6-rc/centos7/Dockerfile)
* [`2.6.0-preview2-slim-centos7`, `2.6-rc-slim-centos7`, `rc-slim-centos7` (*2.6-rc/centos7/slim/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.6-rc/centos7/slim/Dockerfile)
* [`2.5.3-centos7`, `2.5-centos7`, `2-centos7`, `centos7` (*2.5/centos7/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.5/centos7/Dockerfile)
* [`2.5.3-slim-centos7`, `2.5-slim-centos7`, `2-slim-centos7`, `slim-centos7` (*2.5/centos7/slim/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.5/centos7/slim/Dockerfile)
* [`2.4.5-centos7`, `2.4-centos7` (*2.4/centos7/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.4/centos7/Dockerfile)
* [`2.4.5-slim-centos7`, `2.4-slim-centos7` (*2.4/centos7/slim/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.4/centos7/slim/Dockerfile)
* [`2.3.8-centos7`, `2.3-centos7` (*2.3/centos7/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.3/centos7/Dockerfile)
* [`2.3.8-slim-centos7`, `2.3-slim-centos7` (*2.3/centos7/slim/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.3/centos7/slim/Dockerfile)
* [`2.2.10-centos7`, `2.2-centos7` (*2.2/centos7/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.2/centos7/Dockerfile)
* [`2.2.10-slim-centos7`, `2.2-slim-centos7` (*2.2/centos7/slim/Dockerfile*)](https://github.com/nishidayuya/docker-centos-ruby/blob/master/2.2/centos7/slim/Dockerfile)

# Usage

Same as official Ruby image. See [official Ruby image's README.md](https://github.com/docker-library/docs/tree/6c728e6e5244326d715115d8bb04ba2343f93248/ruby#how-to-use-this-image)

# Image Variants

## `nishidayuya/centos-ruby:<version>-centos7`

Same as [`ruby:<version>`](https://github.com/docker-library/docs/tree/6c728e6e5244326d715115d8bb04ba2343f93248/ruby#rubyversion), but this image is based on [`nishidayuya/centos-buildpack-deps:centos7`](https://hub.docker.com/r/nishidayuya/centos-buildpack-deps).

This image is useful to run CI (such as [GitLab CI `image` setting](https://docs.gitlab.com/ee/ci/docker/using_docker_images.html#define-image-and-services-from-gitlab-ciyml)).

## `nishidayuya/centos-ruby:<version>-slim-centos7`

Same as [`ruby:<version>-slim`](https://github.com/docker-library/docs/tree/6c728e6e5244326d715115d8bb04ba2343f93248/ruby#rubyversion-slim), but this image is based on [`centos:7`](https://hub.docker.com/_/centos/).
