# CNN-Image-Classifier
This project was the final project for USC DSCI 552 - Machine Learning for Data Science, in Spring, 2023. This project tasked students with using transfer learning to classify images of notable architectural landmarks into 2 categories: architectural category (i.e. Gothic, Neoclassical, Pagodas) and exact landmark name (i.e. Chartres Cathedral, Academy of Athens, Fogong Temple Pagoda). The training/validation dataset comprised of 6 architectual categories with 5 landmarks each. Each landmark had with 14 images, for a total of 420 training/validation images. 

The .ipynb files in this depository are for demonstration purposes only. The training data has not been provided, and the filepaths are hardcoded to local settings.



"Training.ipynb" demonstrates the data collection/cleaning/preparation, the building of the category and landmark classifiers, fitting the models to the training set, and saving the models to .h5 files.

"Testing.ipynb" demonstrates the loading of the pre-trained models (.h5 files) and predicting on new testing data.
