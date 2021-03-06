# Save the Turtles🐢

> An open source sea turtle facial recognition dataset


### Dataset Description:

Currently, the dataset comprises 2000 images scrapped from bing image search and annotated using [makesense.ai](https://www.makesense.ai/).

The dataset is structured in YOLO Darknet txt format with all the images inside `images\` subdirectory and their corresoponding annotation files inside `labels\` subdirectory:

```
data
  |
  |-- images
  |     |
  |     |-- Image_1.jpg
  |     |-- Image_2.jpg
  |     |-- Image_3.jpg
  |     .
  |     .
  |     .
  |-- labels
  |     |
  |     |-- Image_1.txt
  |     |-- Image_2.txt
  |     |-- Image_3.txt
  |     .
  |     .
  |     .
```

#### Note:

> Each label file has the annotations in the followning format ``<object_id> <x> <y> <height> <weight>``


