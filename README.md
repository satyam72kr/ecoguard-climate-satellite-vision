# EcoGuard Climate Intelligence and Satellite Computer Vision Framework

A remote sensing computer vision framework engineered to analyze climate anomalies, forest fire zones, and flood distributions from high-resolution satellite imagery layers.

## Key Highlights and Metrics
* Advanced Deep Backbone: Utilized a 50-layer deep ResNet50 convolutional neural network to accurately extract intricate features from multi-spectral environmental assets.
* Planetary Risk Visualization: Integrated custom thermal attention heatmaps to localize environmental damage zones and assist analysts in rapid climate risk evaluation.
* Remote Sensing Optimization: Formulated a dedicated contrast enhancement pipeline using OpenCV to handle atmospheric haze and localized lighting variations in raw scans.
* Production Grade Workstation: Deployed an interactive web dashboard via the Gradio framework to allow environmental data scientists to perform live visual diagnostics.

## Tech Stack and Tools Used
* Core Deep Learning: Python, PyTorch, Torchvision, Transfer Learning Architecture
* Computer Vision: OpenCV (cv2), Detail Enhancement Filtering Algorithms, NumPy
* Deployment Framework: Gradio Interface, Google Colab Environment, Tesla T4 GPU

## Repository Structure
* climate_ai.ipynb: Executable production notebook containing the satellite image preprocessing functions, model definition layer, and interactive dashboard layouts.

## How to Execute the Project
1. Open the source notebook file in Google Colab and switch the hardware accelerator type to the T4 GPU option before running any cells.
2. Run the script cells sequentially to automatically update local dependencies, initialize the weight matrices, and generate the live public web link.
