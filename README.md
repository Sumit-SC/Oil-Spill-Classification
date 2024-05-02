# Oil-Spill-Classification
## Predicting whether an Ocean patch contains an oil spill or not.

### About Dataset
The dataset was developed by starting with satellite images of the ocean, some of which contain an oil spill and some that do not.

Images were split into sections and processed using computer vision algorithms to provide a vector of features to describe the contents of the image section or patch.

The task is, given a vector that describes the contents of a patch of a satellite image, then predicts whether the patch contains an oil spill or not, e.g. from the illegal or accidental dumping of oil in the ocean.

There are two classes and the goal is to distinguish between spill and non-spill using the features of a given ocean patch.

● <b>Non-Spill:<b> negative case, or majority class.

● <b>Oil Spill:<b> positive case, or minority class.

There are a total of 50 Columns in the Dataset, the output column is named as a target.
### Binder Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Sumit-SC/Oil-Spill-Classification/HEAD)
### Notebook File [nbviewer](https://nbviewer.org/github/Sumit-SC/Oil-Spill-Classification/blob/main/Oil_Spill_Classification.ipynb)
