# Detect crown-of-thorns starfish in underwater image data
Challenge context see: https://www.kaggle.com/competitions/tensorflow-great-barrier-reef

## Data source
Image from 3 video clips shot by snorkel divers, 23501 images in total and 4919 images with annotation

For full context please check out the Kaggle challenge page

## Models
Resnet-50, limited to small dataset due to CUDA memory limit on Google Colab
Yolov5, more training and higher f2 overall
