## What is offline_CROHME?
**offline_CROHME** is a tool for converting [CROHME](https://www.isical.ac.in/~crohme/) to Offline-handwritting text recognition dataset. This tool help to convert [INKML](https://www.w3.org/TR/InkML/) file format to image and groud-truth latex.

## What is CROHME?
The dataset provides more than 12 000 expressions handwritten by hundreds of writers from different countries, merging the data sets from 4 previous CROHME competitions and adding new ressources. Writers were asked to copy printed expressions from a corpus of expressions. The corpus has been designed to cover the diversity proposed by the different tasks and chosen from an existing math corpus and from expressions embedded in Wikipedia pages. Different devices have been used (different digital pen technologies, white-board input device, tablet with sensible screen), thus different scales and resolutions are used. The dataset provides only the on-line signal.

## How to use?
In the easy way, run below command:
```bash
python extract.py
```
Output data must be stored in CROHME_processed folder. Each INKML file will be extracted to a image file and groud-truth latex string in a text file.