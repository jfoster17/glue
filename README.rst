|Actions Status| |Coverage Status| |DOI| |User mailing list| |Developer mailing list|

Glue
====

Glue is a python project to link visualizations of scientific datasets
across many files.

|Glue demo|

This repository contains the **glue-core** package which includes much of the core
functionality of glue that is used for the different front-ends, including the Qt-based
application and the Jupyter-based application. Other key repositories include:

* `glue-qt <https://github.com/astrofrog/glue-qt/>`_: the original Qt/desktop application for glue
* `glue-jupyter <https://github.com/astrofrog/glue-jupyter/>`_: a Jupyter front-end for glue

In addition to these, there are a number of plugin packages available. For a full list of repositories,
see https://github.com/glue-viz/.

Features
--------

-  Interactive, linked statistical graphics of multiple files.
-  Support for many `file
   formats <http://www.glueviz.org/en/latest/faq.html#what-data-formats-does-glue-understand>`__
   including common image formats (jpg, tiff, png), ascii tables,
   astronomical image and table formats (fits, vot, ipac), and HDF5.
   Custom data loaders can also be `easily
   added <http://www.glueviz.org/en/latest/customization.html#custom-data-loaders>`__.
-  Highly `scriptable and
   extendable <http://www.glueviz.org/en/latest/coding_with_glue.html>`__.

Installation
------------

For installation documentation, visit
`glueviz.org <http://glueviz.org>`__.

Contributing
------------

If you are interested in contributing to ``glue``, please read our
`Code of Conduct <https://github.com/glue-viz/.github/blob/master/CODE_OF_CONDUCT.md>`_
and `Contribution Guidelines <https://github.com/glue-viz/.github/blob/master/CONTRIBUTING.md>`_.

Support
-------

Please report problems to glueviz@gmail.com, or `open an
issue <https://github.com/glue-viz/glue/issues?state=open>`__.

License
-------

Glue is licensed under the `BSD
License <https://github.com/glue-viz/glue/blob/master/LICENSE>`__.

.. |Actions Status| image:: https://github.com/glue-viz/glue/actions/workflows/ci_workflows.yml/badge.svg
    :target: https://github.com/glue-viz/glue/actions
    :alt: Glue's GitHub Actions CI Status
.. |Coverage Status| image:: https://codecov.io/gh/glue-viz/glue/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/glue-viz/glue
.. |DOI| image:: https://zenodo.org/badge/doi/10.5281/zenodo.13866.svg
   :target: http://dx.doi.org/10.5281/zenodo.13866
.. |User mailing list| image:: http://img.shields.io/badge/mailing%20list-users-green.svg?style=flat
   :target: https://groups.google.com/forum/#!forum/glue-viz
.. |Developer mailing list| image:: http://img.shields.io/badge/mailing%20list-development-green.svg?style=flat
   :target: https://groups.google.com/forum/#!forum/glue-viz-dev
.. |Glue demo| image:: https://raw.githubusercontent.com/glue-viz/glue-qt/main/doc/readme.gif
   :target: http://vimeo.com/53378575
