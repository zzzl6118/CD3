
# Change-Preserving Geometric Disentanglement for Fine-Grained Change Detection in Unregistered Remote Sensing Images
## 🛠️ Environment Setup

### Dependencies

```bash
Python 3.8.0
pytorch 1.10.1
torchvision 0.11.2
einops  0.3.2
# other necessary dependencies
```
## ⚡ Ready-to-Run Implementation

**This code is designed to run out-of-the-box.** After following the installation steps below and downloading the required dataset, you can directly execute the main script. Simply download the dataset and update the data path in `data_config.py` file. If you encounter any issues running the code, please don't hesitate to contact me immediately (contact details below)

## Dataset Preparation
- Download the datasets 
- Extract the dataset to your preferred location
- Update the dataset path in data_config.py to point to your dataset location:

# Example of updating data_config.py
self.root_dir = 'D:/Codes/data/LEVIR-CD-V1/' 

## 📁 Project Structure

```
.
├── main.py           # Main execution file
├── model/            # Model implementation
│   ├── __init__.py
│   ├── networks.py   # Network architecture definition
│   └── ...
├── utils/            # Utility functions
├── configs/          # Configuration files
└── README.md
```

## 🚀 Usage

The code implements training and testing pipeline, which can be run with:

```bash
python main.py
```

More parameter settings and detailed instructions will be provided after the paper is published.

## ⏳ Coming Soon

- Detailed method description
- Complete experimental results
- Support for additional datasets

## 📮 Temporary Contact

If you have any questions or suggestions regarding this research, please contact:
zhi_li_8003@163.com

---
