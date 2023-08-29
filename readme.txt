A collection of DCGANs I made with PyTorch.

Some of the datasets used:

https://www.kaggle.com/datasets/sharansmenon/animals141
https://www.kaggle.com/datasets/bryanb/abstract-art-gallery
https://www.kaggle.com/datasets/brendanartley/cartoon-faces-googles-cartoon-set
https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time


Atra - Generating 32 * 32 RGB images from best-artworks-of-all-time dataset
Dimiwck - Generating 32 * 32 RGB images of cartoon faces from the cartoon-faces-goolges-cartoon-set dataset
DimwickZoo- Generating 32 * 32 RGB images of animals141 dataset
Arcwride- Generating 32 * 32 RGE images from abstartc-art-gallery dataset


As can be seen, these DCGANs are still very unstable.

Some tests I've run to correct this, 

Varying the strengths of the discriminator and generator.
Adding dropout
Changing from rgb output to grayscale (seemed to help when I had low amounts of training images)
