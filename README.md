# HS-Diffusion
>**HS-Diffusion: Semantic-Mixing Diffusion for Head Swapping**
>
>Qinghe Wang, Lijie Liu, Miao Hua, Pengfei Zhu, Wangmeng Zuo, Qinghua Hu, Huchuan Lu, Bing Cao
>
<img src="Figures/show.png" width="100%">
This paper aims to stitch a source head to another source body, while maintaining the main components of the two source images unchanged. We first propose a semantic-mixing diffusion model for head swapping, which blends the semantic layouts to guide the mixing of diffusion latents step-by-step, stitching one head to another body seamlessly. We also propose a semantic calibration strategy to adaptively inpaint incomplete region and address the occlusion and noise issues encountered for head swapping.


## Training process.
<img src="Figures/train_process.png" width="60%">

## Inference process.
<img src="Figures/infer_process.png" width="100%">


## Results

### Comparsion for head swapping:
<img src="Figures/comparsion.png" width="100%">

### Semantic-guided head replacement:
<img src="Figures/head_swap_with_fake.png" width="70%">

### Semantic-guided local & multi-component replacement:
<img src="Figures/multi_component.png" width="90%">

### Head swapping in the wild:
<img src="Figures/in_the_wild.png" width="90%">



## Databases

**We process the [Stylish-Humans-HQ(SHHQ) dataset](https://github.com/stylegan-human/StyleGAN-Human) to the half-body SHHQ dataset as introduced in our paper. It can be downloaded from [Baidu Drive](https://pan.baidu.com/s/1TdUjplfiXayUKVpa9q_Zlw?pwd=2zjc)** with password `2zjc`.



## TODOs

- [x] Release training data
- [ ] Release training code
- [ ] Release inference code


## Contact

If you have any questions or suggestions about the paper, feel free to reach me (qinghewang@mail.dlut.edu.cn).

