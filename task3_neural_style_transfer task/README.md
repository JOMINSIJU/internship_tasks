# TASK 3
# Neural Style Transfer

## Overview

This project implements **Neural Style Transfer**, a deep learning technique that combines the **content of one image** with the **artistic style of another image** to create a new stylized image. The model extracts the structure of the content image and applies the visual patterns of the style image.

## Objective

To demonstrate how neural networks can apply artistic styles to photographs using Python and deep learning libraries.

## Technologies Used

* Python
* PyTorch
* Torchvision
* PIL (Python Imaging Library)
* Matplotlib

## How It Works

1. A **content image** (photograph) and a **style image** (painting or artwork) are loaded.
2. Both images are converted into tensors using image transformations.
3. The style patterns and textures from the style image are blended with the structure of the content image.
4. The model generates a **new stylized output image**.

## Project Files

* `neural_style_transfer.ipynb` – Jupyter notebook containing the implementation.
* `content.jpg` – Input photograph.
* `style.jpg` – Image containing artistic style.
* `output.jpg` – Generated stylized image.

## Example Workflow

Content Image → Style Image → Stylized Output

The output image preserves the main structure of the content image while adopting the artistic style of the style image.

## Output

The notebook displays:

* Content Image
* Style Image
* Generated Styled Image
