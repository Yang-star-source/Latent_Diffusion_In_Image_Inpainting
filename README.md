# Latent Diffusion In Image Inpainting
Use pretrained latent diffusion model to perform image inpainting tasks.

![Image Inpainting Demo](gif/mygif.gif)

## Inference Mode :

![Inpainting Flowchart](gif/inpainting.png)

## Draft and Notes
If need to view the draft and mathematic formula used

[Click to view the draft](https://1drv.ms/o/c/eae736d6f2d45eed/IgDn5PJJk8yWRLJfj4rN5ZRLAcTmnnWo1ag8RaTFzGBL7g8?e=5EEBHb)

## Pre-trained Models
You can download the trained weights from Google Drive:

* **[Download Pre-trained Weights Folder](https://drive.google.com/drive/folders/1EbwM13No2i44OCQbxzMkeORkeEqaT9IU?usp=sharing)**
  * `checkpoint.pth` (VAE Autoencoder)
  * `unet_epoch_500.pth` (Diffusion Model)

**Setup:**
1. Download both files.
2. Place them inside your project folder (or upload to Colab).


## Codes Implementation
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yang-star-source/Latent_Diffusion_In_Image_Inpainting/blob/main/Image_Inpainting.ipynb)

## How To Build Latent Diffusion ?
I built a repo that describe how to build Unconditional Image Generation Model , Latent Diffusion from scratch , the Latent Diffusion used for this repo is using exact same weights.

[Check how i build Latent Diffusion from Scratch](https://github.com/Yang-star-source/Latent_Diffusion_From_Scratch)

## Study Resources 
