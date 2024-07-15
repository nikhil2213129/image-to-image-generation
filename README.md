# Grayscale Image Generation with StyleGAN2

This project involves generating grayscale images using the StyleGAN2 model. The code takes grayscale images as input, processes them using StyleGAN2, and outputs grayscale images. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

StyleGAN2 is a state-of-the-art generative adversarial network for generating high-quality images. This project adapts StyleGAN2 to work specifically with grayscale images, maintaining the grayscale format throughout the processing pipeline.

## Features

- Load and preprocess grayscale images
- Use StyleGAN2 to generate grayscale images
- Display generated images in grayscale format

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/grayscale-stylegan2.git
    cd grayscale-stylegan2
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install torch torchvision numpy scipy pillow requests dnnlib click tqdm matplotlib

    ```

## Usage

1. Download the pretrained StyleGAN2 model (e.g., `ffhq.pkl`) and place it in the project directory.

2. Update the dataset path in the script to point to your grayscale image dataset:
    ```python
    dataset_path = '/path/to/your/grayscale/images'
    ```

3. Run the script:
    ```bash
    python generate_grayscale_images.py
    ```

## Dataset

The dataset should consist of grayscale images in `.jpg` format. 
dataset_path = '/kaggle/input/landscape-image-colorization/landscape Images/gray'


## Results

The generated images will be displayed as grayscale images. You can save the generated images by modifying the script to include save functionality.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
