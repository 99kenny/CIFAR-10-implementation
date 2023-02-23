# VGGNet implementation for CIFAR-10

# Configurations
- VGG19
- Batch size


| batch size  | acc | 
|------|---|
| 32  |  0.9048 |  
| 128  | 0.9218  |   
| 256  | 0.9145  |   



|   regularization    | dropout = 0 | dropout = 0.3 | dropout = 0.5 |
|-------------|-------------|---------------|---------------|
| l2 = 0      |             |               |     0.8904    |  
| l2 = 0.01   |             |               |               |  
| l2 = 0.001  |             |  0.9208       |               |   
| l2 = 0.0001 |             |               |               |

| patience | factor=0.5 | factor=0.3 | factor=0.1|
|------|---|---|---|
| 3  |  0.9218 |   |   |
| 5  |0.9253  |   |   |
| 10  |0.9258   | 0.9270   |  0.9270|

