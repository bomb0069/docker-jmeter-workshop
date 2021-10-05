# JMeter Runner on Ubuntu for Performance Testing Workshop

## Build

```cmd
docker build . -t bomb0069/jmeter-runner:20211004-6
```

## Run

```cmd
docker run --name jmeter --rm -p 80:80 -e SIAB_PASSWORD=11111111 -e SIAB_SUDO=true -e SIAB_SSL=false bomb0069/jmeter-runner:20211004
```

## Reference

- [shellinabox - shellinaboxd_man.wiki](https://code.google.com/archive/p/shellinabox/wikis/shellinaboxd_man.wiki)
- [shellinabox](https://github.com/shellinabox/shellinabox)
- [docker-shellinabox](https://github.com/spali/docker-shellinabox)
- [docker-jmeter](https://github.com/justb4/docker-jmeter)
