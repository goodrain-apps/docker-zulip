# Welcome to docker-zulip!

[![Docker Repository on Quay.io](https://quay.io/repository/galexrt/zulip/status "Docker Repository on Quay.io")](https://quay.io/repository/galexrt/zulip)
* [**Quay.io**](https://quay.io/repository/galexrt/zulip)
* [**Docker Hub**](https://hub.docker.com/r/galexrt/zulip)

***

This is a container image for [Zulip](https://zulip.org) from [Dropbox](https://blogs.dropbox.com/tech/2015/09/open-sourcing-zulip-a-dropbox-hack-week-project/)

**Quote from [Zulip.Org](https://zulip.org)**:
> Powerful open source group chat

Thanks to dropbox for Open Sourcing Zulip! - [Zulip's Github](https://github.com/zulip/zulip)

***

## How to configure the container

See the [Configuration](https://github.com/Galexrt/docker-zulip/wiki/Configuration) Page for infos about configuring the container to suit your needs.

***

## How to get the container:
### For docker use:
`docker pull quay.io/galexrt/zulip:v1.3.9`

### For the latest development image changes use:
`docker pull quay.io/galexrt/zulip:dev`

***

## **Configure your `docker-compose.yml`, before running the container!**
**If you don't configure it, you'll end up with a misconfigured Zulip Instance!**

***

## Starting the container
To start the container, you have to use either use `docker-compose` or `kubernetes`:

**Don't forget to configure your `docker-compose.yml` properly!!**
### Using docker-compose:
Change to the root of the source folder and run `docker-compose up`.
### Using kubernetes:
Change to the root of the source folder and run `kubectl create -f ./kubernetes/`.

***

## Community

* Chat with other docker-zulip users in the **IRC**. On the [IRC Freenode Webchat](https://webchat.freenode.net) or using a client [Join IRC channel](irc://chat.freenode.net:6697/#docker-zulip) server, in the #docker-zulip channel

## Contributing

If you find this container useful, here's how you can help:

* Help users with issues they may encounter
* Send a pull request with your awesome new features and bug fixes

_Please use 4 spaces as intent in the files, Thanks!_

**A big thanks to everybody that sends in issues, pull request!** and helps with the issues/tickets! **:-)**
