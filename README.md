# Anime Avatar Generation with DCGAN
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

A DCGAN implementation in Tensorflow, for generating Anime Avatars. Trained on ~21k anime faces for 300 epochs, the generator is capable of generating convincing imaginary anime avatars. The dataset is available here - [Anime Faces - Kaggle](https://www.kaggle.com/datasets/soumikrakshit/anime-faces)

<hr/>
  
    DATASET_SIZE = 21551
  	IMAGE_SIZE = 64x64
  	LATENT_DIM = 128
  	DIS_LR = 1e-4
    GEN_LR = 3e-4
    ALPHA = 0.2
  	EPOCHS = 300
  	BETA1 = 0.5
  	WEIGHT_INIT = RandomNormal(mean=0, stddev=0.02)

<hr/>

Sample generated Anime Avatars after 300 epochs of Training - </br> </br>

<img src='https://github.com/moshiurtonmoy/Anime-Avatar-Generation-with-DCGAN/blob/master/output.png' alt='sample output'/>

