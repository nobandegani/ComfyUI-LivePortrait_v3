# Comfyui_Liveportrait_v3
![image](https://github.com/user-attachments/assets/5a7f07e8-c856-4a6e-ad81-82ebe1d5934d)

## 🔥 Updates
We support image driven mode and regional control for Comfyui!!!
Using a simple way to use an image as a driving signal to drive the source image or video!
## Introduction 
This repo, named Comfyui_Liveportrait_v3, thanks to paper LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control.
We developed a custom_node for Liveportrait_v3 that enables flexible use on Comfyui to drive image-based emoji generation from photos.
## Getting Started
### 1. Clone the code and prepare the environment 
```bash
git clone https://github.com/VangengLab/Comfyui_Liveportrait_v3.git
cd Comfyui_Liveportrait_v3
pip install -r requirements.txt
```
## Download pretrained weights
The easiest way to download the pretrained weights is from HuggingFace:
```bash
huggingface-cli download KwaiVGI/LivePortrait --local-dir pretrained_weights --exclude "*.git*" "README.md" "docs"
```
If you cannot access to Huggingface, you can use hf-mirror to download:
```bash
export HF_ENDPOINT=https://hf-mirror.com
huggingface-cli download KwaiVGI/LivePortrait --local-dir pretrained_weights --exclude "*.git*" "README.md" "docs"
```
you can also visit LivePortrait github searching those pretrained weights,but remember put them to models/liveportrait

​​![cbedb95a-7d1a-4686-8d26-4b72d9f75552](https://github.com/user-attachments/assets/ef1d9943-5a47-4191-a683-3804439c6197)


###maybe there will be some problem about locating models,please use the abusolte address,or tell me I will offer you help.


