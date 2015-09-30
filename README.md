###Predicting Attractiveness using Computer Vision
This is the companion code of my blog [post](http://www.learnopencv.com/computer-vision-for-predicting-facial-attractiveness/).

![alt tag](http://www.learnopencv.com/wp-content/uploads/2015/07/2_det_0.jpg)


### Feature Generation
The features computation part of the pipeline requires the location of facial landmars of the input images.
These landmarks can be generated by the [CLM-framework](https://github.com/TadasBaltrusaitis/CLM-framework).

###Requirements
1. Python 2.7
2. Numpy
3. scikit-learn

###Prerequisites
#Ubuntu:
sudo apt-get install python-sklearn

#Mac OSX:
pip install -U numpy scipy scikit-learn

#Windows:
pip install -U scikit-learn

License: MIT
