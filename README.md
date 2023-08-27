

# Wheat Head Detection using Faster RCNN

Wheat is a staple across the globe and makes up the dominant part of a population's diet. Climate change, extreme heats and other conditions threatened the cultivation yield and health of the wheat. By estimating the density and size of wheat heads farmers can better assess their crops health, also help reseacher study the effect of climate change on food cultivation across globe.

![](https://i.ibb.co/WvSqSpr/9818452-fig-001.jpg)

Challenges in correctly detecting wheat heads. 
- overlap of dense wheat plants, and the wind can blur the photographs.
- Appearances vary due to maturity, color, genotype, and head orientation.
- Wheat is grown worldwide, different varieties, planting densities, patterns, and field conditions must be considered.

**The main goal of this project is to develop a object detection model using FasterRCNN architecture focusing on a generalized solution to estimate the number and size of wheat heads in an images.**

## 🔗 Links

- [Dataset](https://www.kaggle.com/competitions/global-wheat-detection/data)
- [Learned Model Weights](https://www.kaggle.com/code/sudhanshu2198/wheat-head-detection-using-faster-rcnn-pytorch/output?select=model.pth)
- [Kaggle Notebook](https://www.kaggle.com/code/sudhanshu2198/wheat-head-detection-using-faster-rcnn-pytorch/notebook)

## 🛠 Skills
Numpy, Matplotlib, Pandas, OpenCV, Pytorch, torchvision, albumentations

## Comparison between Ground truth and Predicted Bounding Boxes
![](https://i.ibb.co/PGKWW09/44.png)

## Results

**The model achieved a map(mean average precision) of .78 at IOU=0.5.Non-max suppression is performed on model output with conf_threshold=0.5 and iou_threshold=0.8. The model is trained for 50 epochs with ReduceONPlateau learning rate schedulers.**

![](https://i.ibb.co/9VDQ5tP/3-1.jpg)




