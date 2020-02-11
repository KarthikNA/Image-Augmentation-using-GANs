A Survey on Data Augmentation for Multi-Class Image Classification

Submitted By -
Aastha Agrawal (GT ID: 903323805)
Karthik Nama Anil (GT ID: 903471605)

Codebase Structure

main_directory or project_root_directory
    \_ README
    \_ Complex Image Augmentation Techniques
       \_ data
       \_implementations
           \_ aae
               \_ aae.py
           \_ acgan
               \_ acgan.py
           \_ bgan
               \_ bgan.py
           \_ cgan
               \_ cgan.py
           \_ cogan
               \_ cogan.py
           \_ dcgan
               \_ dcgan.py
           \_ drgan
               \_ drgan.py
           \_ ebgan
               \_ ebgan.py
           \_ gan
               \_ gan.py
           \_ infogan
               \_ infogan.py
           \_ lsgan
               \_ lsgan.py
           \_ sgan
               \_ sgan.py
           \_ softmaxgan
               \_ softmaxgan.py
           \_ wgan
               \_ wgan.py
           \_ wgan_gp
               \_ wgan_gp.py
   \_ Simple Image Augmentation Techniques
     \_Centre Crop
     \_Color Jitter
     \_Grayscale
     \_Baseline
     \_Padding
     \_Random Crop
     \_Random Erasing
     \_Random Horizontal Flip
     \_Random Perspective
     \_Random Rotation
     \_Random Vertical Flip
     \_RandomAffine
     
Complex Image Augmentation Techniques

To execute the code, please ensure you have Python 3.7 or higher.
1. Please enter the implementations directory
   cd complex_image_augmentation_techniques/implementations
2. Lets say you wish to execute acgan
   cd acgan
   python3 acgan.py
  Similarly it can be done for other GANs as well.

NOTE - 
      1. Keep in mind GANs take a long time to execute.
      2. At any point if a particular Python package is missing, please install the same.
      3. Ensure that the particular user has the highest access level for that particular folder
           sudo chmod 777 *
      4. The code automatically downloads the MNIST dataset from the web for each GAN.

Simple Augmentation Techniques

All the simple augmentation techniques are individual Google Colab notebook and can be executed online by running each cell. !nvidia-smi command would help to identify the GPU details and it has been added to all the colab files. Each file would take approximately 20-40 minutes to execute.
CIFAR-10 Dataset is directly used from from torchvision.datasets library.
NOTE - We have used existing implementations of various augmentation techniques that is available only to do performance testing. The code is curated from multiple sources and modified to support performance testing.

Google Colab version of Code is available on https://drive.google.com/drive/folders/1IeX21no4TDUMYwQjqcFWK7eNWSRcBH7J?usp=sharing
