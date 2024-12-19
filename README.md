# Vision Tranformer to facil expression recognition
#### Made by: Victor Afonso Teixeira Santos and Gabriel Moreira Marques
You will find is the repository the implementation of a Vision Transformer based on the [AN IMAGE IS WORTH 16X16 WORDS:TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE](https://arxiv.org/pdf/2103.16854) and [Facial Expression Recognition with Visual Transformers and Attentional Selective Fusion](https://arxiv.org/pdf/2103.16854) papers. 
The ViT uses the idead of the transformer architecture to process image patches as sequences, enabling efficient and effective feature extraction for facial expression classification. This repository has the aim to reproduce the idea of this articles to label facial expression images with the correspondent expression potraid in the picture.
## How to run the code
### Get the jupyter notebook and use it on kaggle (or other prefered enviroment)
In this repository you can find a jupyter notebook with the source code of the project, get it and import notebook at [Kaggle](https://www.kaggle.com/). Now you need to get the dataset to your kaggle notebook: download and upload it from this public [link]http://cs231n.stanford.edu/tiny-imagenet-200.zip from the CS231n from the Stanford University. There is an option to get it directly from the Kaggle datasets, but it seems to be messy, so we suggest you to do it how was said before. After that just pick a GPU in the hardware accelerator option and run it! Just remember to change your directory properly on the code in the data loader.

