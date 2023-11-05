# This is donwloader for pip install pyinstaller

## Instructions are as follows

On the system that has access to internet

The pip download command lets you download packages without installing them:

`pip download -r requirements.txt`
(In previous versions of pip, this was spelled pip install --download -r requirements.txt.)

On the system that has no access to internet
Then you can use

`pip install --no-index --find-links /path/to/download/dir/ -r requirements.txt`
to install those downloaded modules, without accessing the network.