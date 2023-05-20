# MacBook Pro M1 DeepLearning config

##### Install PyTorch and Tensorflow for GPU support with a Mac M1 using CONDA.

Reference : Jeff Heaton (https://www.youtube.com/@HeatonResearch)

To remove jupyter notebook kernel : 

```
$ jupyter kernelspec remove <kernel-name>
```

At the beginning my mps wait not available, so I did : 

```
$ pip3 uninstall torch torchvision torchaudio 
```

and then : 

```
$ pip3 install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```
