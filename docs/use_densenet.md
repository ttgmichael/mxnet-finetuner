# Use DenseNet

ImageNet pretrained DenseNet-169 model is introduced on [A MXNet implementation of DenseNet with BC structure].

You can use this model as below

## Download parameter and symbol files

densenet-imagenet-169-0-0125.params  
https://drive.google.com/open?id=0B_M7XF_l0CzXX3V3WXJoUnNKZFE

densenet-imagenet-169-0-symbol.json  
https://raw.githubusercontent.com/bruinxiong/densenet.mxnet/master/densenet-imagenet-169-0-symbol.json

## Rearrange downloaded files

Change the name of the downloaded files and store it as below

```
model/imagenet1k-densenet-169-0000.params
model/imagenet1k-densenet-169-symbol.json
```

## Modify config

To use DenseNet-169 pretrained models, specify the `imagenet1k-densenet-169` in `config.yml`.


[A MXNet implementation of DenseNet with BC structure]: https://github.com/bruinxiong/densenet.mxnet
