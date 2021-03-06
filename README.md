<p align="center">
  <img src="docs/images/wgan-logo.jpg">
</p>

------------

## Getting Started

Clone the repository, navigate to the local directory and run:

```
python main.py
```

<p align="center">
<img src="plots/epoch_0-image_0.png" width="200" height="200">
<img src="plots/epoch_0-image_1.png" width="200" height="200">
<img src="plots/epoch_0-image_2.png" width="200" height="200">
<br>
<img src="plots/epoch_40-image_0.png" width="200" height="200">
<img src="plots/epoch_40-image_1.png" width="200" height="200">
<img src="plots/epoch_40-image_2.png" width="200" height="200">
<br> 
Sample images created by the generator at epochs 0 and 40.
</p>


### Prerequisites

* Keras >= 2.0.8
* TensorFlow >= 1.3.0
* Numpy >= 1.13.3
* Matplotlib >= 2.0.2
* Seaborn >= 0.7.1

## Built With

* [TensorFlow](https://github.com/tensorflow/tensorflow) - A deep learning library
* [Keras](https://github.com/keras-team/keras) - A high-level deep learning package built upon TensorFlow

## Authors

* **David Reiman** - [davidreiman](https://github.com/davidreiman)

## References

* [Wasserstein GAN](https://arxiv.org/abs/1701.07875) - Original paper by Arjovsky et al.
* [Wasserstein implementation](https://github.com/martinarjovsky/WassersteinGAN) - Original implementation by Arjovsky et al.
* [Wasserstein GAN in Keras](https://github.com/tdeboissiere/DeepLearningImplementations/tree/master/WassersteinGAN) - Keras implementation of Wasserstein GAN
