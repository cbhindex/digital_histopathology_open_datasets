# A Summary of Digital Histopathology Open Datasets

This document shows a summary of open databases in digital histopathology sorting by types of cancers. A dataset description including the goal, type of annotations, and download methods are described in each of the datasets.

## 1.Breast Cancer

### 1.1 MITOS Dataset
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

### 1.2 MITOS-ATYPIA-14 Dataset
**Goal:** Mitosis detection <br>
**Images:** 2112 images (1663px\*1485px) <br>
**Annotation:** Centroid pixel of mitotic cells <br>
**Download:** https://mitos-atypia-14.grand-challenge.org/ <br>

### 1.3 TUPAC Challenge Dataset
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

### 1.4 HER2 Scoring (2016) Dataset
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

### 1.5 BreakHis Dataset
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

### 1.6 CAMELYON-16 Dataset
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

### 1.7 CAMELYON-17 Dataset
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

### 1.8 PCam Dataset
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

### 1.9 BACH ICIAR (2018) Dataset
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

### 1.10 BreastPathQ Dataset
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

### 1.11 Post-NAT-BRCA Dataset
**Goal:** Tumour cellularity scoring <br>
**Images:** 96 images from 64 patients <br>
**Annotations:** Nuclei, patch and patient level annotations <br>
**Download:** https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=52758117#52758117bcab02c187174a288dbcbf95d26179e8 <br>

### 1.12 ER+ Breast Cancer Dataset by Andrew Janowczyk
**Goal:** (1) ER+ breast cancer nuclei segmentation, (2) Epithelium region segmentation, (3) Lymphocyte detection, (4) Mitosis detection, (5) Invasive ductal carcinoma (IDC) identification, (6) Lymphoma subtype classification <br>
**Images:** (1) 12,000 nuclei from 143 images (2000px\*2000px) for nuclei segmentation, (2) 42 images (1000px\*1000px) for epithelium segmentation, (3) 100 images (100px\*100px) for lymphocyte detection, (4) 311 images (2000px\*2000px) from 12 patients for mitosis detection, (5) 277,524 images (50px\*50px) from 162 WSIs for IDC identification, (6) 374 images (1388px\*1040px) for lymphoma subtype classification <br>
**Annotations:** (1) Pixel-level nuclei annotation, (2) Pixel-level epithelium annotation, (3) The centers of 3,064 lymphocytes, (4) 550 mitosic centers, (5) binary label for IDC classification, (6) lymphoma subtype labels <br>
**Download (1):** http://andrewjanowczyk.com/use-case-1-nuclei-segmentation/ <br>
**Download (2):** http://andrewjanowczyk.com/use-case-2-epithelium-segmentation/ <br>
**Download (3):** http://andrewjanowczyk.com/use-case-4-lymphocyte-detection/ <br>
**Download (4):** http://andrewjanowczyk.com/use-case-5-mitosis-detection/ <br>
**Download (5):** http://andrewjanowczyk.com/use-case-6-invasive-ductal-carcinoma-idc-segmentation/ <br>
**Download (6):** http://andrewjanowczyk.com/use-case-7-lymphoma-sub-type-classification/ <br>
**Cite:** <br>
```
@article{janowczyk2016deep,
  title={Deep learning for digital pathology image analysis: A comprehensive tutorial with selected use cases},
  author={Janowczyk, Andrew and Madabhushi, Anant},
  journal={Journal of pathology informatics},
  volume={7},
  year={2016},
  publisher={Wolters Kluwer--Medknow Publications}
}
```

## 2.Colon Cancer

### 2.1 GlAS Dataset (MICCAI 2015)
**Goal:** Gland segmentation <br>
**Images:** 165 WSIs at x20 magnification <br>
**Annotations:** Glandular boundaries <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest/ <br>
**Cite:** <br>
```
@article{sirinukunwattana2017gland,
  title={Gland segmentation in colon histology images: The glas challenge contest},
  author={Sirinukunwattana, Korsuk and Pluim, Josien PW and Chen, Hao and Qi, Xiaojuan and Heng, Pheng-Ann and Guo, Yun Bo and Wang, Li Yang and Matuszewski, Bogdan J and Bruni, Elia and Sanchez, Urko and others},
  journal={Medical image analysis},
  volume={35},
  pages={489--502},
  year={2017},
  publisher={Elsevier}
}
```
```
@article{sirinukunwattana2015stochastic,
  title={A stochastic polygons model for glandular structures in colon histology images},
  author={Sirinukunwattana, Korsuk and Snead, David RJ and Rajpoot, Nasir M},
  journal={IEEE transactions on medical imaging},
  volume={34},
  number={11},
  pages={2366--2378},
  year={2015},
  publisher={IEEE}
}
```

### 2.2 CoNSep Dataset
**Goal:** Nuclei segmentation and classification <br>
**Images:** 24,319 exhaustively annotated nuclei with associated class labels <br>
**Annotations:** Pixel-level nuclei annotation with associated class labels <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/hovernet/ <br>
**Cite:* <br>
```
@article{graham2019hover,
  title={Hover-net: Simultaneous segmentation and classification of nuclei in multi-tissue histology images},
  author={Graham, Simon and Vu, Quoc Dang and Raza, Shan E Ahmed and Azam, Ayesha and Tsang, Yee Wah and Kwak, Jin Tae and Rajpoot, Nasir},
  journal={Medical Image Analysis},
  volume={58},
  pages={101563},
  year={2019},
  publisher={Elsevier}
}
```

### 2.3 NCT-CRC-HE-100k Dataset
**Goal:** Tissue classification <br>
**Images:** 107,180 patches from 111 WSIs <br>
**Annotations:** Patch-label for nine class tissue classification <br>
**Download:** https://zenodo.org/record/1214456#.YRkK6ogzaMp <br>
**Cite:** <br>
```
@article{kather2018100,
  title={100,000 histological images of human colorectal cancer and healthy tissue},
  author={Kather, Jakob Nikolas and Halama, Niels and Marx, Alexander},
  journal={URL: https://doi. org/10.5281/zenodo},
  volume={1214456},
  year={2018}
}
```

### 2.4 CRAG (2019) Dataset
**Goal:** Gland segmentation <br>
**Images:** 213 images <br>
**Annotations:** Gland instance-level ground truth <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/mildnet/ <br>
**Cite:** <br>
```
@article{graham2019mild,
  title={MILD-Net: Minimal information loss dilated network for gland instance segmentation in colon histology images},
  author={Graham, Simon and Chen, Hao and Gamper, Jevgenij and Dou, Qi and Heng, Pheng-Ann and Snead, David and Tsang, Yee Wah and Rajpoot, Nasir},
  journal={Medical image analysis},
  volume={52},
  pages={199--211},
  year={2019},
  publisher={Elsevier}
}
```
```
@article{awan2017glandular,
  title={Glandular morphometrics for objective grading of colorectal adenocarcinoma histology images},
  author={Awan, Ruqayya and Sirinukunwattana, Korsuk and Epstein, David and Jefferyes, Samuel and Qidwai, Uvais and Aftab, Zia and Mujeeb, Imaad and Snead, David and Rajpoot, Nasir},
  journal={Scientific reports},
  volume={7},
  number={1},
  pages={1--12},
  year={2017},
  publisher={Nature Publishing Group}
}
```

### 2.5 CRCHistoPhenotypes Dataset
**Goal:** Nuclei detection and classification <br>
**Images:** 29,756 nuclei from 100 WSIs <br>
**Annotations:** 29,756 nuclei centres out of which 22,444 with associated class labels <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/crchistolabelednucleihe/ <br>
**Cite:** <br>
```
@article{sirinukunwattana2016locality,
  title={Locality sensitive deep learning for detection and classification of nuclei in routine colon cancer histology images},
  author={Sirinukunwattana, Korsuk and Raza, Shan E Ahmed and Tsang, Yee-Wah and Snead, David RJ and Cree, Ian A and Rajpoot, Nasir M},
  journal={IEEE transactions on medical imaging},
  volume={35},
  number={5},
  pages={1196--1206},
  year={2016},
  publisher={IEEE}
}
```

### 2.6 Colorectal Cancer Grading Dataset & Extended Colorectal Cancer Grading Dataset
**Goal:** Colorectal Cancer Grading <br>
**Images:** 139 images (4548px\*7548px) <br> plus 300 images (4548px\*7548px) in Extended Colorectal Cancer Grading Dataset <br>
**Annotations:** Cancer grading on the image level <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/crc_grading/ and https://warwick.ac.uk/fac/cross_fac/tia/data/extended_crc_grading/ <br>
**Cite:** <br>
```
@article{awan2017glandular,
  title={Glandular morphometrics for objective grading of colorectal adenocarcinoma histology images},
  author={Awan, Ruqayya and Sirinukunwattana, Korsuk and Epstein, David and Jefferyes, Samuel and Qidwai, Uvais and Aftab, Zia and Mujeeb, Imaad and Snead, David and Rajpoot, Nasir},
  journal={Scientific reports},
  volume={7},
  number={1},
  pages={1--12},
  year={2017},
  publisher={Nature Publishing Group}
}
```
```
@article{shaban2020context,
  title={Context-aware convolutional neural network for grading of colorectal cancer histology images},
  author={Shaban, Muhammad and Awan, Ruqayya and Fraz, Muhammad Moazam and Azam, Ayesha and Tsang, Yee-Wah and Snead, David and Rajpoot, Nasir M},
  journal={IEEE transactions on medical imaging},
  volume={39},
  number={7},
  pages={2395--2405},
  year={2020},
  publisher={IEEE}
}
```

## 3.Pan Cancer

### 3.1 PanNuke Dataset
**Goal:** Nuclei segmentation and classification <br>
**Images:** 205,343 labeled nuclei from 481 visual fields <br>
**Annotations:** Pixel-level nuclei annotation with associated class labels <br>
**Download:** https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke and https://jgamper.github.io/PanNukeDataset/ <br>
**Cite:** <br>
```
@inproceedings{gamper2019pannuke,
  title={PanNuke: an open pan-cancer histology dataset for nuclei instance segmentation and classification},
  author={Gamper, Jevgenij and Koohbanani, Navid Alemi and Benes, Ksenija and Khuram, Ali and Rajpoot, Nasir},
  booktitle={European Congress on Digital Pathology},
  pages={11--19},
  year={2019},
  organization={Springer}
}
```
```
@article{gamper2020pannuke,
  title={PanNuke Dataset Extension, Insights and Baselines},
  author={Gamper, Jevgenij and Koohbanani, Navid Alemi and Graham, Simon and Jahanifar, Mostafa and Khurram, Syed Ali and Azam, Ayesha and Hewitt, Katherine and Rajpoot, Nasir},
  journal={arXiv preprint arXiv:2003.10778},
  year={2020}
}
```

### 3.2 MoNuSeg Dataset
**Goal:** Nuelci segmentation <br>
**Images:** 29,000 nuclei from 44 images <br>
**Annotations:** Pixel-level nuclei annotation <br>
**Download:** https://monuseg.grand-challenge.org/Home/ <br>
**Cite:** <br>
```
@article{kumar2017dataset,
  title={A dataset and a technique for generalized nuclear segmentation for computational pathology},
  author={Kumar, Neeraj and Verma, Ruchika and Sharma, Sanuj and Bhargava, Surabhi and Vahadane, Abhishek and Sethi, Amit},
  journal={IEEE transactions on medical imaging},
  volume={36},
  number={7},
  pages={1550--1560},
  year={2017},
  publisher={IEEE}
}
```

### 3.3 LYON Dataset
**Goal:** Lymphocyte detection <br>
**Images:** 83 WSIs <br>
**Annotations:** 171,166 lymphocytes in 932 ROIs were annotated <br>
**Download:** https://lyon19.grand-challenge.org/Home/ <br>
**Cite:** <br>
```
@article{swiderska2019learning,
  title={Learning to detect lymphocytes in immunohistochemistry with deep learning},
  author={Swiderska-Chadaj, Zaneta and Pinckaers, Hans and van Rijthoven, Mart and Balkenhol, Maschenka and Melnikova, Margarita and Geessink, Oscar and Manson, Quirine and Sherman, Mark and Polonia, Antonio and Parry, Jeremy and others},
  journal={Medical image analysis},
  volume={58},
  pages={101547},
  year={2019},
  publisher={Elsevier}
}
```

## 4.Lung Cancer

### 4.1 ACDC-LungHP (2019) Dataset
**Goal:** Detection and classification of lung cancer subtypes <br>
**Images:** 200 WSIs <br>
**Annotations:** Contour of cancer locations plus image-level cancer subtype scores <br>
**Download:** https://acdc-lunghp.grand-challenge.org/ <br>
**Cite:** <br>
```
@inproceedings{reddy2021biomedical,
  title={Biomedical image classification using deep convolutional neural networks--overview},
  author={Reddy, M Bharath Simha and Rana, Pooja},
  booktitle={IOP Conference Series: Materials Science and Engineering},
  volume={1022},
  number={1},
  pages={012020},
  year={2021},
  organization={IOP Publishing}
}
```


