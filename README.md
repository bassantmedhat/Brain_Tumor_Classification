# Brain Tumor Classification using Deep Learning
## Table of contents:

- [Introduction](#dataset)
- [Technologies](#technologies)
- [Segmentation](#segmentation-phase)
- [Classification Model](#classification-model)
- [Plot Training and Validation Loss](#plot-training-and-validation-loss)
- [Model-Evaluation](#model-evaluation)

## Dataset 
- The data set consists of 14 tumor classes and 4478 MRI images. 
- 'Astrocitoma' , 'Carcinoma', 'Ependimoma', 'Ganglioglioma', 'Germinoma', 'Glioblastoma', 'Granuloma', 'Meduloblastoma', 'Meningioma', 'Neurocitoma', 'Oligodendroglioma, 'Papiloma', 'Schwannoma', 'Tuberculoma'.
- for each class :
  a) T1
  b) T1C+ (T1-weighted)
  c) T2
  
## Technologies
- NumPy
- Matplotlib
- Keras
- TensorFlow
- sklearn
- seaborn
- pandas

## Segmentation Phase
#### -- in progress --

## Classification Model
### Building Brain tumor classification model based on EfficientNetB5
- Data set consists of 29 classes and 4479 images 
- Why EfficientNet not ResNet ?

  AS EfficientNet with much smaller parameters results in better performance than RESNET with a high parameter number.
- And for top layer building

  optimizier: AdamMax, Loss function :'categorical_crossentropy', Evaluation Metric: 'Accuracy' 
  
  ![Screenshot (365)](https://user-images.githubusercontent.com/85830264/230723564-77bd23f4-2fe8-4fdd-89f1-e538c7a563d1.png)

### Samples from image classes
- Astrocitoma T1

![Screenshot (360)](https://user-images.githubusercontent.com/85830264/230207529-0137a3e4-544a-452e-9d0c-d9d692475859.png)




- Carcinoma T1

![Screenshot (361)](https://user-images.githubusercontent.com/85830264/230207590-7c59e0c5-7057-41fc-8de9-54cd09307124.png)




- Germinoma T1

![Screenshot (369)](https://user-images.githubusercontent.com/85830264/230723285-b3379e2a-04ed-473b-8857-ca419fa10638.png)




- Ganglioglioma T1 

![Screenshot (363)](https://user-images.githubusercontent.com/85830264/230207787-c451c189-f672-479b-804c-5133cf94bfb9.png)


## Labels distribution
![Screenshot (366)](https://user-images.githubusercontent.com/85830264/230722613-51631f6a-f372-4f7f-88a3-dc9348226dcd.png)

## Images per label in train data
![Screenshot (367)](https://user-images.githubusercontent.com/85830264/230722803-35501f93-8ce3-49b0-891e-0d1eb4acd73d.png)



## Plot Training and Validation Loss
![output](https://user-images.githubusercontent.com/85830264/231580173-62dbf185-c4c1-4a94-ae16-403b8e9983b2.png)


## Model Evaluation
![output (4)](https://user-images.githubusercontent.com/85830264/233827043-892862ab-2fc4-4d78-94c1-5aeaedfb13a2.png)




