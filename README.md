-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Gecko Detection Dataset

**Version:** 1.0.0
**Release Date:** 08 October 2026

## Overview

The Gecko Detection Dataset is an annotated image dataset developed for object detection research. It contains images of geckos and non-gecko samples collected under diverse environmental conditions. All annotations are provided in the YOLO object detection format.

The images included in this dataset were obtained from the iNaturalist platform. The intellectual property and copyright of each image remain with their respective authors. Each image is distributed under its original Creative Commons license, as specified in the accompanying `CITATION.xlsx` file, which also provides the corresponding attribution information.

If you use this dataset, in whole or in part, including its images, annotations, or any derived subsets, please cite both the original image authors (as listed in `CITATION.xlsx`) and the author of this dataset.

If you are the copyright holder of any image included in this dataset and would like your attribution to be corrected or your image to be removed, please contact the dataset author using the email addresses provided in the Contact section.

## Contents

- Images
- Bounding box annotations
- CITATION.csv
- LICENSE
- README.md

## Directory Structure

```
GeckoDetectionDataset/
├── README.md
├── LICENSE
├── CITATION.xlsx
├── Images/
│   ├── Gecko/
│   └── Non-gecko/ 
└── Labels/
    ├── Gecko/
    └── Non-gecko/ 
```

## Dataset Statistics

|    Property                         | Value |
|-------------------------------------|------:|
| Total images                        | 5,880 |
| Gecko images                        | 2,940 |
| Non-gecko images                    | 2,940 |
|                                     |       |
| Total annotation files              | 5,880 |
| Gecko annotation files              | 2,940 |
| Non-gecko annotation files          | 2,940 |

## Annotation Format

Annotations follow the YOLO object detection format:

<class_id> <x_center> <y_center> <width> <height>

where all bounding-box coordinates are normalized to the image dimensions.

This is a binary object detection dataset. The YOLO class label used in this dataset is:

```
0: GECKO
```

The corresponding class definition must be included in the dataset YAML configuration file used for training or inference.


## Author

- Juan Carlos Garcia Jimenez
- Úrsula Samantha Morales Rodríguez
- Miriam Pescador Rojas

## Affiliation

Instituto Politécnico Nacional

Escuela Superior de Cómputo

Sección de Estudios de Posgrado e Investigación

## Contact

Juan Carlos Garcia Jimenez: 
- jgarciaj1401@alumno.ipn.mx 
- juancarlosgarciajimenez123@gmail.com

Úrsula Samantha Morales Rodríguez:
- umoralesr@ipn.mx

Miriam Pescador Rojas:
- mpescadorr@ipn.mx

## License

This dataset is distributed under the terms described in the `LICENSE` file. 

## Citation

If you use this dataset in your research, please cite the associated thesis, publication, or the dataset itself if no associated publication is available.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

