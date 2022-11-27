# source 
https://www.kaggle.com/datasets/sudhanshu2198/oil-spill-detection

# About Dataset
The dataset was developed by starting with satellite images of the ocean, some of which contain an oil spill and some that do not.
Images were split into sections and processed using computer vision algorithms to provide a vector of features to describe the contents of the image section or patch.
The task is, given a vector that describes the contents of a patch of a satellite image, then predicts whether the patch contains an oil spill or not, e.g. from the illegal or accidental dumping of oil in the ocean.

There are two classes and the goal is to distinguish between spill and non-spill using the features for a given ocean patch.

* Non-Spill: negative case, or majority class.
* Oil Spill: positive case, or minority class.