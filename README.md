## Animal-Image-Classification-and-Detection
This repository contains a project based on a University Exam I took for a Deep Learning and Neural Network course. The project's aim was to try to create a Deep Learning model that could classify some images and detect the area of the image in which the object was present. The dataset that was used can be found on Kaggle at this [link](https://www.kaggle.com/datasets/maricinnamon/caltech101-butterfly-dalmatian-dolphin/data) (**NOTE:** the data may be structured in a different way than how it is in the file in this repository, so the data loading part can be different), and it is a subset of the Caltech 101 dataset, containing only images of butterflies, dalmatians and dolphins.

# Project Summary
**1. Data Loading & Analysis:** Here I loaded the dataset and checked its characteristics, in particular with regards to data formatting. I also split the data, separating unlabeled from labeled images

**2. Data Preprocessing:** I did a fundamental part of the prediction task, i.e., data augmentation, for better generalization capabilities of the model

**3. Output Design**: Brief explanation about the design of the output layer of the model, given the multiple tasks to do.

**4. Model Creation**: I described the basic design of the model, with its layers and basic building blocks.

**5. Hyperparameter Tuning:** I did a hyperparameter tuning process to optimize the model, with particular regards to the choices of evaluation for the two different tasks (and their combination)

**5. Model Evaluation & Conclusions**: This final part was dedicated to the evaluation of the model performances, thrugh metrics (f1-score, MSE...), curves and confusion matrices, also by testing the performance on unlabeled data. Conclusions on the model's performances and overall capabilities were drawn.

Please feel free to delve more in depht in the code and descriptions included in the .ipynb file.
