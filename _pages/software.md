---
title: "Software"
permalink: /software/
---

## `deepcell-tf`
[![PyPI version](https://img.shields.io/pypi/v/deepcell?color=%23{{ site.accent_color }})](https://badge.fury.io/py/deepcell) ![PyPI - Downloads](https://img.shields.io/pypi/dm/deepcell?color=%23{{ site.accent_color }}) [![GitHub Repo stars](https://img.shields.io/github/stars/vanvalenlab/deepcell-tf)](https://github.com/vanvalenlab/deepcell-tf)

`deepcell-tf` is a deep learning package developed by the Van Valen Lab for single cell analysis of biological microscopy data. It is the home of the models Mesmer ([Greenwald et al. 2022](https://doi.org/10.1038/s41587-021-01094-0)) and Caliban ([Schwartz et al. 2023](https://doi.org/10.1101/803205)) and their associated datasets TissueNet and DynamicNuclearNet.

Within `deepcell-tf`, I developed the `deepcell.application` framework which wraps around a models and handles standard pre- and post-processing tasks such as resizing, tiling and post-processing to generate masks. The application object exposes a simple predict method for the user.

```python
from deepcell.applications import Mesmer
app = Mesmer()
segmentation_predictions = app.predict(X, image_mpp=0.5)
```

## `deepcell-tracking`
[![PyPI version](https://img.shields.io/pypi/v/deepcell-tracking?color=%23{{ site.accent_color }})](https://badge.fury.io/py/deepcell-tracking) [![PyPi Monthly Downloads](https://img.shields.io/pypi/dm/deepcell-tracking?color=%23{{ site.accent_color }})](https://pypistats.org/packages/deepcell-tracking) [![GitHub Repo stars](https://img.shields.io/github/stars/vanvalenlab/deepcell-tracking)](https://github.com/vanvalenlab/deepcell-tracking)

## `deepcell-toolbox`
[![PyPI version](https://img.shields.io/pypi/v/deepcell-toolbox?color=%23{{ site.accent_color }})](https://badge.fury.io/py/deepcell-toolbox) [![PyPi Monthly Downloads](https://img.shields.io/pypi/dm/deepcell-toolbox?color=%23{{ site.accent_color }})](https://pypistats.org/packages/deepcell-toolbox) [![GitHub Repo stars](https://img.shields.io/github/stars/vanvalenlab/deepcell-toolbox)](https://github.com/vanvalenlab/deepcell-toolbox)
- object based metrics

## `deepcell-kiosk`
[![GitHub Repo stars](https://img.shields.io/github/stars/vanvalenlab/kiosk-console)](https://github.com/vanvalenlab/kiosk-console)

## `traccuracy`
[![PyPI version](https://img.shields.io/pypi/v/traccuracy?color=%23{{ site.accent_color }})](https://badge.fury.io/py/traccuracy) [![PyPi Monthly Downloads](https://img.shields.io/pypi/dm/traccuracy?color=%23{{ site.accent_color }})](https://pypistats.org/packages/traccuracy) [![GitHub Repo stars](https://img.shields.io/github/stars/Janelia-Trackathon-2023/traccuracy)](https://github.com/Janelia-Trackathon-2023/traccuracy)
