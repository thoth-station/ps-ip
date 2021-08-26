Predictable Stack for Computer Vision Applications
--------------------------------------------------

The images described here are built with Thoth Predictable Stacks and contains Computer Vision packages for Data Science usage.

.. image:: https://img.shields.io/github/v/tag/thoth-station/ps-cv?style=plastic
  :target: https://github.com/thoth-station/ps-cv/releases
  :alt: GitHub tag (latest by date)

List of packages in ps-cv-ocr
=============================

.. image:: https://quay.io/repository/thoth-station/ps-cv-ocr/status
  :target: https://quay.io/repository/thoth-station/ps-cv-ocr?tab=tags
  :alt: Quay - Build

.. code-block:: python

    - opencv-python
    - pytesseract
    - pillow

This image contain specific binaries for `openv-cv` and `tesseract`. In particular tesseract languages added are Finnish, Swedish and English).

List of packages in ps-cv-tensorflow
====================================

.. image:: https://quay.io/repository/thoth-station/ps-cv-tensorflow/status
  :target: https://quay.io/repository/thoth-station/ps-cv-tensorflow?tab=tags
  :alt: Quay - Build

.. code-block:: python

    - opencv-python
    - tensorflow
    - pillow
    - keras
    - tensorboard
    - tensorflow
    - jupyter-tensorboard

This image contain specific binaries for `openv-cv`.

List of packages in ps-cv-pytorch
=================================

.. image:: https://quay.io/repository/thoth-station/ps-cv-pytorch/status
  :target: https://quay.io/repository/thoth-station/ps-cv-pytorch?tab=tags
  :alt: Quay - Build

.. code-block:: python

    - opencv-python
    - torch
    - torchvision
    - pillow
    - tensorboard
    - jupyter-tensorboard

This image contain specific binaries for `openv-cv`.

Generic data science packages
=============================

All the above images are built from `Generic Data Science Image <https://github.com/thoth-station/s2i-generic-data-science-notebook>`__,
therefore they contain also the following packages:

.. code-block:: python

    - beautifulsoup4
    - bokeh
    - boto3
    - cloudpickle
    - cython
    - dask
    - dill
    - distributed
    - h5py
    - ipywidgets
    - kafka-python
    - matplotlib
    - numpy
    - pandas
    - plotly
    - pyarrow
    - s3fs
    - scikit-image
    - scikit-learn
    - scipy
    - seaborn
    - sqlalchemy
    - statsmodels
