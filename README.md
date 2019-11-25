# [bokeh-server](https://github.com/tst-labs/bokeh-server)

## Maintained by: [the TST Labs](https://github.com/tst-labs)

Starts a bokeh server on port 8080.

## Building

```bash
docker build -t tstlabs/bokeh-server .
```

## Running

```bash
docker run -u $(id -u) -it --rm -v $HOME/myapp:/opt/app -p 8080:8080 tstlabs/bokeh-server
```
