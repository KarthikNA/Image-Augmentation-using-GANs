NOTE - WE ARE USING EXISTING CODE THAT IS AVAILABLE ONLINE TO DO PERFORMANCE TESTING ON DIFFERENT COMPLEX AND SIMPLE IMAGE AUGMENTATION TECHNIQUES. THE CODE IS CURATED FROM MULTIPLE SOURCES AND MODIFIED TO SUPPORT THE PERFORMANCE TESTING.

Codebase Structure

main_directory or project_root_directory
     \_ README.txt
     \_ complex_image_augmentation_techniques
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

Complex Image Augmentation Techniques
To execute the code, please ensure you have Python 3.7 or higher.
1. Please enter the implementations directory
    cd complex_image_augmentation_techniques/implementations
2. Lets say you wish to execute acgan
    cd acgan
    python3 acgan.py
   Similarly it can be done for other GANs as well.


NOTE - 1. Keep in mind GANs take a long time to execute.
       2. At any point if a particular Python package is missing, please install the same.
       3. Ensure that the particular user has the highest access level for that particular folder
            sudo chmod 777 *
       4. The code automatically downloads the MNIST dataset from the web for each GAN.

Project Done By -
Aastha Agrawal(GT ID:903323805)
Karthik Nama Anil(GT ID:903471605)