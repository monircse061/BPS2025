<img width="3920" height="2544" alt="bps_detailed_analysis" src="https://github.com/user-attachments/assets/c589111c-7c59-4697-9099-83b1065eb87a" /># Bangla Primary Script 2025 (BPS2025) Dataset

## Overview
The Bangla Primary Script 2025 (BPS2025) is a novel, demographically-oriented dataset of isolated handwritten Bangla characters and numerals specifically collected from young primary school students in Bangladesh. This dataset addresses a significant gap in existing benchmarks by capturing the formative and variable handwriting styles of children aged 7-12.

## Key Features
- **First large-scale dataset** focused exclusively on young Bangla learners (primary school students)
- **24,420 processed images** across **60 balanced classes**
- **500 students** from grades 2-5 across four districts in Bangladesh
- **Demographic metadata** including age, gender, grade, and district
- **Two versions available**: raw scanned data and pre-processed data
- **No artificial augmentation** applied to preserve authenticity

## Dataset Structure
The dataset consists of 60 classes:
- **Classes 00-49**: Basic Bangla characters (11 vowels, 39 consonants)
- **Classes 50-59**: Digits (0-9)

### File Organization
<img width="504" height="334" alt="image" src="https://github.com/user-attachments/assets/ceb9c423-ad95-4be0-a885-87ccc1c7357b" />

## Data Collection
- **Participants**: 500 primary school students (aged 7-12, grades 2-5)
- **Geographic distribution**: Four districts in Bangladesh
- **Collection method**: Scanned handwritten samples on standardized forms
- **Ethical considerations**: Collected with appropriate consent and anonymized

## Pre-processing Pipeline
The processed data underwent a 5-stage pre-processing pipeline:
1. **Image binarization** (conversion to black and white)
2. **Noise removal** (elimination of scanning artifacts)
3. **Border cropping** (removal of unnecessary margins)
4. **Size normalization** (standardization to uniform dimensions)
5. **Quality filtering** (removal of incomplete or damaged samples)



## Intended Uses
- **Handwritten Character Recognition (HCR)**: Developing robust OCR models for Bangla script
- **Educational Technology**: Building tools for automated grading and learning assessment
- **Demographic Studies**: Investigating age and gender patterns in early handwriting development
- **Deep Learning Research**: Benchmarking CNN, Transformer, and transfer learning models
- **Computer Vision Applications**: Image classification and pattern recognition research
  
## Citation

If you use the BPS2025 dataset in your research, please cite:

**BibTeX:**
```bibtex
@dataset{atique2025bps2025,
  author = {Atique, Md Monir Ahammod Bin},
  title = {BPS2025: A Demographically Focused Dataset of Handwritten Bangla Primary Script for Early Writer Recognition},
  year = {2025},
  version = {3},
  publisher = {Mendeley Data},
  doi = {10.17632/mt6jfkxprj.3},
  url = {https://doi.org/10.17632/mt6jfkxprj.3}
}
