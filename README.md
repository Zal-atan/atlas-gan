# atlas-gan
In this project we explore GANs and DCGANs in machine learning. 

The first part of the project DCGAN is exploring building a basic dcgan model using the mnist data set. I then create three different experiments where I test changing the structure of the models, tuning the hyperparameters, and changing the precision of the models to see the difference.

The second part of the project is the advanced-gan repository. In this repo I built a basic GAN which uses the CelebA dataset (20000 pictures of celebrities) to try to build a GAN which can make pictures of humans. After the first base case, I only had time for one additional experiment as the training time became immense with this model. I decided to both add layers to the generator model, as well as adding learning rate reduction at the same time.

## Paths
* atlas-gan/

    * advanced_gan/
        * advanced_gan_base/ - contains log file and jupyter notebook
            * models/ - contains model from every 2nd epoch
            * pngs/ - contains a 10 image x 10 image selection of generated numbers from every 2nd

        * advanced_gan_experiment_1/ - contains log file and jupyter notebook
            * models/ - contains model from every 2nd epoch
            * pngs/ - contains a 10 image x 10 image selection of generated numbers from every 2nd

    * dcgan/
        * dcgan_base/ - contains log file and jupyter notebook
            * models/ - contains model from every 10th epoch
            * pngs/ - contains a 10 image x 10 image selection of generated numbers from every 10th epoch

        * dcgan_experiment_1/ - contains log file and jupyter notebook
            * models/ - contains model from every 10th epoch
            * pngs/ - contains a 10 image x 10 image selection of generated numbers from every 10th epoch

        * dcgan_experiment_2/ - contains log file and jupyter notebook
            * models/ - contains model from every 10th epoch
            * pngs/ - contains a 10 image x 10 image selection of generated numbers from every 10th epoch

        * dcgan_experiment_3/ - contains log file and jupyter notebook
            * models/ - contains model from every 10th epoch
            * pngs/ - contains a 10 image x 10 image selection of generated numbers from every 10th epoch

