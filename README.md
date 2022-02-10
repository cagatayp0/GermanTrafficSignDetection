# Traffic Sign Detection with Deep Learning

## About the Project

I've done this project for my MEC324 lecture in Turkish-German University. The main goal of this project is to detect and classify traffic signs on a given image. The traffic signs were splitted into 4 classes. Prohibitory, mandatory, danger and other.

## About the Classes

The name of the classes are below.

<ul>
  <li>Prohibitory</li>
  <li>Mandatory</li>
  <li>Danger</li>
  <li>Other</li>
</ul>

### Prohibitory

The traffic signs in this class are round and white. They also have red borders. An example for this class are shown below.

### Mandatory

Traffic signs in this class are blue. There's an illustration shown below.

### Danger

This class contains white and drieckig signs with red border.

### Other

They don't have a specific shape. Any other traffic signs that are not part of the three classes I've mentioned above, belong to this class. Thus, this is the most difficult class to train and they have the least accuracy scores.

## About the Data

The original data are from [German Traffic Sign Detection Benchmark](https://benchmark.ini.rub.de/gtsdb_news.html). It features 900 images, divided by 600 train images and 300 test images. The labeling of this data was not compatible with Yolo format (Yolo wants specific txt files for each class), so I labeled them myself via [Roboflow](https://roboflow.com/). But the images in this dataset were in .ppm format and Roboflow does not support this format. So, I've turned them into .jpg images, and I've also added a validation set. You can access the data from this [kaggle link](https://www.kaggle.com/aatayparlar/german-traffic-sign-detection-benchmark).

## Acknowledgements

http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset
