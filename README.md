# DogBreedClassifier_UT

The main notebook is colled final_notebook.

In order to run our code(final_notebook) you need to install Tensorflow and all other libraries that are imported in the beginning of the notebook, also download train images and labels from KAGGLE (https://www.kaggle.com/c/dog-breed-identification).

First thing we do after importing all of the libraries is loading data and preparing it for fitting into the model. 
We used Sequential model with imported layers of pre-trained model MobileResV2. 
In the end you can see the visualization of the predicted labels. The picture of a dog with correctly predicted label has a green frame and the wrong one has a red frame with the correct answer shown in brackets.

Our notebook also contains analysis of the train process and another model that was not really successful in acheieving a good accuracy results.  
