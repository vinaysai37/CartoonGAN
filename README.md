# Cartoonization
Pytorch testing code of [CartoonGAN](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/2205.pdf) `[Chen et al., CVPR18]`.

<p>
    <img src='test_output/demo_ori.gif' width=300 />
    <img src='test_output/demo.gif' width=300 />
</p>


## Getting started

- Linux
- NVIDIA GPU
- Pytorch 0.3
- Torch

```
!git clone https://github.com/vinaysai37/CartoonGAN.git
cd CartoonGAN
```

## Pytorch

- For testing:

```
!python test.py --input_dir YourImgDir --style Hosoda --gpu 0
```


## Examples (Left: input, Right: output)

<p>
    <img src='test_img/in2.png' width=300 />
    <img src='test_output/in2_Hayao.png' width=300 />
</p>

<p>
    <img src='test_img/in3.png' width=300 />
    <img src='test_output/in3_Hayao.png' width=300 />
</p>

<p>
    <img src='test_img/5--26.jpg' width=300 />
    <img src='test_output/5--26_Hosoda.jpg' width=300 />
</p>

<p>
    <img src='test_img/7--136.jpg' width=300 />
    <img src='test_output/7--136_Hayao.jpg' width=300 />
</p>

<p>
    <img src='test_img/15--324.jpg' width=300 />
    <img src='test_output/15--324_Hosoda.jpg' width=300 />
</p>


## Note

- The training code should be similar to the popular GAN-based image-translation frameworks and thus is not included here.

## Acknowledgement

- Part of the codes are borrowed from [DCGAN](https://github.com/soumith/dcgan.torch), [TextureNet](https://github.com/DmitryUlyanov/texture_nets), [AdaIN](https://github.com/xunhuang1995/AdaIN-style) and [CycleGAN](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).

