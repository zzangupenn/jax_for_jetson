# jax_for_jetson_orin

## For Jetson Xavier
You can try these built [wheel files](https://drive.google.com/drive/folders/16XHsvKMb5L744dCcH9M1xWInWsjZfygi?usp=sharing).

#### This repo is deprecated. The newer version is out. [Here](https://github.com/zzangupenn/jax_ros_docker_jetson) is a ROS+JAX container.

JAX 0.4.26 is built on Jetson Orin NX with Jetpack 6.0. Newer versions fail, maybe due to cudnn version.

## Built wheels
### [python 3.10, numpy 1.22](https://drive.google.com/file/d/1a63g4pEbtcAZXusio99A_nzoIwKK-LJF/view?usp=sharing)
### [python 3.10, numpy 1.26.4](https://drive.google.com/file/d/1kaLXBcUPg99orAJQ09XOZ5RtRFtAd7oL/view?usp=sharing)
### [python 3.11, numpy 1.26.4](https://drive.google.com/file/d/1dP7sEI9JeMMQ8OtwlFLyJzh_KlwBRJBH/view?usp=sharing)

## Install Jaxlib
```
pip install <path_to_wheel> --force-reinstall
```

## Install Jax
```
pip install jax==0.4.26
pip install numpy==1.26.4
```

## Libraries compatible with 0.4.26
```
pip install flax==0.8.2 chex==0.1.86 optax==0.2.2 orbax-checkpoint==0.6.3
```

## Libraries that seems compatible
```
pip install flax==0.8.5 chex==0.1.86 optax==0.2.3 orbax-checkpoint==0.6.3
```
