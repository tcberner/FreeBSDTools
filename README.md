# FreeBSD (new) Committer's Tools

> This repo contains notes from my new-committer period, as well as links 
> to useful FreeBSD resources (mostly for new committers) and some tools 
> of mixed parentage.

## Links

* [FreeBSD bugzilla](https://bugs.freebsd.org/)
* [FreeBSD phab](https://reviews.freebsd.org/)
* [FreeBSD package builders](https://pkg-status.freebsd.org/)

## Tools

* [sparse-checkout](bin/sparse-ports-checkout.sh)
  > This script checks out a (writable) ports-tree suitable for working
  > on individual ports. The ports tree is checked out in *sparse*
  > mode, which means that you only get the bits needed to modify
  > and build the ports you ask for. Can also be used to create
  > a ports tree from a Phab review. Joint work with tcberner@
