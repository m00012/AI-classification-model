# AI-classification-model 
# Model building essentials
1. torch.nn - contains all of building for computational graph(nn is a considered coputational graph)
2. torch.nn.Parameter - defines parameters of the model try and lern
3. torch.nn.Module - The base class for all nn modules (requires overwrite forward())
4. torch.optim - this where optimizers in pytorch (helps with Gradient desent)  
5. def forward() - All nn.module subclasses requires to overwrite forward() - defines what happensin forward computation
Load datas and dreresentationata
6. torch.utils.data.Dataset
7. torch.utils.data.Dataloader - allows to iterate over the input data
8. torchvision.transforms
 torchmetric
