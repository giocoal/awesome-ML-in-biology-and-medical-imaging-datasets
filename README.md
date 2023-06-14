# Awesome Machine Learning in Biology and Medical Imaging

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/yassouali/awesome-semi-supervised-learning/graphs/commit-activity)


<p align="center">
  <img width="300" src="https://i.imgur.com/Ky2jxnj.png" "Awesome!">
</p>

🧬☣️ An up-to-date and curated list of awesome Machine Learning in Biology and Medical Imaging project ideas, papers, datasets and repositories.

# Medical Imaging (classification/generation)

## Datasets

### MRI

- MRNet: A Dataset of Knee MRIs and Competition for Automated Knee MRI Interpretation: https://stanfordmlgroup.github.io/competitions/mrnet/

**Alzheimer's Disease**
- [OASIS Brains - Open Access Series of Imaging Studies (oasis-brains.org)](https://oasis-brains.org/)
  - [OASIS-1 Dataset](https://paperswithcode.com/dataset/oasis-1)
- [0. Classification of Alzheimer’s disease diagnosis — Deep Learning for Medical Imaging (DL4MI 2022) (inria.fr)](https://aramislab.paris.inria.fr/workshops/DL4MI/2022/notebooks/classification.html#clustering-on-ad-cn-populations)
- openfmri.org: http://openfmri.org/data-organization/
- ADNI Database
  - [ADNI |  ACCESS DATA (usc.edu)](https://adni.loni.usc.edu/data-samples/access-data/) o [IDA (usc.edu)](https://ida.loni.usc.edu/login.jsp?project=ADNI&page=HOME#)
  - [Google ADNI Group (google.com)](https://groups.google.com/g/adni-data/search?q=access)

**Brain Tumor**:

- [Brain Tumor Dataset](https://paperswithcode.com/dataset/brain-tumor-dataset) e [brain tumor dataset](https://figshare.com/articles/dataset/brain_tumor_dataset/1512427)
- [Brain Tumor MRI Dataset Dataset | Papers With Code](https://paperswithcode.com/dataset/brain-tumor-mri-dataset)
- [RSNA-MICCAI Brain Tumor Radiogenomic Classification](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification)
    - [RSNA MICCAI PNG | Kaggle](https://www.kaggle.com/datasets/jonathanbesomi/rsna-miccai-png)
- BraTS 2013-2021 [Papers With Code](https://paperswithcode.com/datasets?q=brats&v=lst&o=match)
    - [BRaTS 2021 Task 1 Dataset | Kaggle](https://www.kaggle.com/datasets/dschettler8845/brats-2021-task1) 
    - [MICCAI BRATS - The Multimodal Brain Tumor Segmentation Challenge](http://braintumorsegmentation.org/) 
    - [Brats2021Dataset | Kaggle](https://www.kaggle.com/datasets/victorfernandezalbor/brats2021dataset) 
    - [BraTS2020 Dataset (Training + Validation) | Kaggle](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation)

### X-Rays

- MURA Dataset: Towards Radiologist-Level Abnormality Detection in Musculoskeletal Radiographs: https://stanfordmlgroup.github.io/competitions/mura/
- CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning: https://stanfordmlgroup.github.io/projects/chexnet/

### CT/PET

- DeepLesion, a dataset with 32735 lesions in 32120 CT slices from 10594 studies of 4427 unique patients: https://nihcc.app.box.com/v/DeepLesion

**Lung Cancer**:
- The Cancer Imaging Archive (TCIA): https://imaging.cancer.gov/informatics/cancer_imaging_archive.htm
- A Large-Scale CT and PET/CT Dataset for Lung Cancer Diagnosis (Lung-PET-CT-Dx) - The Cancer Imaging Archive (TCIA) Public Access - Cancer Imaging Archive Wiki: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216#7022421621c64ff049c44f03bb442ec5eb88bdf2
- Chest CT-Scan images Dataset: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
- Luna16 Lung Cancer Dataset: https://www.kaggle.com/datasets/fanbyprinciple/luna-lung-cancer-dataset?select=candidates_V2
- CT Scan Images for Lung Cancer: https://www.kaggle.com/datasets/dishantrathi20/ct-scan-images-for-lung-cancer
- IQ-OTH/NCCD - Lung Cancer Dataset: https://www.kaggle.com/datasets/adityamahimkar/iqothnccd-lung-cancer-dataset

**Breast Cancer**:
- Breast Cancer CT (Fully Preprocessed); https://www.kaggle.com/datasets/sabermalek/bcfpp
- Duke Breast Cancer MRI Dataset: https://paperswithcode.com/dataset/duke-breast-cancer-mri

**COVID/Pneumonia**:
- https://www.cancerimagingarchive.net/access-data/
- Large COVID-19 CT scan slice dataset: https://www.kaggle.com/datasets/maedemaftouni/large-covid19-ct-slice-dataset
  - Curated Covid CT: https://github.com/maftouni/Curated_Covid_CT
  - COVID-CT Dataset: https://paperswithcode.com/dataset/covid-ct
  - COVIDx CT-3A: https://www.kaggle.com/datasets/hgunraj/covidxct?select=3A_images
- COVIDNet-CT: https://github.com/haydengunraj/COVIDNet-CT/blob/master/docs/dataset.md#data-distribution
- COVID-19 Lung CT Scans: https://www.kaggle.com/datasets/luisblanche/covidct?select=CT_COVID

## Papers

**COVID/Pneumonia**
- [COVID-19-Affected-Lung-CT-Image-Generative-Network/Modeling_COVID_19_Using_GANs_Paper.pdf at master · brendon-ng/COVID-19-Affected-Lung-CT-Image-Generative-Network · GitHub](https://github.com/brendon-ng/COVID-19-Affected-Lung-CT-Image-Generative-Network/blob/master/Modeling_COVID_19_Using_GANs_Paper.pdf)
- https://github.com/Arminkhayati/CovidCT_CNN-ACGAN
- [brendon-ng/COVID-19-Affected-Lung-CT-Image-Generative-Network: A Generative Adversarial Network (GAN) trained to generate artificial CT scan images of lungs infected with the COVID-19 virus. (github.com)](https://github.com/brendon-ng/COVID-19-Affected-Lung-CT-Image-Generative-Network/tree/master)
- https://github.com/ParisanSH/Training-AC-GAN-in-order-to-generate-more-images-in-COVID-Non-COVID-CT-IMAGES
- [COVID-19-Affected-Lung-CT-Image-Generative-Network/Modeling_COVID_19_Using_GANs_Paper.pdf at master · brendon-ng/COVID-19-Affected-Lung-CT-Image-Generative-Network · GitHub](https://github.com/brendon-ng/COVID-19-Affected-Lung-CT-Image-Generative-Network/blob/master/Modeling_COVID_19_Using_GANs_Paper.pdf)
- [COVID-19 Chest CT image Augmentation GAN Dataset | Kaggle](https://www.kaggle.com/datasets/mloey1/covid19-chest-ct-image-augmentation-gan-dataset)
- [COVID‐19 diagnosis on CT scan images using a generative adversarial network and concatenated feature pyramid network with an attention mechanism - PMC (nih.gov)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8420535/)
- [CCS-GAN: COVID-19 CT Scan Generation and Classification with Very Few Positive Training Images - PMC (nih.gov)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10109233/)

# Medical Imaging (segmentation)

## Datasets
- Prostate Cancer Segmentation + Grade Assessment: https://www.kaggle.com/competitions/prostate-cancer-grade-assessment/data
- 3D Teeth Scan Segmentation + Labeling: https://3dteethseg.grand-challenge.org/
- Carotid Vessel Wall Segementation + Atheosclerosos Diagnosis: https://vessel-wall-segmentation-2022.grand-challenge.org/data/
- MELA Challenge (Lung CT Lesions Detection): https://mela.grand-challenge.org/
- Immunofluorescence for Immunohistochemical from Image: https://github.com/nadeemlab/DeepLIIF
- BIDCell: Biologically-informed deep learning for cell segmentation of subcelluar spatial transcriptomics data: https://github.com/SydneyBioX/BIDCell
- Mitochondria-EM-Image-Segmentation: https://github.com/wangyiranamy/Mitochondria-EM-Image-Segmentation

## Projects

- **Retinal Layers Segmenters**: https://github.com/Beknaizer/OCT-Retinal-Layer-Segmenter

# Histopathology

## Datasets

- Lung and Colon Cancer Histopathological Images: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images

## Papers

**Generative Models**
- Generative Adversarial Networks in Digital Pathology and Histopathological Image Processing: A Review - PMC (nih.gov): https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8609288/
- Generative Augmentation Methods for Histological Image Analysis in Limited Data Conditions: https://link.springer.com/article/10.1007/s10598-023-09578-1

## Projects

# Biology

## Projects

- Binary classification of Chemical Structure / not chemical structure: https://github.com/jorgeso/biof509-final-project
- Biological Named Entity Recognition in text: https://github.com/hhkkxxx133/Biological-Named-Entity-Recognition-NER-System
- Multiple Myeloma DREAM Challenge: A crowd-sourced challenge to improve identification of high-risk patients: https://www.synapse.org/#!Synapse:syn6187098/files/
- A biologically interpretable integrative deep learning model that integrates PAthological images and GEnomic data
  - https://github.com/DataX-JieHao/PAGE-Net
  - [Integrating neuroimaging and gene expression data using the imaging transcriptomics toolbox - PMC (nih.gov)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9036395/)
- DeepConv-DTI: Prediction of drug-target interactions via deep learning with convolution on protein sequences: https://github.com/Rye-Catcher-ZCH/HITSZ-2020-Bioinformatics-Course-Project-Two-Team-zchnb


