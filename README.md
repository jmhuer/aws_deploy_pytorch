# aws_deploy_pytorch

Other available models from pytorch https://pytorch.org/docs/stable/torchvision/models.html

SageMaker api on PytorchModel: 
https://sagemaker.readthedocs.io/en/stable/frameworks/pytorch/sagemaker.pytorch.html#pytorch-model
https://sagemaker.readthedocs.io/en/stable/frameworks/pytorch/using_pytorch.html#create-a-pytorchmodel-object

understand docker:
https://levelup.gitconnected.com/docker-containers-for-deep-learning-77e8b7e10ef1

We are using  PyTorchModel object instead of PyTorch estimator-this is because no training job is being submitted.

We are using default-pre-built pytorch inference docker image when we call PyTorchModel deployment see docs

*original from https://github.com/aws/amazon-sagemaker-examples/tree/master/sagemaker_neo_compilation_jobs/pytorch_torchvision
