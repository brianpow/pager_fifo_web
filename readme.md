# Real-time decoding of pager using GNU Radio and multimonNG with a cheap RTL2832U SDR dongle #

## What's new ##

The original version from [here](http://www.superkuh.com/rtlsdr.html#pager) supports GNU Radio 3.6 only. This fork supports latest GNU Radio 3.7

## Usage ##

```
mkfifo /tmp/pager_fifo.raw
./multimonNG -t raw /tmp/pager_fifo.raw
gnuradio-companion pager_fifo_web.grc
```

## Reference ##

[multimonNG](https://github.com/EliasOenal/multimonNG.git)