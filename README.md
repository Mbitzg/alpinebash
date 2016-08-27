# docker image: alpinebase [Layer 2]

This layer 2 bash image is built upon [mbitz/alpinebase](https://hub.docker.com/r/mbitz/alpinebase/)

## Description

Install bash as default shell. Change time zone from GMT0 to GMT+8.


## Upcoming Changes

TBD

## Additions
/:
	entrypoint

/root/:
    .bashrc
	.bash_profile

## Tags

* `latest` tracks the `edge` tag from [upstream](https://hub.docker.com/r/_/alpine/)

_This includes the `main`, `testing`, and `community` repositories, but all packages outside `main` are masked. To import them, just use `apk-install pkgname@reponame`._

# License
[MIT](https://tldrlegal.com/license/mit-license)

