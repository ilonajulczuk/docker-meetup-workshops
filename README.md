# docker-meetup-workshops

Hi! Here are some instructions to get you started.


# Installing docker

Docker runs only on GNU/Linux 64 bit. If you're using MacOS or Windows (or strange Linux distro), you should consider installing Virtual Machine with Linux and install docker on it.

Install vagrant with ubuntu 14.04 64bit, or just make sure that you have a similar distro on your laptop.

1. [Install vagant](http://www.vagrantup.com/downloads)
2. Configure vagrant:
  ```
  $ vagrant init hashicorp/trusty64
  ```
3. Start machine
  ```
  $ vagrant up
  ```
4. Ssh to the machine
  ```
  $ vagrant ssh
  ```

Official installation instructions for ubuntu 14.04 docker [site](https://docs.docker.com/installation/ubuntulinux/).

If you're lazy, you can just type:

```
$ wget -qO- https://get.docker.com/ | sh
```

## Lazy option

If you're super lazy, you can skip all those steps and quickly start a cheap vm from digital ocean with Docker installed.

Here is a 10 USD coupon code that should cover you for two months (the cheapest instance) or a month for a bigger one. Definitely enough for those workshops.

- [Coupon](https://www.digitalocean.com/?refcode=a039cd29dcba)
- [Creating a docker VM on Digital Ocean](https://www.digitalocean.com/features/one-click-apps/docker/).
