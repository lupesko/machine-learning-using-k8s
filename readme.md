# Machine Learning Frameworks on Kubernetes

This repository explains how to run different Machine Learning frameworks on [Amazon EKS](https://aws.amazon.com/eks).

- [Create GPU-enabled Amazon EKS cluster](docs/eks-gpu.md)
- [Setup KubeFlow on Amazon EKS](docs/kubeflow.md)
- [Jupyter Notebook on Amazon EKS](docs/jupyterhub.md)
- Training
  - Single node training for MNIST
    - [TensorFlow + Keras on Amazon EKS](docs/mnist/training/tensorflow-keras.md)
    - [MXNet on Amazon EKS](docs/mnist/training/mxnet.md)  
  - Distributed training
    - [TensorFlow and Horovod on Amazon EKS with ImageNet Data](docs/imagenet/training/tensorflow-horovod.md)
    - [TensorFlow and Horovod on Amazon EKS with Synthetic Data](docs/tensorflow-horovod-synthetic.md)
- Inference
  - [MNIST using TensorFlow Serving Component](docs/mnist/inference/tensorflow.md)
  - [ImageNet using TensorFlow on Amazon EKS](docs/imagenet/inference/tensorflow.md)
- TensorBoard setup
  - [TensorBoard on Amazon EKS](docs/tensorboard.md)
