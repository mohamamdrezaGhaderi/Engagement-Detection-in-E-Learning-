# Engagement Detection in E-Learning Environments
This repository contains the implementation and results of a research study focused on detecting engagement levels in e-learning environments using interpretable machine learning models.
The study leverages facial and behavioral features to classify engagement levels, contributing to the development of adaptive and personalized educational technologies.
# Overview
Engagement is a critical factor influencing learning outcomes and user satisfaction in online education. This research proposes a robust and interpretable framework for engagement detection, utilizing features derived from facial behavior and machine learning techniques.
The approach aims to classify engagement into levels such as very low, low, medium, and high based on behavioral patterns.
The research was conducted using balanced datasets and advanced machine learning models, achieving state-of-the-art results in engagement classification. Key features, such as Head Tilt, Eyebrow Distance, and Eye Area, were identified as significant predictors of engagement levels, enhancing the interpretability of the classification process.

# Features

  ##   1_Facial and Behavioral Metrics:
        Head Tilt
        Eyebrow Distance
        Mouth Area
        Eye Area
        Aspect Ratios (e.g., EAR, MAR)

   ## 2_Machine Learning Models:
        Random Forest
        XGBoost
        Neural Network
        Stacking Ensemble Model (Achieved the highest accuracy of 91.04%)

  ##  3_Key Contributions:
        A comprehensive analysis of feature importance for interpretable engagement detection.
        Multimodal approaches integrating facial and behavioral features.
        Practical insights into designing adaptive e-learning systems.
# Dataset

The study utilizes the DAiSEE dataset, which contains video snippets annotated for engagement-related affective states such as boredom, confusion, engagement, and frustration. This dataset is a benchmark in the field, providing naturalistic settings for machine learning research.

To download the DAiSEE dataset (due to its large size), please visit the following link:

https://docs.google.com/forms/d/e/1FAIpQLSeRIjWnqBNqhFaIMnmUshkQJ6gH_HWuN425JRK_WYTPJ1pSHQ/viewform?usp=sf_link

Ensure you adhere to the dataset's terms of use and cite the original work when utilizing this resource.


Certainly! Below is a detailed README draft for your GitHub repository, tailored to explain your research effectively while providing guidance on accessing the DAiSEE dataset.
Engagement Detection in E-Learning Environments

This repository contains the implementation and results of a research study focused on detecting engagement levels in e-learning environments using interpretable machine learning models. The study leverages facial and behavioral features to classify engagement levels, contributing to the development of adaptive and personalized educational technologies.
Overview

Engagement is a critical factor influencing learning outcomes and user satisfaction in online education. This research proposes a robust and interpretable framework for engagement detection, utilizing features derived from facial behavior and machine learning techniques. The approach aims to classify engagement into levels such as very low, low, medium, and high based on behavioral patterns.

The research was conducted using balanced datasets and advanced machine learning models, achieving state-of-the-art results in engagement classification. Key features, such as Head Tilt, Eyebrow Distance, and Eye Area, were identified as significant predictors of engagement levels, enhancing the interpretability of the classification process.
Features

    Facial and Behavioral Metrics:
        Head Tilt
        Eyebrow Distance
        Mouth Area
        Eye Area
        Aspect Ratios (e.g., EAR, MAR)

    Machine Learning Models:
        Random Forest
        XGBoost
        Neural Network
        Stacking Ensemble Model (Achieved the highest accuracy of 91.04%)

    Key Contributions:
        A comprehensive analysis of feature importance for interpretable engagement detection.
        Multimodal approaches integrating facial and behavioral features.
        Practical insights into designing adaptive e-learning systems.

Dataset

The study utilizes the DAiSEE dataset, which contains video snippets annotated for engagement-related affective states such as boredom, confusion, engagement, and frustration. This dataset is a benchmark in the field, providing naturalistic settings for machine learning research.

To download the DAiSEE dataset (due to its large size), please visit the following link:

Download DAiSEE Dataset

Ensure you adhere to the dataset's terms of use and cite the original work when utilizing this resource.
Installation and Setup


# Results

The study achieved the following key results:

    Stacking Ensemble Model outperformed other models with an accuracy of 91.04%.
    Features like Head Tilt and Eyebrow Distance emerged as the most significant predictors of engagement levels.
    A balanced dataset and multimodal approaches addressed common challenges such as data imbalance and interpretability.

