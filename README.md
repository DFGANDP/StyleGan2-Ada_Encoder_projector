![This is an image](Banner.png)

![GitHub](https://img.shields.io/github/license/DFGANDP/StyleGan2-Ada_Encoder_projector)

# Image2StyleGAN implementation

## Pipeline
```bash
1. Aligned Image
2. Preprocess
3. Find latent vector with encoder
4. Find exact latent by optimize it using gradient descent
```

1. ### Image
![Menu](bradley_cooper.jpg)

2. ### Aligned
![Menu](face_aligned.png)

3. ### Encoder latent
![Menu](encoder_img.png)

4. ### Gradient_descent
![Menu](Projector.png)


With latent vectors you can make a lot of transformation, look at my other repo!

https://github.com/DFGANDP/CelebA-VAE-feature-extractor

# References:
https://arxiv.org/abs/1904.03189

http://www.seeprettyface.com/research_notes.html

https://github.com/zaidbhat1234/Image2StyleGAN
