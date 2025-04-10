# Plant Leaf Disease classifier

Plant disease detection through computer vision has emerged as a transformative solution for crop management, offering automation and accuracy in identifying diseases affecting crops. Typically, symptoms of diseases manifest on plant leaves, making leaf images a primary source for detection. Convolutional Neural Networks (CNNs) provide a rapid alternative to manual inspection, efficiently processing visual data and automatically learning relevant features for accurate disease detection. Despite the potential benefits, challenges such as variability in symptoms across species, unpredictable image characteristics, and the difficulty in delineating healthy and diseased regions persist. To address these, our research employs ResNet18, MobileNetV2, and InceptionV3 CNN architectures, aiming to develop robust solutions through rigorous experimentation and evaluation. By advancing agricultural practices and ensuring sustainable food production, we strive to contribute to global food security efforts.

This project aims to conduct a comparative analysis of Convolutional Neural Networks (CNNs) for the classification of plant diseases using three distinct datasets. 
## Datasets
| Name  | size |  Link |
| ------------- | ------------- | ------------- |
| Plant Leaf Disease  |  1.5 Gb (61K Images)  | https://data.mendeley.com/datasets/tywbtsjrjv/1  |
 Tomato Leaf Disease  | 1 Gb (16K Images)  |  https://www.kaggle.com/datasets/ashishmotwani/tomato |
| Corn Maize dataset  | 500 Mb (3.5k Images)  | https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset |

## Folder Structure
    .
    ├── Plant Leaf                     # Dataset 1
    │   ├── ..                         # respective model folders
    ├── Tomato Leaf                    # Dataset 2
        ├── Inceptionv3                # Model 1
        │   ├── inceptionV3.ipynb      # Model notebook     
        │   ├── results                # contains all the plots and results of the model trained.  
    │   ├── MobilenetV2               
    │   ├── Resnet18                     
    ├── Corn Maize                     # Dataset 3
    │   ├── ..                         # respective model folders
    ├── report                         # Contains the project report along with the TSNE plot
    ├── requirement.txt                # library requirement
    ├── HP_tuning                      # results and code for hyperparameter tuning
       │   ├── results                 # contains all the plots and results of the hyper parameter tuning trained.  
    └── README.md

## Requirements

The following are the basic libraries that are required for the notebooks

[![Python][Python.js]][Python-url]
[![torch][torch.js]][torch-url]
[![torch.nn, torch.nn.functional][torch.nn.js]][torch.nn-url]
[![torch.utils.data][torch.utils.data.js]][torch.utils.data-url]
[![torchvision][torchvision.js]][torchvision-url]
[![sklearn][sklearn.js]][sklearn-url]
[![torchsummary][torchsummary.js]][torchsummary-url]
[![pandas][pandas.js]][pandas-url]
[![numpy][numpy.js]][numpy-url]
[![matplotlib][matplotlib.js]][matplotlib-url]

[Python.js]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[torch.js]: https://img.shields.io/badge/torch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[torch-url]: https://pytorch.org/
[torch.nn.js]: https://img.shields.io/badge/torch.nn%2C%20torch.nn.functional-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[torch.nn-url]: https://pytorch.org/docs/stable/nn.html
[torch.utils.data.js]: https://img.shields.io/badge/torch.utils.data-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[torch.utils.data-url]: https://pytorch.org/docs/stable/data.html
[torchvision.js]: https://img.shields.io/badge/torchvision.datasets%2C%20torchvision.transforms%2C%20torchvision.models-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[torchvision-url]: https://pytorch.org/vision/
[sklearn.js]: https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white
[sklearn-url]: https://scikit-learn.org/stable/
[torchsummary.js]: https://img.shields.io/badge/torchsummary-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[torchsummary-url]: https://github.com/sksq96/pytorch-summary
[pandas.js]: https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[pandas-url]: https://pandas.pydata.org/
[numpy.js]: https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white
[numpy-url]: https://numpy.org/
[matplotlib.js]: https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white
[matplotlib-url]: https://matplotlib.org/

For installing other dependencies, please run the following command

```
pip install requirement.txt
```
## How to run the project

Install the requirements for the project.

- To run the project, get the sample dataset from the following link.

- Change the directory path in the model that needs to be trained with.
- Get the pretrained model and their weight and the run the notebook.

## Train and validation of models
The code for training and validating the models are present inside the respective model folder for the dataset. Along with that, a pretrained model files are also available in the name of ```.pth``` format. 

Video Presentation: 

https://liveconcordia-my.sharepoint.com/:f:/g/personal/r_periya_live_concordia_ca/ElDlh9aNHQtHhcoD5qBYv3IBHQbahIUZxi2We766z-xeNQ?e=a2t2y7

Sample dataset: 
https://liveconcordia-my.sharepoint.com/:f:/g/personal/r_periya_live_concordia_ca/Et5CtiRbvi9DpGjmICP5ExcByKXrU9DFsbDXKfXIwB2kdw?e=IWdopc

### Contributors

- Dinesh Kumar Gopinathan, (dineshkumar.gopinathan@mail.concordia.ca)
- Fiza Altaf Razvi, (fizarazvi10@gmail.com)
- Ramprakash Periyagaram Ganesan, (rampg23@gmail.com)
- Sanjay Bharathi Subramanian, (sanjaystz98@gmail.com)

### Collaborators
- GitHub ID: mahdihosseini, (mahdi.hosseini@mail.utoronto.ca)
- GitHub ID: ahmedalagha1418, (ahmedn.alagha@hotmail.com)


