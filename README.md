# Skin-lesions-classification
This repo includes classifier trained to distinct 7 type of skin lesions.
## Dataset
Dataset consists of 10015 images which describe 7 type of lesions.
Dataset includes images of following 7 skin lesions:
* Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
* basal cell carcinoma (bcc)
* benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl)
* dermatofibroma (df)
* melanoma (mel)
* melanocytic nevi (nv) 
* vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc)

Dataset link https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000

## Model Training
The following CNN models are used:
* InceptionV3
* Resnet152
* VGG19
* Xception
* Ensemble

## Results
| Model | Accuracy |
| ----- | -------- |
| InceptionV3 | 0.862 |
| Resnet152 | 0.802 |
| VGG19 | 0.835 |
| Xception | 0.862 |
| Ensemble | 0.875 |

## Conclusion
Out of all the algorithms used, Ensemble of Xception, Resnet152, InceptionV3 gives the best accuracy of 0.8753.
