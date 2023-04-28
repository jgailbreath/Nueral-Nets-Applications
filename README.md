#MTSU-CSCI 4850//Neural Networks: Semester Project 2021
# **Expanding limited datasets using augmentation methods for improved training on neural nets.**
# Project Design: Jesse Gailbreath
# Group Members: Noah Norrod, Jacob Swindell, Grayson Cordell

  Small datasets can be plagued with the issue of producing models that present poor accuracy. Sometimes, there is just not enough information to get a network to learn without drastic overfitting. So, let's say you have a small dataset and you are having issues training a network with decent accuracy? Well, do we have a cure for you: data augmentation.
### What's in the repository?
  Here you will find some resources and a step-by-step demonstation on how incorporating data augmentation can improve your accuracy.
  1. A free dataset of audio samples recored as .wav files (original source:  https://github.com/Jakobovski/free-spoken-digit-dataset)
  2. Documentation on how you can perform augmentations on the audio samples.  If you just want to get to the good stuff, feel free to use our augmented dataset located in the Data section.
  3. The code to transform the .wav files into spectrogram images for use in a neural network.  Don't have the time?  We've got you!  A full set of images are housed in the Data section as well.
  4. The code to build a network designed to test out your handiwork (or ours if you just want to see the end result).
  5. You will also find some interesting links and documentation all related to this topic and our final paper sharing our results.
### Ready to take a look?
We utilized Jupyter Notebook as our development evironment.  If you are not familiar with it, head here:  https://jupyter.org/

We also used Google Colab to execute our notebook.  Not familiar with this? No worries, just head over here:  https://colab.research.google.com/notebooks/intro.ipynb

Our datasets are fairly large so we utilized Google Drive for storage and access:  https://www.google.com/drive/

To run our short demo, use this link to download the unseen_originals dataset to have locally:  https://drive.google.com/drive/folders/156QEK8JuWnFqsHnptc--pRW0lYam8fis?usp=sharing

To run our long demo you can download from the our Demo folder or from https://drive.google.com/drive/folders/10ldZfWHfqrv20AnGLO9QQdpr2S9493Tz?usp=sharing

You will also need this file to use our pre-trained model:  https://drive.google.com/file/d/1LyMNrvk72AVxLWGEQP-B4DAm9wkoc93b/view?usp=sharing

We utilized Tensorflow and Keras to make the magic happen.  It does require a few Python dependencies (yep, you have to have Python already installed). Using the pip command will make this fairly simple.  Enter the following steps in your command line to get going:

1.  $ pip install --upgrade tensorflow
2.  $ pip install numpy scipy
3.  $ pip install scikit-learn
4.  $ pip install pillow
5.  $ pip install h5py
6.  $ pip install keras

If you are having some issues, you can check out this resource for more details:  https://www.tensorflow.org/install/pip

Okay, you should be good-to-go! We have two demo options depending on how much time you have.  Open the demo folder above to let the fun begin.
  

_____________________________________________________________________________
Short Demo
https://colab.research.google.com/drive/1te5e-wfNxUqyPRLCPVMau8Nf3AMlprOB?usp=sharing
UnseenOriginals- https://drive.google.com/drive/folders/156QEK8JuWnFqsHnptc--pRW0lYam8fis?usp=sharing
PreTrained- https://drive.google.com/file/d/1LyMNrvk72AVxLWGEQP-B4DAm9wkoc93b/view?usp=sharing
_____________________________________________________________________________
Long Demo 
https://colab.research.google.com/drive/1te5e-wfNxUqyPRLCPVMau8Nf3AMlprOB?usp=sharing
Smaller dataset- https://drive.google.com/drive/folders/10ldZfWHfqrv20AnGLO9QQdpr2S9493Tz?usp=sharing
For Large Dataset Use Repo
_____________________________________________________________________________

If you are looking for a quick way to augment wav files checkout Grayson's walkthrough
https://colab.research.google.com/drive/1yl3aNLWl1qHWhtzitdaq91GRJhiqfMVD?usp=sharing

Or his Ugly Auto Audio Augmentor
https://colab.research.google.com/drive/1TnD-WGQ8w4O03ktO-SQ-RWZOJpc949yK?usp=sharing


