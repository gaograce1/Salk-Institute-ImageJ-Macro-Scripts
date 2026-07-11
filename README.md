# Salk Institute – ImageJ Macro Automation for Scientific Image Analysis

## Overview

During my research at the Salk Institute, I developed a collection of **ImageJ Macro (IJM) scripts** to automate the analysis of spinal cord microscopy videos. The objective was to replace a time-intensive manual workflow with a reproducible, high-throughput image processing pipeline capable of analyzing large microscopy datasets.

The automation pipeline standardized ROI (Region of Interest) detection and quantification, significantly reducing manual image processing while improving consistency across experiments. This work supported the image analysis used in two peer-reviewed publications in **Nature Communications** and **Nature Biotechnology**.

---

## Technical Overview

The ImageJ Macro scripts automated several key image processing tasks:

- Segmented microscopy images into **10 × 10 μm Regions of Interest (ROIs)** using an automated tiling approach.
- Calculated average pixel intensity for every ROI across microscopy images.
- Applied configurable statistical thresholding using image mean and standard deviation to classify ROIs.
- Automatically identified and categorized ROIs as:
  - Blood vessel
  - Near blood vessel
  - Distant from blood vessel
- Excluded unwanted ROIs prior to downstream calcium activity analysis.
- Automated ROI generation and manipulation to create a reproducible image analysis workflow.

By eliminating manual ROI selection, the scripts enabled researchers to efficiently process thousands of microscopy frames while improving reproducibility and consistency across experiments.

---

## Technologies

- ImageJ Macro (IJM)
- Scientific Image Processing
- Threshold-Based Image Segmentation
- ROI Generation & Manipulation
- Statistical Image Analysis
- Workflow Automation

---

## Repository Contents

### [Tiling-Script.ijm](https://drive.google.com/file/d/15wRHVoVAbrOyTXsQjYzU-Et6QN-rmXsO/preview)

Automates image tiling, calculates pixel intensity statistics, and classifies Regions of Interest using configurable threshold values.

### [ROI_Manipulation.ijm](https://drive.google.com/file/d/15XQpEg39tdX3tGreMJMH9fLCfj_Tmzrs/view?usp=sharing)

Automates ROI creation, filtering, editing, and batch manipulation for downstream quantitative image analysis.

---

## Research Impact

The automation pipeline became part of the laboratory's image analysis workflow, reducing manual data processing while providing a standardized and reproducible method for quantifying microscopy data.

This work supported image analysis used in the following publications:

- **Nature Communications (2023)**  
  [*Multiplex translaminar imaging in the spinal cord of behaving mice*](https://rdcu.be/ftpjg)

- **Nature Biotechnology (2023)**  
  [*Trans-segmental imaging in the spinal cord of behaving mice*](https://rdcu.be/c6ZW9)

---

## Figures

Example screenshots from the published image analysis pipeline are included below, demonstrating:

- Original microscopy images
- ROI tiling
- Threshold-based blood vessel detection
- ROI classification
- Final quantitative analysis output

**Nature Biotechnology (2023)**  
[*Trans-segmental imaging in the spinal cord of behaving mice*](https://rdcu.be/c6ZW9)

<img width="768" height="269" alt="image" src="https://github.com/user-attachments/assets/0e9524f2-8282-468e-8b58-6236b42b818c" />

Extended Data Fig. 10 | High-speed trans-segmental imaging of sensory-evoked calcium activity in freely behaving GFAP-GCaMP6f mice. a,b, Average intensity projection images from a time-lapse recording in a freely moving  GFAP-GaMP6f mouse (Supplementary Video 8) taken at ~50 μm focal depth below the pia overlaid with ~10 μm × 10 μm ROIs. Only active ROIs above the indicated ΔF/F thresholds in response to an innocuous tail pinch/touch (p < 200 g) (a) or a noxious tail pinch (>500 g) (b) are shown. 



**Nature Communications (2023)**  
[*Multiplex translaminar imaging in the spinal cord of behaving mice*](https://rdcu.be/ftpjg)

<img width="259" height="341" alt="image" src="https://github.com/user-attachments/assets/d45cad35-bd7d-450c-9dd1-810e393a9986" />

[Fig. 4: High-speed translaminar imaging reveals region-specific sensory and motor-evoked activity in behaving GFAP-GCaMP6f mice.](https://www.nature.com/articles/s41467-023-36959-2/figures/4)

<img width="259" height="341" alt="image" src="https://github.com/user-attachments/assets/8fe540c5-5cba-4273-aea8-2311415b2455" />

[Fig. 5: High-speed translaminar imaging reveals noxious mechanical stimulus-evoked activity in the spinal cord of behaving Tac1-GCaMP6f mice.](https://www.nature.com/articles/s41467-023-36959-2/figures/5)


