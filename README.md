# FCND-Term1-Starter-Kit

Starter kit for FCND Term 1. Python 3 is used for the entirety of term 1.

Packages used:

* [`numpy`](http://www.numpy.org/)
* [`matplotlib`](https://matplotlib.org/)
* [`jupyter`](http://jupyter.org/)
* [`future`](https://pypi.python.org/pypi/future)
* [`lxml`](http://lxml.de/)
* [`pymavlink`](https://pypi.python.org/pypi/pymavlink). Common [MAVLink messages](http://mavlink.org/messages/common/). We recommend glancing over these to get a feel for the type of messages send back and forth.
* [`utm`](https://pypi.python.org/pypi/utm)

NOTE: `future` and `lxml` are required by `pymavlink`, and if they are not installed prior to `pymavlink` this may cause issues.

NOTE: If you're on MacOS you'll need to install developer tools to install `pymavlink`. You can do this by typing the following into a shell:

```
xcode-select --install
```

The recommended way to get up and running:

## [Anaconda Environment](docs/configure_via_anaconda.md)

Get started [here](docs/configure_via_anaconda.md). More info [here](http://conda.pydata.org/docs/).

Supported Sytems: MacOS, Windows, Linux