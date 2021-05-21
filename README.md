# Insights-into-few-shot-learning-for-scene-classification

### Datasets

**MiniSun** 

The MiniSun dataset contains 100 classes randomly chosen from sun397 with 100 images of size 84×84 pixels per class. It is split into 64 base classes, 16 validation classes and 20 novel classes.

**MiniPlaces**

The MiniPlaces dataset contains 100 classes randomly chosen from Places with 600 images of size 84×84 pixels per class. It is split into 64 base classes, 16 validation classes and 20 novel classes.

### Pipeline 

![](https://raw.githubusercontent.com/MohmedSoudy/Insights-into-few-shot-learning-for-scene-classification/main/Graphical%20abstract.jpeg)


### Proposed models 

![](https://raw.githubusercontent.com/MohmedSoudy/Insights-into-few-shot-learning-for-scene-classification/main/Figure%203.jpeg)

### Results 

|                  | MiniSun          |                  |          
|------------------|------------------|------------------|
| **k-way**        | **5**            |**5**             |
| **n-shot**       | **5**            |**1**             |
| MobileNetV2      | 20.16 ± 0.011    |                  |
| Conv4            | 39.14 ± 0.015    | 26.03  ± 0.013    |
| Conv6            | 33.42 ± 0.015    | 24.58  ± 0.012   |
| Conv8            | 29.32 ± 0.012    | 21.48  ± 0.011   |
| MobileBlock1     | 40.12 ± 0.015    |**30.86 ± 0.01**  |
| MobileConv       |**47.5 ± 0.0158** | 30.72  ± 0.013   |


|                  | MiniPlaces       |                  |          
|------------------|------------------|------------------|
| **k-way**        | **5**            |**5**             |
| **n-shot**       | **5**            |**1**             |
| Conv4            | 27.9   ± 0.014   | 29.62 ± 0.013    |
| Conv6            | 19.84  ± 0.007   | 21.42 ± 0.009    |
| Conv8            | 25.2   ± 0.011   | 21.14 ± 0.004    |
| MobileConv       |**34.64 ± 0.014** | 26.36 ± 0.013    |
