# Summary
Object detection is the task of detecting and classifying every object of interest in an image. In computer vision, this technique is used in applications such as picture retrieval, security cameras and autonomous vehicles.

One of the most famous families of Deep Convolutional Neural Networks (DNN) for object detection is the YOLO (You Only Look Once), achieving near state-of-the-art results with a single end-to-end model (Redmon, Joseph, et al. — 2016). However, to run it in real-time, it’s necessary to have a good graphics card, like an Nvidia Tesla V100 (Bochkovskiy, A., Wang, C. Y., & Liao, H. Y. M. — 2020), not accessible for everyone. So getting these models into production in a cost-effective way remains a core challenge.

In this post, we are going to develop an end-to-end solution using TensorFlow to train a custom object-detection model in Python, put it into production, and run real-time inferences in the browser through TensorFlow.js. No powerful computers or complex libraries will be needed.

# links
- [LabelStudio] (https://github.com/HumanSignal/label-studio)
- [tensorjs] (https://towardsdatascience.com/custom-real-time-object-detection-in-the-browser-using-tensorflow-js-5ca90538eace)
- [Convert to html] (https://saturncloud.io/blog/convert-ipynb-notebook-to-html-in-google-colab/)

# Setup

# Requires Python >=3.8
- pip install label-studio

# Start the server at http://localhost:8080
- export DATA_UPLOAD_MAX_NUMBER_FILES=1000000
- label-studio

# Browser
- http://localhost:8080

```
create acct + login
ksericpro@gmail
Sks*12345
```

## create project guitar
import 301 files from data/guitars
configure guitar and human as labels
start labelling for the imported files

# Install 
- pip install tensorflowjs[wizard]
- pip install nbconvert

# Run
- tensorflowjs_wizards

# convert ipynb to HTML
- jupyter nbconvert --to html tensorflow_aquariums.ipynb
