## Explainable AI (Bachelor Thesis)
This repository contains material and experiments used in my thesis about XAI (Explainable AI).  It's possible to use different models and explain the results through different libraries. It's  also possible to execute some adversarial attacks on the images and check the returned explanation.

## Install
The libraries used are  
- lime https://github.com/marcotcr/lime
- shap https://github.com/slundberg/shap
- tf-explain https://github.com/sicara/tf-explain
- adversarial-robustness-toolbox https://github.com/Trusted-AI/adversarial-robustness-toolbox
  
For all the libraries it's possible the installation with pip

## Screenshots
#### Lime 
<img src="https://user-images.githubusercontent.com/79462238/128388947-6088133a-dc22-40fe-9633-d257b069515b.png" width="500" height="400">

#### Shap Gradient Explainer
<img src="https://user-images.githubusercontent.com/79462238/128388977-51593f7b-caf7-4105-8b22-54054f9eaf00.png" width="500" height="600">

#### Shap Kernel Explainer
<img src="https://user-images.githubusercontent.com/79462238/128389006-a46d516c-b0f5-426d-b08b-317ca8d79d1b.png" width="500" height="400">

#### tf-explain
<img src="https://user-images.githubusercontent.com/79462238/128389041-8e2c7287-346a-415d-8495-8a8ecd491dfc.png" width="500" height="400">

#### ART Toolbox
<img src="https://user-images.githubusercontent.com/79462238/128389087-42ace7dc-d2c4-4f6a-bfa0-712d60f90e76.png" width="500" height="400">



## Notebooks
Through these Notebooks it's possible to replicate the experiments using pictures of choice
- [Lime](/XAI_libraries/imageExplain(lime).ipynb)
- [Shap Gradient Explainer](/XAI_libraries/imageExplain(shap).ipynb)
- [Shap Kernel Explainer](/XAI_libraries/imageExplain(shap2).ipynb)
- [tf-explain](/XAI_libraries/imageExplain(tfexplain).ipynb)
- [Adversarial Attacks](/Adversarial_Attacks/attacks.ipynb)



