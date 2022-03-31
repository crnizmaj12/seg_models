Seg-Models Python API
==============================


Getting started with Seg-Models is easy.

Unet
~~~~
.. autofunction:: seg_models.Unet

Linknet
~~~~~~~
.. autofunction:: seg_models.Linknet

FPN
~~~
.. autofunction:: seg_models.FPN

PSPNet
~~~~~~
.. autofunction:: seg_models.PSPNet

metrics
~~~~~~~
.. autofunction:: seg_models.metrics.IOUScore
.. autofunction:: seg_models.metrics.FScore

losses
~~~~~~
.. autofunction:: seg_models.losses.JaccardLoss
.. autofunction:: seg_models.losses.DiceLoss
.. autofunction:: seg_models.losses.BinaryCELoss
.. autofunction:: seg_models.losses.CategoricalCELoss
.. autofunction:: seg_models.losses.BinaryFocalLoss
.. autofunction:: seg_models.losses.CategoricalFocalLoss

utils
~~~~~
.. autofunction:: seg_models.utils.set_trainable