# OpenCV Fundamentals Assignment

<p align="center">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge" />
  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge" />
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge" />
  <img alt="Computer Vision" src="https://img.shields.io/badge/Computer%20Vision-5C3EE8?style=for-the-badge" />
</p>

<p align="center">
  <strong>A notebook-based computer-vision assignment covering foundational OpenCV operations and image-processing workflows.</strong>
</p>

cv2_assign presents core OpenCV concepts in a reproducible notebook format. It is structured for review, experimentation, and extension into more advanced image-processing pipelines.

## Core Capabilities

- Demonstrates foundational OpenCV operations.
- Uses a notebook workflow for step-by-step inspection.
- Supports image-processing experimentation and visual output review.
- Documents setup and execution for straightforward reproduction.

## Technical Architecture

The repository centers on one Jupyter notebook. This structure keeps the computer-vision workflow visible from input through transformation and output.

## Architecture Diagram

```mermaid
flowchart LR
  Images["Image Inputs"] --> Notebook["OpenCV Notebook"]
  Notebook --> Operations["Core CV Operations"]
  Operations --> Visuals["Intermediate Visual Outputs"]
  Visuals --> Results["Final Processed Images"]
```

## Technology Stack

- Python notebook workflow.
- OpenCV for image-processing operations.
- NumPy for array-level image manipulation.
- Jupyter for visual execution and explanation.

## Repository Structure

- `cv2-basic.ipynb` - Primary OpenCV assignment notebook.

## Getting Started

```bash
python -m venv .venv
source .venv/bin/activate
pip install opencv-python numpy matplotlib jupyter
```

```bash
jupyter notebook cv2-basic.ipynb
```

## Professional Context

This project demonstrates computer-vision fundamentals, reproducible notebook practice, and image-processing experimentation.
