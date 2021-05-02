s21-team7-project
### Members: Grayson Cordell, Jesse Gailbreath, Noah Norrod, Jacob Swindell
# ***Using augmentation methods on audio files to increase the size of limited datasets.***

  Small datasets can be plagued with the issue of producing models that present poor accuracy. Sometimes, there is just not enough information to get a network to learn without drastic overfitting. So, you have a small dataset and you are having issues training a network with decent accuracy? Well, do we have a cure for you: data augmentation.
### What's in the repository?
  Here you will find a some resources and a step-by-step demonstation on how incorporating data augmentation can improve your accuracy.
  1. A free dataset of audio samples recored as .wav files (original source:  https://github.com/Jakobovski/free-spoken-digit-dataset)
  2. Documentation on how you can perform augmenetations on the audio samples.  If you just want to get to the good stuff, feel free to use our augmented dataset located in the Data section.
  3. The code to transform the .wav files into spectrogram images for use in a neural network.  Don't have the time?  We've got you!  A full set of images are housed in the Data section as well.
  4. The code to build a network designed to test out your handiwork (or ours if you just want to see the end result).
  5. You will also find some interesting links and documentation all related to this topic and our final paper sharing our results.
### Ready to take a look?
We used Jupyter Notebook to write our code.  If you are not familiar with it, head here:  https://jupyter.org/

We also used Google Colab to execute our notebook.  Not familiar with this? No worries, just head over here:  https://colab.research.google.com/notebooks/intro.ipynb

Our datasets are fairly large so we utilized Google Drive for storage and access:  https://www.google.com/drive/

We utilized Tensorflow and Keras to make the magic happen.  It does require a few Python dependencies (yep, you have to have Python already installed). Using the pip install command will make this fairly simple.  Enter the following steps in your command line to get going:

$ pip install --upgrade tensorflow
$ pip install numpy scipy
$ pip install scikit-learn
$ pip install pillow
$ pip install h5py
$ pip install keras

If you are having some issues here you can check out this resource for more details:  https://www.tensorflow.org/install/pip

Okay, you should be good-to-go! Open the demo above to let the fun begin.
  

