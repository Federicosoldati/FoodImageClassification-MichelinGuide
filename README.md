# FOOD-IMAGE-CLASSIFICATION-MICHELIN-GUIDE

This repository is intended for the group members of the *Advanced Analytics in a Big Data World* course to collaborate for the second assignment (deep learning on images).

- I have included a *create_venv.ps1* file that creates a virtual environment and installs the packages included in the *requirements.txt* file automatically.

- The installed packages for this project are tensorflow, keras, pandas, numpy, tqdm, scikit-learn,scikit-plot, matplotlib, and pillow. However, the produced requirements.txt file in the repository include additional packages that were installed as dependencies. 

- The dataset used for this project is composed of two folders, "food" and "non_food", both located inside a folder called "dataset". The images inside the "non_food" folder should be named as "0_index", while the images inside the "food" folder should be named as "1_index" in order for the model to work properly. So far only 98 images were used to give it a try.

- The procedure followed to solve the given case study involves importing necessary packages, collecting data, performing feature extraction using CNN of Transfer Learning, splitting data into train, validation, and test sets, building machine learning models including logistic regression and SVM for classification, comparing the results obtained, and finally testing the models with real-world data.

- Note that the results obtained from the model are provisional, and this repository only serves as a potential starting point for the final project. The dataset used in this project consists of just 98 images, and the model's performance may vary significantly when using a larger dataset.

- The model can be used to filter out the non-food images from the given dataset for the assignment. This can be done by running all the images through the model and only keeping the ones that the model classifies as food. Once the non-food images have been filtered out, the resulting set of food images can be manually labeled and used as input to train a new model for tasks A) and B). This approach can save time and effort in manually filtering out non-food images and provide a starting point to create a model that predicts the type of cuisine and the expensiveness of the restaurant based on food images.

---

Food Image classification is the process of taking an input like “image”and output us in the form of class like (“food”,”non-food”) or a probability of the particular class (there’s is a probability of 95% that it belongs to class food).


Goal: Building a machine learning model that can distinguish between food and non-food class using CNN for given an input of image.
