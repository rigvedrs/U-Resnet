# 3D ResNet combined with encoder using PyTorch :chart_with_upwards_trend:

### A 3D ResNet combined with an encoder to create a U-net having shapes of expansive and contrctive layers derived from ResNet

- The function can generate all ResNet shapes [Resnet10, Resnet18, Resnet34, Resnet50, Resnet101, Resnet152, Resnet200]

- You can also load the pre-trained values of [MedNet3d](https://github.com/Tencent/MedicalNet) in the decoder part of the network

- Code to generate the model is given in [U-ResNet3D](https://github.com/rigvedrs/U-Resnet/blob/main/U-ResNet3D.ipynb)

- Code to load MedNet3D given in [Load MedNet3d](https://github.com/rigvedrs/U-Resnet/blob/main/Load%20MedNet3d.ipynb)

- Network structure parameter settings for loading MedNet3D:
  - resnet_10.pth: model_depth 10 - resnet_shortcut B
  - resnet_18.pth: model_depth 18 - resnet_shortcut A
  - resnet_34.pth: model_depth 34 - resnet_shortcut A
  - resnet_50.pth: model_depth 50 - resnet_shortcut B
  - resnet_101.pth: model_depth 101 - resnet_shortcut B
  - resnet_152.pth: model_depth 152 - resnet_shortcut B
  - resnet_200.pth: model_depth 200 - resnet_shortcut B
  
- The model will require huge GPU size for running so good luck with that :zipper_mouth_face:

- P.S: u can just replace '3D' in the code to '2D' to create a 2-dimensional model

