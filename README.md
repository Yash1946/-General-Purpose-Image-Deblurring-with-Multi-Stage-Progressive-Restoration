🖼️ MPRNet Deblur: General-Purpose Image Deblurring with Multi-Stage Progressive Restoration
Clearer images. Simpler workflow. State-of-the-art deblurring in one click. 

A ready-to-run Colab implementation of MPRNet (CVPR 2021) for high-quality image deblurring—designed for real-world blurry photos, archival images, smartphone captures, or any motion/defocus-degraded input.

🔍 Overview
Blur from camera shake, object motion, or poor focus can ruin otherwise perfect shots. MPRNet Deblur leverages the award-winning Multi-Stage Progressive Image Restoration architecture to recover sharp, detailed, and visually pleasing results—without retraining or fine-tuning.

This project provides a zero-setup, Colab-based pipeline to:

Upload any blurry image
Restore it using the official MPRNet deblurring model
Download a sharp, enhanced version
Perfect for photographers, researchers, or developers integrating deblurring into larger workflows.

🚀 Features
✅ Plug-and-play: Works out of the box with pretrained weights
📸 General-purpose: Handles photos, documents, scenes, faces—no domain constraints
⚡ Fast & lightweight: Runs on Colab CPU or GPU in seconds
🧪 Reproducible: Based on the official MPRNet codebase
📦 Minimal dependencies: Only PyTorch, OpenCV, and standard vision libraries
🛠️ Tech Stack
Core Model: MPRNet — Multi-Stage Progressive Image Restoration (CVPR 2021)
Framework: PyTorch 1.1+
Deployment: Google Colab (ideal for demos & prototyping)
Key Dependencies: opencv-python, Pillow, tqdm, yacs, warmup_scheduler
▶️ Quick Start (Google Colab)
Open the notebook
Upload a blurry image
Run all cells
Get a deblurred result — no configuration needed!
python


1
2
# Behind the scenes:
!python demo.py --task Deblurring --input_dir demo/degraded --result_dir results/
📚 Citation
If you use this project, please cite the original MPRNet paper:

bibtex


1
2
3
4
5
6
7
8
@inproceedings{Zamir2021MPRNet,
  title={Multi-Stage Progressive Image Restoration},
  author={Zamir, Syed Waqas and Arora, Aditya and Khan, Salman and Hayat, Munawar and 
          Khan, Fahad Shahbaz and Yang, Ming-Hsuan and Shao, Ling},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2021},
  pages={285--294}
}
Bring clarity back to your images — effortlessly.
✨ MPRNet Deblur: Where blur meets its match.

