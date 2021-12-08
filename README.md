# Controllable Image Generation through Latent Space Navigation

Controllable semantic image editing enables a user to change entire image attributes with a few clicks, e.g., gradually making a summer scene look like it was taken in winter. Classic approaches for this task use a Generative Adversarial Net (GAN) to learn a latent space and suitable latent-space transformations. 

However, current approaches often suffer from attribute edits that are entangled, global image identity changes, and diminished photo-realism. To address these concerns, Zhuag et al. [1] proposed a method that  enhanced the control of the edits on images by monitoring and analysing the latent space involved with GANs. 

In this project, you will implement this method and generate qualitative results on datasets like CelebA, MITPlaces2, and take a step further in understanding controllable GANs. Finally, you will document your learnings and results in a report. 

Note that a firm knowledge of GANs is expected for taking up this project. "Learning how a GAN works" is NOT a part of the project.

![](https://github.com/nirajmahajan/Controllable-Gans-Through-Latent-Space-Navigation/blob/main/images/im.png)


## Structure and Timeline

1. **Reading**. 
You will read and present the paper. Note that the paper is a bit on the harder side to understand thoroughly. 

2. **Programming**.
  The paper implementation comprises of two implementation phases-

  - GAN for face data generation
  - Latent Space Direction Learning

  The majority of the time for implementation should be devoted to training and experimenting on the second phase. 

  You will code in Python using  PyTorch (preferable). 


3. **Writing**.
You will submit a short report (< 5 pages, typeset in LaTeX) explaining what you did in the project. 
It is recommended to *not* leave this till the end, as writing helps crystallize concepts. A document can be maintained to track weekly/daily progress.

The project duration is 15 Dec - 15 Jan. 
It is not much time, so we'll structure the timeline in five-day periods (qweeks: quick week, also quintic means degree 5).

| Qweek(s) | Dates           | Plan                                  |
| -------- | --------------- | ------------------------------------- |
| 0-0.5    | 15 Dec - 18 Dec | Reading and Understanding the paper   |
| 0.5-1.5  | 18 Dec - 25 Dec | Implementing and Training the phase 1 |
| 1.5 - 3  | 25 Dec - 4 Jan  | Implementing the phase 2              |
| 4        | 4 Jan - 10 Jan  | Conducting various experiments        |
| 5        | 10 Jan - 15 Jan | Writing                               |
 

## References

[1] Enjoy your editing : Controllable GANs for image editing via Latent Space Navigation, 2021, https://arxiv.org/abs/2102.01187

Special thanks to [Akkapaka Saikiran](https://github.com/akkapakasaikiran) via [Niraj Mahajan](https://github.com/nirajmahajan), for the document skeleton.
