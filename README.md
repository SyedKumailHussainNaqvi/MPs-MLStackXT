# [MPs-MLStackXT:Machine Learning-Driven Microplastics Identification Using Ensemble Stacking with Extra Tree Meta-Models from FTIR Data](https://doi.org/10.1016/j.jece.2025.118315))  

Implementation of MPs-MLStackXT, by Syed Kumail Hussain Naqvi & Co. authors.

---

## Highlights
- A novel ensemble **MLStackXT** model is developed to classify microplastics.  
- Model achieves **95.85% accuracy** on Kedzierski, and **95.00%** on Jung datasets.  
- Confusion matrix shows **100% accuracy in 8 of 12 microplastic categories**.  
- Outperforms previous ML and DL models in **kappa, F1-score, and accuracy**.  
- Promotes accurate, transparent plastic pollution monitoring via AI.  

---

## Abstract
Microplastics (MPs) have become a major global environmental issue in recent decades due to their widespread presence in oceans, bioavailability, and ability to carry toxic chemicals.  
Attenuated Total Reflectance Fourier-Transform Infrared (ATR-FTIR) spectroscopy is widely used for MPs identification and analysis, but it faces challenges such as class imbalance, spectral similarities, and fouling, which hinder data accuracy and classification.  

This study proposes **MLStackXT**, a stacking-based machine learning (ML) model designed to enhance MPs classification by addressing these challenges using FTIR spectral datasets. The model was trained and validated using the **Kedzierski** and **Jung** datasets.  

It demonstrated superior performance compared to previous ML and deep learning (DL) approaches, including support vector machines (SVMs), ensemble learning, and deep neural networks (DNNs).  

- On the **Kedzierski** dataset, MLStackXT achieved **95.85% accuracy**, with a **kappa score of 94.96%**, **F1-score of 95.73%**, **recall of 95.85%**, and **precision of 96.10%**.  
- On the **Jung** dataset, the model attained **95.00% accuracy**, a **kappa score of 91.28%**, an **F1-score of 94.78%**, a **recall of 95.00%**, and a **precision of 94.81%**.  

Confusion matrix analysis confirmed a significant reduction in misclassification, achieving **100% accuracy in 8 out of 12 MPs categories (Kedzierski)** and over **97% accuracy in 4 out of 5 MPs categories (Jung)**.  

Model optimization via **Optuna** and interpretability analysis using **SHAP** highlighted the influence of **PCA** and key spectral features on classification performance.  
In addition, MLStackXT outperformed various stacking configurations, demonstrating its robustness and effectiveness for MPs detection.  
## Citation
Please cite the following article if you find our work helpful:

 K. Shahzad, S.K.H. Naqvi, A. Hussain, R. Irshad, K.T. Chong & S. H. Park.  
Machine Learning-Driven Microplastics Identification Using Ensemble Stacking with Extra Tree Meta-Models from FTIR Data.  
Journal of Environmental Chemical Engineering (2025).  
[https://doi.org/10.1016/j.jece.2025.118315](https://doi.org/10.1016/j.jece.2025.118315)) 

## Questions / Contact
If you have any questions, feel free to open an issue on this repository or reach out to us directly:  
[syedkumailhussainnaqvi@jbnu.ac.kr](mailto:syedkumailhussainnaqvi@jbnu.ac.kr)
