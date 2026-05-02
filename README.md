# Anemia Model Builder Lab

This repository contains an end-to-end experimentation workflow for anemia detection using palm images, including baseline deep learning training and advanced ensemble-style modeling.

## Repository Structure

1. `notebooks/core/01_palm_anemia_detection_convnext.ipynb`  
   Main baseline pipeline using TensorFlow + ConvNeXtTiny on palm image data.

2. `notebooks/advanced/02_multimodal_ensemble_anemia.ipynb`  
   Advanced workflow with multi-model and tabular-fusion style experimentation using FastAI components.

3. `notebooks/archive/03_experiments_fastai_timm.ipynb`  
   Archived trial notebook with intermediate experiments and setup iterations.

## Quick Start

1. Open the `core` notebook to run the primary training and evaluation flow.
2. Continue with the `advanced` notebook for improved/extended modeling ideas.
3. Use `archive` only for reference and experiment history.

## Notes

- Notebooks were originally developed in Colab-style environments.
- Update dataset and model paths before running in a new environment.
