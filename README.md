# GenGapCHIRA2024

![alt text](https://github.com/ukuhl/GenGapCHIRA2024/blob/d1198d11ebd319c7f9b626913be732fdf84ec3f4/GenGap_stats/GenGap_Fig2_Example_Images.png)

This repository contains the data and experimental code accompanying the paper 

> Lüdemann, R., Schulz, A., & Kuhl, U. (2024). Generation Gap or Diffusion Trap? How Age Affects the Detection of Personalized AI-Generated Images. 8th International Conference on Computer-Human Interaction Research and Applications, CHIRA 2024, Porto, Portugal. (*Accepted*)

## Abstract

AI-generated content, particularly artificially generated im- age data, presents a fascinating challenge as it blurs the line between reality and fabrication in digital media. This study explores the ability of different age groups to distinguish between real and AI-generated images, using a custom model based on Stable Diffusion to create personalized synthetic images of the same individual. Participants (N=112) showed an overall accuracy of 87.0%, with younger individuals outperforming older ones in both detection accuracy and confidence. Older participants also took longer to make their decisions, indicating either an age-related de- cline in processing speed, or a more careful and deliberate analysis of the presented content. These findings highlight the importance of improving digital literacy across age groups and developing robust detection tools to better equip users to navigate an increasingly AI-driven digital landscape.

## Ressources used for model training / image generation in `GenGap_dreambooth`:

- `GenGap_dreambooth/class-images`:
  - images generated using the "class prompt" (in our case, "a man"), important to preserve this concept in DreamBooth training
- `GenGap_dreambooth/instance-images`:
  - images representing the visual concept we will be teaching the model
- `GenGap_dreambooth/GenGap_dreambooth_training_and_generation.ipynb`:
- [GenGap_dreambooth/GenGap_dreambooth_training_and_generation.ipynb](GenGap_dreambooth/GenGap_dreambooth_training_and_generation.ipynb) <a target="_blank" href="LINK"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
  - notebook detailing the training process and subsequent image generation process

## Ressources used in user study in `GenGap_studyData`:

- `GenGap_studyData/GenGap_images/*`:
  - final image dataset used in user study, separated in subdirectories `artificial`, `real`, and `validation`.
- `GenGap_studyData/GenGap_surveyData.xlsx`:
  - raw data obtained from user study
- `GenGap_studyData/GenGap_surveyStructure_limesurvey.lss`:
  - structure of the entire survey (groups, questions, subquestions, answers, and conditions); XML file

## Statistical analysis in `GenGap_stats`:

- `GenGap_studyData/GenGap_a-priori-poweranalysis.R`:
  - R script to perform a-priori power analysis
- [GenGap_stats/GenGap_userStudy_evaluation.ipynb](GenGap_stats/GenGap_userStudy_evaluation.ipynb) <a target="_blank" href="https://colab.research.google.com/github/ukuhl/GenGapCHIRA2024/blob/be31358288e7a0f051f94559e6cf55da50567cff/GenGap_stats/GenGap_userStudy_evaluation.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
  - notebook detailing the entire statistical analysis of user data

## License

TO DO: MIT license - See LICENSE.

## How to cite

Lüdemann, R., Schulz, A., & Kuhl, U. (2024). Generation Gap or Diffusion Trap? How Age Affects the Detection of Personalized AI-Generated Images. 8th International Conference on Computer-Human Interaction Research and Applications, CHIRA 2024, Porto, Portugal. (*Accepted*)
