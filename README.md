# docker-alpine-mtr

This is a very small container with MTR installed.
[MTR](https://github.com/traviscross/mtr) is a powerful tool which enables administrators to diagnose and isolate networking errors and provide reports of network status to upstream providers. MTR represents an evolution of the traceroute command by providing a greater data sample, as if augmenting traceroute with ping output.

## Getting Started

These instructions will cover usage information and for the docker container.
Create an alias to your Bash or Zsh:

ZSH Example:
```shell
vim ~/.zshrc
```
Add the following line to your file:
```shell
alias mtr='docker run -it fabianotessarolo/docker-alpine-mtr'
```
### Prerequisities

In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

mtr hostname-here

#### Container Parameters

```shell
docker run -it fabianotessarolo/docker-alpine-mtr destinationhere
```

## Built With

* Alpine Linux
* MTR

## Find Us

* [GitHub](https://github.com/fabianotessarolo/docker-alpine-mtr)

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the 
[tags on this repository](https://github.com/fabianotessarolo/repository/tags). 

## Authors

* **Fabiano Tessarolo** - *Initial work* - [FabianoTessarolo](https://github.com/FabianoTessarolo)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
