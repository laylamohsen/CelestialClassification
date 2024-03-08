Celestial objects to detect & corresponding models:

# Stellar & Galactic Classification
Simple CNN model that classifies images captured by a telescope to be either a Star or a Galaxy.
Uses Star-Galaxy Dataset:
https://www.kaggle.com/datasets/divyansh22/dummy-astronomy-data

# Nebula, Galaxies, Clusters Detection & Classification
Also includes Mission/Reflection/Dark/Planetary Nebulas, and Globular/Open Clusters.
This uses YOLOv7 for celestial object detection. Uses DeepSpace Dataset, images captured by smart telescope:
https://paperswithcode.com/dataset/deepspaceyolodataset
The YOLO model detects and bounds the celestial object. Bounded image will then be passed
to a classifier which uses the images captured by smart telescope:
https://esahubble.org/images/archive/category/nebulae
https://esahubble.org/images/archive/category/galaxies
https://esahubble.org/images/archive/category/starclusters
