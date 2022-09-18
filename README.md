# Diffusion Practice 

A repo to record the practice to use diffusion models for some applications

## Intro 

- What is a diffusion model?
    - A new technique is used at image/audio/video generation and achieve than GAN
    - It consists 2 processes [ref](https://huggingface.co/blog/annotated-diffusion)
        - forward: gradually adds Gaussian noise to an image, untial end up with pure noise(Gaussian Noise)
        - backward: a learned reverse denoising diffusion process, where a neural network is trained to gradually denoise from pure noise