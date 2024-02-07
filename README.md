# Swin Transformer Underwater Image Enhancement: Reinforced Swin-Convs Transformer for Simultaneous Underwater Sensing Scene Image Enhancement


---


[ <a href="https://colab.research.google.com/drive/1vkkVz_ZYtqGHsPT97HXOAsNWVRhbLIds?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="google colab logo"></a>](https://colab.research.google.com/drive/1vkkVz_ZYtqGHsPT97HXOAsNWVRhbLIds)


This repository is the PyTorch implementation of Swin Transformer Underwater Image Enhancement: Reinforced Swin-Convs Transformer for Simultaneous Underwater Sensing Scene Image Enhancement
<img width="1000" src="Swin network.png">

## Contents

1. [QucikStart](#QuickStart)
2. [Training](#Training)
3. [Testing](#Testing)
4. [Download](#Download)
5. [Citation](#Citation)


## QuickStart
### Attention: Please ensure the pytorch version be same with requirements.txt

### Start a custom training
We have put demo data in folder "_./dataset_", hence you can run file "_*Enh_train.py_" in  folder "_./scripts_".

### Start a test with pre-trained model
If you want to use the pre-trained model for testing, please read the following content about data settings. After that, run file "*Enh_eval.py" in folder "./scripts".

## Training 
### 1. Put your dataset into your folder storing data (for example "_./dataset/demo_data_Enh_") as follows:
_SWIM-TRANSFORMER-BASED-UNDERWATER-IMAGE-ENHANCEMENT_<br />
├─ other files and folders<br />
├─ _dataset_<br />
│&ensp;&ensp;├─ _demo\_data\_Enh_<br />
│&ensp;&ensp;│&ensp;&ensp;├─ _train\_data_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ _input_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ _fig1.png_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ ...<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ _target_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ _fig1.png_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ ...<br />
│&ensp;&ensp;│&ensp;&ensp;├─ _val\_data_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ ...<br />
│&ensp;&ensp;│&ensp;&ensp;├─ _test\_data_<br />
│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;│&ensp;&ensp;├─ ...

