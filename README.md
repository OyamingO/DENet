# Domain-incremental Learning for Fire Detection in Space-air-ground Integrated Observation Network	
DENet, a dynamic equilibrium approach for cross-domain fire detection, effectively balancing learning across heterogeneous sensor data and outperforming classical incremental methods.

[Ming Wang*](https://github.com/OyamingO), Dayu Yu*, Wanting He, Peng Yue*, Zheheng Liang

[[`Paper`](https://doi.org/10.1016/j.jag.2023.103279)] [[`Project`](https://github.com/OyamingO/DENet)] [[`Dataset`](https://doi.org/10.57760/sciencedb.j00104.00103)]  [[`BibTeX`](#Citing-SliceSamp)]


### 🔥: SliceSamp design
<img src="assets/SliceSamp.jpg?raw=true" width="66%" />

### 🚀: SliceUpsamp design
<img src="assets/SliceUpsamp.jpg?raw=true" width="66%" />

## Installation

The code requires `python>=3.7`, as well as `pytorch>=1.7` and `torchvision>=0.8`. Please follow the instructions [here](https://pytorch.org/get-started/locally/) to install both PyTorch and TorchVision dependencies. Installing both PyTorch and TorchVision with CUDA support is strongly recommended.

The following optional dependencies are necessary for mask post-processing, saving masks in COCO format, the example notebooks, and exporting the model in ONNX format. `jupyter` is also required to run the example notebooks.

```
pip install opencv-python pycocotools matplotlib
```

## Citing DENet

If you use DENet in your research, please use the following BibTeX entry.

```
@article{DENet,
  title={Domain-incremental Learning for Fire Detection in Space-air-ground Integrated Observation Network},
  author={Ming Wang, Dayu Yu, Wanting He, Peng Yue, Zheheng Liang},
  journal={International Journal of Applied Earth Observation and Geoinformation},
  year={2023}
}

```
