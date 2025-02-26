# UI-Recognition-Project
This project uses YOLO v8, a CNN to identify UI elements in the game: Wargame: Red Dragon.
I used tools such as Pyautogui, and CVAT.ai to collect and annotate the training dataset.
This model will be used for improving upon the accuracy of later models, as I increase the confidence level.

**NAVIGATION**

Inside the training data folder, there are two other folders, as well as a list of files. Below, I explain the contents of some of the files/folders.

**IMPORTANT FILES**

results.png: This file gives overall statistics of the accuracy of the model while training the initial dataset via line-graph format.
confusion_matrix_normalized.png: This file gives the normalized confusion matrix of the dataset, or basically which labels were confused with other labels.
P_curve.png: One of the methods used to evaluate the precision and confidence of my dataset, or how my model's performance was evaluated.

Prediction Results:
Inside Prediction Results, there is a set of images that have had the YOLO prediction algorithm run via my weights inside the weights folder.

Weights:
Inside this folder, you will find the weights of my model that was trained.



