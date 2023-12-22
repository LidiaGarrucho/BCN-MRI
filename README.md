# Breast DCE-MRI Dataset
> Note: This is not the final version of the repository.

## Overview

Welcome to the repository for the breast Dynamic Contrast-Enhanced Magnetic Resonance Imaging (DCE-MRI) dataset and associated journal article. This dataset is designed for research purposes related to breast imaging and can be used for tasks such as image analysis, machine learning, and algorithm development.

![Graphical Abstract](https://github.com/LidiaGarrucho/BCN-MRI/blob/b8f3ebaa6273194103809892d47c6353f5a16c0c/misc/graphical_abstract.jpg)

## Dataset Details

### Description

- **Dataset Name:** Breast DCE-MRI Dataset
- **Modality:** Dynamic Contrast-Enhanced Magnetic Resonance Imaging (DCE-MRI)
- **Purpose:** Research and development in breast imaging, radiomics, machine learning and deep learning.

### Data Records

- High-resolution pre-treatment breast DCE-MRI images from patients with cancer that underwent neoadjuvant chemotherapy.
- Patient demographics (age, gender, etc.) and clinical information (treatment response, survival status, tumor subtype).
- Scanner and imaging details (manufacturer, model, field strength, resolution, etc.).
- Ground truth manual tumor segmentations.
- Expert-evaluated automatic tumor segmentations.
- Radiomic features from manual and automatic segmentations. 

## Journal Article

### A large-scale multi-purpose breast cancer MRI benchmark dataset with expert-approved tumor annotations and radiomics

**Name:** [Journal Name]
**Volume/Issue:** [Volume Number, Issue Number]
**Year:** 2024
**DOI:** [DOI Link]

### Abstract

This paper presents a large-scale multi-center breast cancer MRI dataset, featuring 1508 dynamic contrast-enhanced pre-treatment images sourced from four publicly available datasets. The dataset incorporates crucial clinical information, including age, tumor subtype, ethnicity, neoadjuvant chemotherapy response, and patient survival status. Notably, it encompasses 411 gold standard and 1508 expert-evaluated automatic pixel-level tumor annotations. Among the automatic annotations, 75.6\% were rated as _Good_, 18.2\% as _Acceptable_, and only 6.2\% as _Poor_ or _Missed_. 
Furthermore, comparing radiomic features extracted from both gold standard and automatic segmentations can help to evaluate the consistency of radiomics with segmentation. Meticulously curated for benchmarking and reproducibility by harmonizing diverse datasets, this resource is poised to significantly advance breast cancer research. We anticipate that this dataset will play a pivotal role in accelerating the development of data-intensive deep learning models, fostering innovation in breast cancer diagnostics and treatment planning. Our commitment extends to ongoing enhancements of the dataset, including manual annotations for the entire dataset and the incorporation of additional images in the future as part as RadioVal[^1] European project.

## Data Usage and Citation
Users must abide by the [TCIA Data Usage Policy and Restrictions](https://www.cancerimagingarchive.net/data-usage-policies-and-restrictions/). Ensure that you comply with the terms specified in the license. 
If you use this dataset or refer to the associated journal article in your work, please cite them using the following:

```bibtex
@article{your-article-citation,
  author = {Author Name 1 and Author Name 2 and ...},
  title = {Title of Your Journal Article},
  journal = {Journal Name},
  volume = {Volume Number},
  number = {Issue Number},
  year = {Publication Year},
  doi = {DOI Link}
}

@misc{your-dataset-citation,
  author = {Your Organization or Your Name},
  title = {Breast DCE-MRI Dataset},
  year = {Year},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{Repository URL}}
}
```
[^1]: Link to RadoVal webpage: [radioval.eu](https://radioval.eu/).
