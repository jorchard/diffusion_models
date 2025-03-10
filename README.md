# Diffusion Model Demo

This code is based on code from

https://github.com/Seachaos/Tree.Rocks/blob/main/QuickDiffusionModel/QuickDiffusionModel_torch.ipynb

which is described on the blog

https://tree.rocks/make-diffusion-model-from-scratch-easy-way-to-implement-quick-diffusion-model-e60d18fd0f2e

## Main Demod

The main demonstration is in the file `QuickDiffusionModel_torch.ipynb`.

It can load the pretrained model `diff_model_50epochs.pt`.

There is also the demo `no_resid.ipynb`, which is similar code but excludes the skip connections. It also can read in a pre-trained model.
