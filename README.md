# DGC-DETR
## Offcial implementation of "Dual-Stream Geometric-Semantic Compensation Detection Transformer for All-Weather Cattle Behaviour Recognition".

![pipeline](./DGCDETR/overall.jpg)

## 1. Dependencies
```

grad-cam==1.5.4          
ipykernel==7.1.0         
ipython==8.38.0       
numpy==2.2.6         
opencv-python==4.13.0.90     
pandas==2.3.3         
pillow==12.1.0     
pip==25.3          
prettytable==3.17.0      
psutil==7.2.2         
python==3.10.19        
scipy==1.15.3         
setuptools==80.10.1        
six==1.17.0       
tensorboard==2.20.0        
tensorboard-data-server==0.7.2       
threadpoolctl==3.6.0      
timm==1.0.24        
tk==8.6.15         
torch== 2.3.1+cu121      
torchaudio==2.3.1+cu121     
torchvision== 0.18.1+cu121   
tornado== 6.5.4          
tqdm==4.67.2         

```
## 2. Usage
### 2.1 Data preparation

![pipeline](./DGCDETR/S)

We created a large traffic accident dataset called 4M-TAD containing frame-level labels standardized for unsupervised traffic accident detection.

As the paper is currently in the process of submitting, the dataset needs to be kept confidential for the time being, here we only disclose part of the dataset:

[4M-TAD_Part_1](https://drive.google.com/file/d/142zp6sD6WZ6RyWt0QTmOAmB7msLV8KVQ/view?usp=drive_link)

The full dataset will be updated after the acceptance of the article.

### 2.2 Train
The paper is under review and now needs to be kept confidential.
Code will be available soon.
### 2.3 Evaluation
The paper is under review and now needs to be kept confidential.
Code will be available soon.

## 3. Results
mAP is the core indicator.

|     Model      | mAP@50 | mAP@75 | mAP@50:95 |
| :------------: | :-------: | :---------: | :---------: | 
|    DGC-DETR    | 93.77% | 92.30% |  87.62%   |

## Acknowledgment
The paper is under review and now needs to be kept confidential.

## Citation
The paper is under review and now needs to be kept confidential.
