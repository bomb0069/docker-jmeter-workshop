# JMeter Runner on Ubuntu for Performance Testing Workshop

## Build

```cmd
docker build . -t bomb0069/jmeter-runner
```

## Run

```cmd
docker run --name jmeter --rm -p 4200:4200 -e SIAB_PASSWORD=xyz678abc -e SIAB_SUDO=true -e SIAB_SSL=false bomb0069/jmeter-runner
```
