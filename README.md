# MacnCheese Detector Dataset

This is a dataset that I collected to train my own MacnCheese detector with [TensorFlow's Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection). Images are from Google and Pixabay. In total, there are 154 images (142 are used for training and 12 for validation).

## Getting Started

##### Folder Structure:
```

+ data: contains the input file for the TF object detection API and the label files (csv)
+ images: contains the image data in jpg format
+ training: contains the pipeline configuration file, frozen model and labelmap
- a few handy scripts: generate_tfrecord.py is used to generate the input files
for the TF API and xml_to_csv.py is used to convert the xml files into one csv

```

