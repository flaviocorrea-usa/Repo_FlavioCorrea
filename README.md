# 👁️ Computer Vision & Deep Learning — Flavio Correa

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![PyTorch / TensorFlow](https://img.shields.io/badge/Deep%20Learning-CNNs%20%7C%20ViT%20%7C%20Diffusion-8A2BE2)
![Notebooks](https://img.shields.io/badge/notebooks-20-2ea44f)
![Updated](https://img.shields.io/badge/updated-2026-blue)

A hands-on portfolio of computer vision work — from basic image handling to transformers, diffusion models, 3D geometry and motion. Every notebook can be **viewed on GitHub** or **opened and run in Google Colab** with one click.

---

## 🗺️ Learning path

```mermaid
flowchart LR
    A[01 · Image Data] --> B[04 · ConvNets]
    B --> C[04B · Transfer Learning]
    C --> D[05 · Vision Transformers]
    D --> E[06 · Autoencoders & Captioning]
    E --> F[07 · Diffusion / DDIMs]
    F --> G[08 · Object Detection]
    G --> H[09 · Semantic Segmentation]
    H --> I[10 · Homography]
    I --> J[11 · Monocular Depth]
    J --> K[12 · Optical Flow]
    K --> P((🏁 Final Project))

    classDef found fill:#dbeafe,stroke:#2563eb,color:#1e3a8a;
    classDef gen fill:#ede9fe,stroke:#7c3aed,color:#4c1d95;
    classDef scene fill:#dcfce7,stroke:#16a34a,color:#14532d;
    classDef geo fill:#fef3c7,stroke:#d97706,color:#78350f;
    class A,B,C,D found;
    class E,F gen;
    class G,H scene;
    class I,J,K geo;
```

<sub>🔵 Foundations &nbsp;·&nbsp; 🟣 Generative models &nbsp;·&nbsp; 🟢 Scene understanding &nbsp;·&nbsp; 🟠 Geometry & motion</sub>

---

## 📂 Modules

| # | Module | What it covers | Open |
|:-:|---|---|:-:|
| 01 | [**Working with Image Data**](01_Working-with-Image-Data) | Loading, inspecting and transforming images as arrays | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/01_Working-with-Image-Data/1_WorkingWithImageData_FlavioCorrea.ipynb) |
| 04 | [**Intro to ConvNets**](04_Intro-to-ConvNets) | Convolutional neural networks for image classification | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/04_Intro-to-ConvNets/4_IntroToCovNetsForCV_FlavioCorreaMar052026_549PM.ipynb) |
| 04B | [**Transfer Learning & Augmentation**](04B_Transfer-Learning-and-Augmentation) | Fine-tuning pretrained models; data augmentation | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/04B_Transfer-Learning-and-Augmentation/4B_TransferLearningDataAugmentation_FlavioCorrea_2026_Mar08.ipynb) |
| 05 | [**Vision Transformers**](05_Vision-Transformers) | Image classification with ViT | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/05_Vision-Transformers/5_Image_Classification_with_Vision_Transformer_FlavioCorrea_11Mar2026.ipynb) |
| 06 | [**Autoencoders & Image Captioning**](06_Autoencoders-and-Image-Captioning) | Encoder–decoder models that describe images in text | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/06_Autoencoders-and-Image-Captioning/Copy_of_6_Autoencoder_Image_Captioning_FlavioCorrea_run2026Mar12_1211PM.ipynb) |
| 07 | [**Diffusion Models (DDIMs)**](07_Diffusion-DDIMs) | Denoising diffusion implicit models for image generation | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/07_Diffusion-DDIMs/7_IntroductionToDDIMs.ipynb) |
| 08 | [**Object Detection**](08_Object-Detection) | Locating and classifying multiple objects per image | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/08_Object-Detection/8_ObjectDetection_Flavio_Correa_2026Apr03.ipynb) |
| 09 | [**Semantic Segmentation**](09_Semantic-Segmentation) | Pixel-level classification of scenes | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/09_Semantic-Segmentation/9_SemanticSegmentation_FlavioCorrea_2026Apr08_run444PM.ipynb) |
| 10 | [**Homography & Projections**](10_Homography-and-Projections) | Planar transformations, warping and image alignment | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/10_Homography-and-Projections/10_HomographyProjections_16Apr2026_run1127PM.ipynb) |
| 11 | [**Monocular Depth Estimation**](11_Monocular-Depth-Estimation) | Predicting depth from a single image | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/11_Monocular-Depth-Estimation/11_Monocular_Depth_Estimation_Flavio_Correa_runApr22_1022AM.ipynb) |
| 12 | [**Optical Flow**](12_Optical-Flow) | Estimating motion between video frames | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/12_Optical-Flow/12_OpticalFlow_Flavio_Correa_run_May3rd_840PM.ipynb) |
| 🏁 | [**Final Project**](Final-Project) | Capstone applying the techniques above | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/flaviocorrea-usa/Repo_FlavioCorrea/blob/main/Final-Project/Project_FlavioCorrea_2026Apr09_1137PM.ipynb) |

> The Colab button opens the most recent run of each module. Earlier runs are kept inside each folder.

---

## 🧱 Repository structure

```
Repo_FlavioCorrea/
├── 01_Working-with-Image-Data/
├── 04_Intro-to-ConvNets/
├── 04B_Transfer-Learning-and-Augmentation/
├── 05_Vision-Transformers/
├── 06_Autoencoders-and-Image-Captioning/
├── 07_Diffusion-DDIMs/
├── 08_Object-Detection/
├── 09_Semantic-Segmentation/
├── 10_Homography-and-Projections/
├── 11_Monocular-Depth-Estimation/
├── 12_Optical-Flow/
├── Final-Project/
└── README.md
```

## 🚀 Run locally

```bash
git clone https://github.com/flaviocorrea-usa/Repo_FlavioCorrea.git
cd Repo_FlavioCorrea
pip install jupyter numpy matplotlib opencv-python torch torchvision
jupyter notebook
```

> 💡 If a notebook doesn't render on GitHub (large outputs), open it on [nbviewer](https://nbviewer.org/github/flaviocorrea-usa/Repo_FlavioCorrea/tree/main/) instead.

---

## 👤 About

**Flavio Correa** · Tampa, FL
[![GitHub](https://img.shields.io/badge/GitHub-flaviocorrea--usa-181717?logo=github)](https://github.com/flaviocorrea-usa)
