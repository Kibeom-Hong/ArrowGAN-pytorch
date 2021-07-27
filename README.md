# ArrowGAN-pytorch
### Official Implementation of ArrowGAN : Learning to Generate Videos by Learning Arrow of Time (Neurocomputing)

![ArrowGAN](https://user-images.githubusercontent.com/77425614/127087830-a799438e-392e-4ce0-b1a3-6c0ea9b6e02b.PNG)


> ## ArrowGAN : Learning to Generate Videos by Learning Arrow of Time
> 
> Kibeom Hong (Yonsei Univ.), Youngjung Uh (Yonsei Univ.), Hyeran Byun (Yonsei Univ.)
>
> Paper : [https://arxiv.org/abs/2101.03710](https://arxiv.org/abs/2101.03710)
> 
> **Abstract**: Training GANs on videos is even more sophisticated than on images because videos have a distinguished dimension: time. While recent methods designed a dedicated architecture considering time, generated videos are still far from indistinguishable from real videos. In this paper, we introduce ArrowGAN framework, where the discriminators learns to classify arrow of time as an auxiliary task and the generators tries to synthesize forward-running videos. We argue that the auxiliary task should be carefully chosen regarding the target domain. In addition, we explore categorical ArrowGAN with recent techniques in conditional image generation upon ArrowGAN framework, achieving the stateof-the-art performance on categorical video generation. Our extensive experiments validate the effectiveness of arrow of time as a self-supervisory task, and demonstrate that all our components of categorical ArrowGAN lead to the improvement regarding video inception score and Fréchet video distance on three datasets: Weizmann, UCFsports, and UCF-101.


## Prerequisites

### Dependency
- Python 3.6
- CUDA 10.2
- Pytorch 1.4
- Check the requirements.txt

```
pip install -r requirements.txt
```

## Usuage
#### Training
#### Evaluation


## Ciation
If you find this work useful for your research, please cite:
```
@article{Hong2021ArrowGANL,
  title={ArrowGAN : Learning to Generate Videos by Learning Arrow of Time},
  author={Kibeom Hong and Youngjung Uh and H. Byun},
  journal={Neurocomputing},
  year={2021},
  volume={438},
  pages={223-234}
}
```

## Contact
If you have any question or comment, please contacth the first author of this paper - Kibeom Hong

[cha2068@yonsei.ac.kr](cha2068@yonsei.ac.kr)
