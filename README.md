# Finetune Deit on CIFAR-10

The code was adapted from [DeiT](https://github.com/facebookresearch/deit), but make sure you have the [pytorch-image-models](https://github.com/rwightman/pytorch-image-models) package `timm==0.4.12`.

```
pip install timm==0.4.12
```

## Example


```
python main.py --finetune https://dl.fbaipublicfiles.com/deit/deit_base_patch16_224-b5f2ef4d.pth --data-set CIFAR-10 --model deit_base_patch16_224 --batch-size 128 --epochs 20 --output_dir output
```

