# FCND-Term1-Starter-Kit

Starter kit for FCND Term 1. Python 3 is used for the entirety of term 1.

Packages used:

* [`matplotlib`](https://matplotlib.org/)
* [`jupyter`](http://jupyter.org/)
* [`udacidrone`](https://github.com/udacity/udacidrone). Due to `udacidrone` being updated as the ND progresses, it's recommended for new projects you update udacidrone with `pip install --upgrade udacidrone`.
* [`visdom`](https://github.com/facebookresearch/visdom/)


The recommended way to get up and running:

## [Anaconda Environment](docs/configure_via_anaconda.md)

Get started [here](docs/configure_via_anaconda.md). More info [here](http://conda.pydata.org/docs/).

Supported Sytems: MacOS, Windows, Linux

## Troubleshooting

**NOTE:** If `future` is not installed prior to `pymavlink` this will output an error message similar to the following:

```
  # omitted Traceback
  ModuleNotFoundError: No module named 'future'
  
  ----------------------------------------
  Failed building wheel for pymavlink
  Running setup.py clean for pymavlink
Failed to build pymavlink
Installing collected packages: torchfile, pillow, idna, chardet, urllib3, requests, visdom, future, lxml, pymavlink, utm, websockets, uvloop, udacidrone
  Running setup.py install for pymavlink ... done
  Running setup.py install for udacidrone ... done
Successfully installed chardet-3.0.4 future-0.16.0 idna-2.6 lxml-4.1.1 pillow-5.0.0 pymavlink-2.2.8 requests-2.18.4 torchfile-0.1.0 udacidrone-0.1.0 urllib3-1.22 utm-0.4.2 uvloop-0.9.1 visdom-0.1.7 websockets-4.0.1
```

If the output is `Successfully installed ... pymavlink ..` it's likely the install is fine. You can check by running:

```
python -c "import pymavlink"
```

if the install was successful there should be no output.

**NOTE:** If you're on MacOS you'll need to install developer tools to install `pymavlink`. You can do this by typing the following into a shell:

```
xcode-select --install
```

**NOTE:** On Windows you may need to open a terminal/powershell as an administrator. This can be done by right-clicking the program and selecting "Run as Administrator".
