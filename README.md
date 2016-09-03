# docker image: alpinebash [Layer 2]

This layer 2 docker image is built upon [mbitz/alpinebase](https://hub.docker.com/r/mbitz/alpinebase/)

## Description

Install bash as default shell. Set time zone to Asia/Singapore.


## Additions
Packages:
```
bash
```

Files and Folders:
```
/:
	entrypoint

/root/:
    .bashrc
	.bash_profile
```

## Tags

* `latest` tracks the `edge` tag from [mbitz/alpinebase](https://hub.docker.com/r/mbitz/alpinebase/)

* `e340` tracks the `e340` tag from [mbitz/alpinebase](https://hub.docker.com/r/mbitz/alpinebase/)

# License
[Apache 2.0](https://www.tldrlegal.com/l/apache2)
