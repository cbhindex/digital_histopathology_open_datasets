# A Summary of Digital Histopathology Open Databases

This document shows a summary of open databases in digital histopathology sorting by types of cancers. A dataset description including the goal, type of annotations, and download methods are described in each of the datasets.

## Breast Cancer

### 1. MITOS Dataset
**Goal:** Mitosis detection <br>
**Images:** 50 images (2048px\*2048px, 2252px\*2250px, 2767px\*2767px) <br>
**Annotation:** Pixel-level annotation of mitotic cells <br>
**Download:** http://ludo17.free.fr/mitos_2012/ <br>
**Cite:** <br>
```
@inproceedings{tripathi20132,
  title={2-simdom: a 2-sieve model for detection of mitosis in multispectral breast cancer imagery},
  author={Tripathi, Ardhendu Shekhar and Mathur, Atin and Daga, Mohit and Kuse, Manohar and Au, Oscar C},
  booktitle={2013 IEEE International Conference on Image Processing},
  pages={611--615},
  year={2013},
  organization={IEEE}
}
```

### MITOS-ATYPIA-14 Dataset
**Goal:** Mitosis detection <br>
**Images:** 2112 images (1663px\*1485px) <br>
**Annotation:** Centroid pixel of mitotic cells <br>
**Download:** https://mitos-atypia-14.grand-challenge.org/ <br>

### TUPAC Challenge Dataset
**Goal:** (1) Prediction of proliferation score based on mitosis counting, (2) Prediction of proliferation score based on molecular data, (3) Mitosis detection <br>
**Images:** 821 images from 73 cases <br>
**Annotation:** Proliferation scores, ROI of mitotic cells <br>
**Download:** https://tupac.grand-challenge.org/TUPAC/ <br>
**Cite:** <br>
```
@article{veta2019predicting,
  title={Predicting breast tumor proliferation from whole-slide images: the TUPAC16 challenge},
  author={Veta, Mitko and Heng, Yujing J and Stathonikos, Nikolas and Bejnordi, Babak Ehteshami and Beca, Francisco and Wollmann, Thomas and Rohr, Karl and Shah, Manan A and Wang, Dayong and Rousson, Mikael and others},
  journal={Medical image analysis},
  volume={54},
  pages={111--121},
  year={2019},
  publisher={Elsevier}
}
```

### HER2 Scoring (2016) Dataset
**Goal:** HER2 scoring in breast cancer WSIs <br>
**Images:** 86 WSIs <br>
**Annotation:** HER2 score on whole-slide level <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/her2contest (currently download is not available) <br>
**Cite:** <br>
```
@article{qaiser2018her,
  title={Her 2 challenge contest: a detailed assessment of automated her 2 scoring algorithms in whole slide images of breast cancer tissues},
  author={Qaiser, Talha and Mukherjee, Abhik and Reddy Pb, Chaitanya and Munugoti, Sai D and Tallam, Vamsi and Pitk{\"a}aho, Tomi and Lehtim{\"a}ki, Taina and Naughton, Thomas and Berseth, Matt and Pedraza, An{\'\i}bal and others},
  journal={Histopathology},
  volume={72},
  number={2},
  pages={227--238},
  year={2018},
  publisher={Wiley Online Library}
}
```

### BreakHis Dataset
**Goal:** Breast cancer detection <br>
**Images:** 7909 images (700px\*460px) from 82 patients <br>
**Annotations:** Benign vs. Malignant annotation on the WSI level <br>
**Download:** https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/ (access upon request) <br>
**Cite:** <br>
```
@article{spanhol2015dataset,
  title={A dataset for breast cancer histopathological image classification},
  author={Spanhol, Fabio A and Oliveira, Luiz S and Petitjean, Caroline and Heutte, Laurent},
  journal={Ieee transactions on biomedical engineering},
  volume={63},
  number={7},
  pages={1455--1462},
  year={2015},
  publisher={IEEE}
}
```

### CAMELYON-16 Dataset
**Goal:** Breast cancer metastasis detection <br>
**Images:** 400 WSIs <br>
**Annotations:** Contour of cancer locations (ROIs) <br>
**Download:** https://camelyon16.grand-challenge.org/Home/ <br>
**Cite:** <br>
```
@article{bejnordi2017diagnostic,
  title={Diagnostic assessment of deep learning algorithms for detection of lymph node metastases in women with breast cancer},
  author={Bejnordi, Babak Ehteshami and Veta, Mitko and Van Diest, Paul Johannes and Van Ginneken, Bram and Karssemeijer, Nico and Litjens, Geert and Van Der Laak, Jeroen AWM and Hermsen, Meyke and Manson, Quirine F and Balkenhol, Maschenka and others},
  journal={Jama},
  volume={318},
  number={22},
  pages={2199--2210},
  year={2017},
  publisher={American Medical Association}
}
```

### CAMELYON-17 Dataset
**Goal:** Breast cancer metastasis detection, pN-stage prediction <br>
**Images:** 100 WSIs <br>
**Annotations:** Contour of cancer locations (ROIs), patient level score <br>
**Download:** https://camelyon17.grand-challenge.org/Home/ <br>
**Cite:** <br>
```
@article{litjens20181399,
  title={1399 H\&E-stained sentinel lymph node sections of breast cancer patients: the CAMELYON dataset},
  author={Litjens, Geert and Bandi, Peter and Ehteshami Bejnordi, Babak and Geessink, Oscar and Balkenhol, Maschenka and Bult, Peter and Halilovic, Altuna and Hermsen, Meyke and van de Loo, Rob and Vogels, Rob and others},
  journal={GigaScience},
  volume={7},
  number={6},
  pages={giy065},
  year={2018},
  publisher={Oxford University Press}
}
```

### PCam Dataset
**Goal:** Breast Cancer metastasis detection <br>
**Images:** 294,912 patches extracted from CAMELYON-16 dataset <br>
**Annotations:** Patch-level binary label <br>
**Download:** https://github.com/basveeling/pcam <br>
**Cite:** <br>
```
@inproceedings{veeling2018rotation,
  title={Rotation equivariant cnns for digital pathology},
  author={Veeling, Bastiaan S and Linmans, Jasper and Winkens, Jim and Cohen, Taco and Welling, Max},
  booktitle={International Conference on Medical image computing and computer-assisted intervention},
  pages={210--218},
  year={2018},
  organization={Springer}
}
```

### BACH ICIAR (2018) Dataset
**Goal:** Breast cancer classification <br>
**Images:** 500 images (2048px\*1536px) <br>
**Annotations:** Image-wise and pixel-level annotations <br>
**Download:** https://iciar2018-challenge.grand-challenge.org/Home/ (access upon request) <br>
**Cite:** <br>
```
@article{aresta2019bach,
  title={Bach: Grand challenge on breast cancer histology images},
  author={Aresta, Guilherme and Ara{\'u}jo, Teresa and Kwok, Scotty and Chennamsetty, Sai Saketh and Safwan, Mohammed and Alex, Varghese and Marami, Bahram and Prastawa, Marcel and Chan, Monica and Donovan, Michael and others},
  journal={Medical image analysis},
  volume={56},
  pages={122--139},
  year={2019},
  publisher={Elsevier}
}
```

### BreastPathQ Dataset
**Goal:** Tumour cellularity scoring <br>
**Images:** 3700 images from 96 WSIs <br>
**Annotations:** 3700 patch-level tumour cellularity score <br>
**Download:** https://breastpathq.grand-challenge.org/ (access needed) <br>
**Cite:** <br>
```
@article{peikari2017automatic,
  title={Automatic cellularity assessment from post-treated breast surgical specimens},
  author={Peikari, Mohammad and Salama, Sherine and Nofech-Mozes, Sharon and Martel, Anne L},
  journal={Cytometry Part A},
  volume={91},
  number={11},
  pages={1078--1087},
  year={2017},
  publisher={Wiley Online Library}
}
```

### Post-NAT-BRCA Dataset
**Goal:** Tumour cellularity scoring <br>
**Images:** 96 images from64 patients <br>
**Annotations:** Nuclei, patch and patient level annotations <br>
**Download:** https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=52758117#52758117bcab02c187174a288dbcbf95d26179e8 <br>

## Colon Cancer

### TBC




