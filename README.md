# ML-PBE
This repository constains orginial source codes and dataset for the research manuscript "Wang, Jingchun; Zhang, DaDi; Xu, Rui-Xue; Yam, ChiYung; Chen, GuanHua; Zheng, Xiao (2021): Improving Density Functional Prediction of Molecular Thermochemical Properties with a Machine-Learning-Corrected Generalized Gradient Approximation. ChemRxiv. Preprint. https://doi.org/10.26434/chemrxiv.14595321.v1".


The machine learning model is trained with a sklearn wrapper of XGBoost. We adopted the GPU version of XGBoost and thus specific version of XGBoost, along with other necessary packages imported in our codes, should be installed to make the codes work properly. On the linux platform with Anaconda, you could type " conda install -c anaconda py-xgboost-gpu " to get the XGBoost. 


Thanks again for Tianqi Chen et al. for the elegant ML library (https://xgboost.ai/).
