# SUT-Crack - Classification

## Overview

This package provides the **Classification** variant of SUT-Crack for the Large Road Damage DataLake.

SUT-Crack was introduced in *Data in Brief* as a pavement crack dataset designed to support
classification, object detection, and segmentation workflows under challenging field conditions.

- Dataset ID: sut-crack-classification
- Task: classification
- Images: 25561
- Annotations: 25561
- Classes: 2 (cracked, non-cracked)
- Format: image_folder
- Source dataset DOI: 10.17632/gsbmknrhkv.6
- Source paper DOI: 10.1016/j.dib.2023.109642

## Source Facts

- Original crack imagery for segmentation/object detection: 130 images (3024x4032).
- Images captured from fixed height: 672 mm above pavement.
- Captured with a Samsung Galaxy S20 FE smartphone mounted on the rear bumper of a vehicle on Hashemieh Boulevard, Mashhad, Iran.
- Geotag metadata included on the 130 parent images in the source dataset.
- Classification set built by 200x200 cropping from the 130 parent images, producing 25,561 patches (1,886 `cracked`, 23,675 `non-cracked`; all 25,561 files have unique SHA-256 hashes) in the Mendeley Data v6 release (the *Data in Brief* article text reports 25,563 patches).

## Source Dataset

- Source URL: https://data.mendeley.com/datasets/gsbmknrhkv/6
- Mendeley DOI URL: https://doi.org/10.17632/gsbmknrhkv.6
- Source paper: https://doi.org/10.1016/j.dib.2023.109642
- Package URL: https://github.com/large-road-damage-datalake/sut-crack-classification

## Package Contents

- METADATA.json
- stats/
- visualizations/
- ABSTRACT.md
- SUMMARY.md
- CITATION.bib
- CITATION.md
- DOWNLOAD.md
- LICENSE.md
