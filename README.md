# Urban Green Space Analysis Using Deep Learning

This repository contains the work for a project focused on analyzing urban green spaces using a deep learning framework. The project fine-tuned some semantic segmentation models to process street-level imagery and quantify urban greenery within the images.

## Project Structure
- `fine_tuning.ipynb`: Jupyter notebook that contains the fine-tuning process and evaluations of our deep learning models on the ADE20k dataset.
- `green_ratio.ipynb`: Jupyter notebook that processes the images and computes the green ratio - a measure of green space within each image.
- `fine-tuned model weights`: model weights can be found in this link: https://drive.google.com/drive/u/1/folders/18Cw7GInPbGwn8t7Mx7Q9XRdYrVLNnQGE

## Data

The data used in this project is sourced from the publicly available dataset on Kaggle: [Geolocation GeoGuessr Images](https://www.kaggle.com/datasets/ubitquitin/geolocation-geoguessr-images-50k/code). It includes 50,000 geo-tagged street view images from various urban areas.

## Requirements

The project was developed using Python 3.8, GPU of 4080 and T4

