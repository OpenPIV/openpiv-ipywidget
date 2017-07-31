openpiv-ipywidget
===============================

Jupyter Widget GUI for OpenPIV

Installation
------------

To install use pip:

    $ pip install ipywidget_openpiv
    $ jupyter nbextension enable --py --sys-prefix ipywidget_openpiv


For a development installation (requires npm),

    $ git clone https://github.com/openpiv/openpiv-ipywidget.git
    $ cd openpiv-ipywidget
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix ipywidget_openpiv
    $ jupyter nbextension enable --py --sys-prefix ipywidget_openpiv
