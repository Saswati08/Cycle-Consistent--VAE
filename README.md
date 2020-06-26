# Cycle-Consistent--VAE

This is an implementation of paper, "Disentangling Factors of Variation with Cycle-Consistent Variational Auto-Encoders" on 2D Sprites dataset.
Link for dataset is : http://www-personal.umich.edu/~reedscot/files/nips2015-analogy-data.tar.gz
The .ipynb jupyter notebook file can be run for creating dataloader for sprites, training architecture and producing results.

Libraries to be installed :
pytorch
matplotlib
imagegrid
glob 
scipy

##About :
In this paper a novel architecture is introduced that disentangles the latent spcae into two complementary subspaces by using semi supervised approach in the
form of pair wise similarity of labels. It is also shown that using z- feature we get much lesser accuracy as compared to s-feature,thus proving successful 
disentaglement of latent space.


