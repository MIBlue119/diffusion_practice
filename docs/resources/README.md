### Resources

- Intro of diffusion model
    - assembly’s intro: [https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/)
    - lili’log: [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)
    - generative modeling: [https://yang-song.github.io/blog/2021/score/](https://yang-song.github.io/blog/2021/score/)
    - Yannic Kilcher’s intro about DDPM(Denoising Diffusion Probalistic Models ): [https://www.youtube.com/watch?v=W-O7AZNzbzQ](https://www.youtube.com/watch?v=W-O7AZNzbzQ)
        - OpenAI’s **[Diffusion Models Beat GANs on Image Synthesis](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbXlYNW1xSWFVdGFKeV9CUTBpQW15WEdBZWVTd3xBQ3Jtc0trcDdTVXhIYzBMZU5EODgxTmJCeloxQnBlZGR4UlBJanBYeVpHNG9PelpqS0dBNGhSYW83MUpmRzVhS0VWODA5X3VkVHY4YmJOb2lQZnRMLTNBX1VVUEtlaTFjX0hvUXVWODUwRjFnb2t2bmJCSzRMUQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F2105.05233&v=W-O7AZNzbzQ)**
        - https://github.com/openai/guided-diffusion
        
        - philosophy
            
            - forward noising process
                - 有張圖片/或是資料作為輸入，加入Gaussian noise 很多個steps
                    - 最後我們會得到什麼？ 一張有滿滿normal distribution noise的圖
            - Could we learn a function(May be NN model) to reverse the process?
        
    - video: [What are Diffusion Models?](https://www.youtube.com/watch?v=fbLgFrlTnGU&list=LL&index=3)
        - 在Diffusion只需要訓練reverse

        
        **Papers:**
        
        - Feller, 1949: On the Theory of Stochastic Processes, with Particular Reference to Applications ([https://digitalassets.lib.berkeley.ed...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbE5zS2xIV0I3Rk9iNlhzYUEtbGpTdzhqaDRCd3xBQ3Jtc0trclowcW1SVFFwck0xSEdyclRWYzBMT1NIN2dfMTYzRE9ISDNyb0Y3SFdjOUxrZXFJaVREbjgwQnFJTngxMlM1OU9SVEhCRG1JM1huZ3prRWNmS3NfcEx5eVlHYy1FWHI5Y3Y0SlF4U0FTYVZQMmtfRQ&q=https%3A%2F%2Fdigitalassets.lib.berkeley.edu%2Fmath%2Fucb%2Ftext%2Fmath_s1_article-21.pdf&v=fbLgFrlTnGU))
        - Sohl-Dickstein et al., 2015: Deep Unsupervised Learning using Nonequilibrium Thermodynamics ([https://arxiv.org/abs/1503.03585](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmItWnl0YnU5OERXTE80VEIwUFpTbDRlM3Ixd3xBQ3Jtc0tsNDhveGRsVHFuQzNabHJwbUJTdHAwWUxYbUFsSDVfZEVPWU51UFNrWE9SRWNJNndDQkJmLVNmVWM2YktFLV82T1NFNnhEQ3BBTkIya0V2VjJ4UWhRdWxZUUxMZUNOdllpQnRCSXR4Njc4X3BYWFQxWQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F1503.03585&v=fbLgFrlTnGU))
        - Ho et al., 2020: Denoising Diffusion Probabilistic Models ([https://arxiv.org/abs/2006.11239](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbV9BUTc0cUdqUmJ3b0E3VFBKelVNMjM1QlAwZ3xBQ3Jtc0tsdnZZWmxuWjBWd1ViVnM3OXJPX1hMYlU5YmVaRWotQUxpWlU3VmNDa1gzelNOa0tqWHJ2bjFQYlQxVElDSmItVjF1U3pQcWtwYnpiYnd6QkdrT3oyODg1WTJGbklZXzNaMWVNTGFxNGUtZDdURXRUcw&q=https%3A%2F%2Farxiv.org%2Fabs%2F2006.11239&v=fbLgFrlTnGU))
        - Song & Ermon, 2019: Generative Modeling by Estimating Gradients of the Data Distribution ([https://arxiv.org/abs/1907.05600](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmRHRTlVNnlIOHAtQ000WmJQOGtLZjFpNjZXUXxBQ3Jtc0tuYXBTZ1daUWR1S0JPZUltNDlzb3RXV2ttWnFQUm5pNkFQYkZibm9qcDViQ1dnNTlGbm1kT2pxa2wtMTRnUmFpT1hXMkFWckV1SnZVMENVczl6dU5DZDZIX2E0bjc5ejdtOHJWLW9CcVRlOXZERklRNA&q=https%3A%2F%2Farxiv.org%2Fabs%2F1907.05600&v=fbLgFrlTnGU))
        - Dhariwal & Nichol, 2021: Diffusion Models Beat GANs on Image Synthesis ([https://arxiv.org/abs/2105.05233](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbHJsTTdpdUhRUG1YNkF5aWpFYVVDcVA4bDZhQXxBQ3Jtc0tuSHNFdDhNS0RsSjZNT1lVSFZFbjdBVE5feTFZSmtqY2NiWkhCWEFKZlFTb05iTWZvcTFELXN5eElYV1gzbXdPMDg2c0NCSFFZQzd4WWM1YjZLczBpLXEzazVuYzFpakZXdWYxbld4dlhRd2VIcTJMSQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F2105.05233&v=fbLgFrlTnGU))
        - Nichol et al., 2021: GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models ([https://arxiv.org/abs/2112.10741](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbkFDd3pBbWV1UFNEMDRxbzdXQ3dFSXNhUllHQXxBQ3Jtc0ttM3NTUEU3R0xIa3RfS1A3YkNfZUNtMDk0UlNTaWk2Mm4xQTdDZTYwSWRGZzkwMjYtY2VYOS1hUXpnS0h6SlNsZDZDXzkzMUpxd3puWE9vdUZWcjlaSG5kRkwyUHJDUGkzZGhMdnhwMnZYY0Q0Q1Y5TQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F2112.10741&v=fbLgFrlTnGU))
        - Saharia et al., 2021: Palette: Image-to-Image Diffusion Models ([https://arxiv.org/abs/2111.05826](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmhORDNvVzdIaXN0N25qMl80SW1VR3l3TWVuZ3xBQ3Jtc0trVE5YMnhFZ21NbnYxUm9JTW9lRFVVN29nMFd5MllmOUZ3MWI1Q3EtaWMyaGw3bFlDcXJJdFhvZEU4bGI5NF9fWE9YWWY2Vy0zS0tQcFdMa1pDQlBpSkliTmZNOW0wSm0zejhyTFN6V1FoYzFQYi1yYw&q=https%3A%2F%2Farxiv.org%2Fabs%2F2111.05826&v=fbLgFrlTnGU))
        - Ramesh et al, 2022: Hierarchical Text-Conditional Image Generation with CLIP Latents ([https://arxiv.org/abs/2204.06125](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa25yQlJMT2ZzdV9YWFVQcEtXUlNXTTB4ZHVLZ3xBQ3Jtc0ttWTdVSUhMOWNjckxZVERSZGFoNVVHaXF5bkZ1aW1sOVVDMWRQUDEwd3hGMkZTR2VXRm9YcUFoRGdwRzlBbHNLTFlzZG5rbm5BRWw3Z3dNak9ZWnp4c2I3YTVLYXFyZWFxd3RZNEVfQThPNm9VUWhsdw&q=https%3A%2F%2Farxiv.org%2Fabs%2F2204.06125&v=fbLgFrlTnGU))
        - Song et al., 2021: Denoising Diffusion Implicit Models ([https://arxiv.org/abs/2010.02502](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbDdGbWJwMzdZVGVydTlDT19UWWdseUhnZ3lEQXxBQ3Jtc0tsdXlnZmZuX3JTRTdmZTN1Q1N1WnUzdHF1SUNiUVloWjJ5RTNLYnRJNlJQSDBSVHdJQ2ZWTHExY0pZdENWZ21uRmF5elpmRE9rMXJxMHl4TE03ZU52QmMwN2I4ZzVBU2NiQTQyUjZpcmdIS21DMlBKSQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F2010.02502&v=fbLgFrlTnGU))
        - Nichol & Dhariwal, 2021: Improved Denoising Diffusion Probabilistic Models ([https://arxiv.org/abs/2102.09672](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbi1QQVJra2daU2x3QUxubVNxLXpsY0FIa1BPUXxBQ3Jtc0tsM1dfTUNjSTk0QXNwUXRJVG9uVGw4alJ4UlZRUXFXczNDYVFGR0dyRkhnOW5QMmd5ZlQ4Z1RrRVk1eWtJRVdPUUltemJsTmV1T0lvTV9UVmt2Z2hPNmtuR1N5clByR2poLU1Ec3NROVQ4TmRiMzZOUQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F2102.09672&v=fbLgFrlTnGU))
        - Kingma et al., 2021: Variational Diffusion Models ([https://arxiv.org/abs/2107.00630](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqblpXZW9fUC1Vc3BYbUIxOFZERVZ1S0lnTWlxd3xBQ3Jtc0tsV2VsOUhmeWtzNllMaUFBRnZ4bW5nb29aV25DUWQ3RmQ3VW9WX0xCX1REOVFaeENuMmJfX01Bd0VvbzE0Q2M0NXUtWHhqalpWcXlSUkFraEl5NjFNT21MRzJPbXJ3QXVGYThZQXVZR3d6SXJvS1FNWQ&q=https%3A%2F%2Farxiv.org%2Fabs%2F2107.00630&v=fbLgFrlTnGU))
        - Song et al., 2021: Score-Based Generative Modeling through Stochastic Differential Equations ([https://arxiv.org/abs/2011.13456](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbV9IcXRYVUNhOHl1NElxbUZpTVNZWHhQa21Nd3xBQ3Jtc0ttSGU3Y0M1WGx6WUtSWDBTTlRtaE5qRDVWLXc5R21MTHp1M2NvdDE0cTQwOTBLM01qQmZCQ0pjYUx0UEpIWXZCTHlXbDNyNmxVR09WMy04eTFKeEhCRlotV3Z0S3VMOXNJYk9sX0FrMmZ3Z0xmRnl6NA&q=https%3A%2F%2Farxiv.org%2Fabs%2F2011.13456&v=fbLgFrlTnGU))
    - [2022]video: [Diffusion models explained. How does OpenAI’s GLIDE work?](https://www.youtube.com/watch?v=344w5h24-h8)
        - 4 types Generative models
            
            ![source from: [https://lilianweng.github.io/posts/2021-07-11-diffusion-models/](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) ](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f217aa08-cedc-45ef-9972-79fc14e94f08/Untitled.png)
            
            source from: [https://lilianweng.github.io/posts/2021-07-11-diffusion-models/](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) 
            
            - GAN
            - Forward Diffusion Process
                
            - Reverse

            
    - [2021] video: [號稱打敗GAN的生成模型: Diffusion Models](https://www.youtube.com/watch?v=6HdOpr_lNhw)
        
        
    - 2022 CVPR Tutorial: [Denoising Diffusion-based Generative Modeling: Foundations and Applications](https://cvpr2022-tutorial-diffusion-models.github.io/)
- github
    - implementaion of Denoising Diffusion Probabilistic in Pytorch
        - https://github.com/lucidrains/denoising-diffusion-pytorch
    - awesome-diffusion-models: https://github.com/heejkoo/Awesome-Diffusion-Models

### Keywords

- KL Divergence
- Marcov chain
    - current step depend on previous step
- Gauissian Distribution

### Application

- Image generation
    - OpenAI Dalle-2
    - text-conditional image synthesis
        - OpenAI’s glide-textc2im: https://github.com/openai/glide-text2im
        - [https://arxiv.org/abs/2112.10741](https://arxiv.org/abs/2112.10741)
    - Google;s Imagen *`Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding`*
        - [https://arxiv.org/abs/2205.11487](https://arxiv.org/abs/2205.11487)
        - [https://imagen.research.google/](https://imagen.research.google/)
- Inpainting
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b53a356f-c4a9-4eeb-bf2d-800425668c09/Untitled.png)
    
- Music generation
    - 2021 Google Magenta Symbolic Music Generation With Diffusion Models
        - [https://arxiv.org/pdf/2103.16091.pdf](https://arxiv.org/pdf/2103.16091.pdf)
        - https://github.com/magenta/symbolic-music-diffusion
- Audio Synthesis
    - 2021 Nvidia’s Diffwave
        - [https://arxiv.org/pdf/2009.09761.pdf](https://arxiv.org/pdf/2009.09761.pdf)
        - demo: [https://diffwave-demo.github.io/](https://diffwave-demo.github.io/)
        - https://github.com/lmnt-com/diffwave
- Audio Denoise
    - 2022 DolbyIO’s research `Universal Speech Enhancement With Score-based Diffusion`
        - [https://serrjoa.github.io/projects/universe/](https://serrjoa.github.io/projects/universe/)
        - arxiv: [https://arxiv.org/pdf/2206.03065.pdf](https://arxiv.org/pdf/2206.03065.pdf)
    - 2022 ICASSP Conditional Diffusion Probalistic Model for speech enahncement
        - [https://arxiv.org/pdf/2202.05256.pdf](https://arxiv.org/pdf/2202.05256.pdf)
        - https://github.com/neillu23/CDiffuSE

### Questions

- Difference between GANs and Diffusion Models
- Generative model家族之間的差異