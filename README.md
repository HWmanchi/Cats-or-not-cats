# Cats-or-not-cats
Download the data from: https://github.com/rpeden/cat-or-not/releases.  
Refer to Kaggle https://www.kaggle.com/competitions/dogs-vs-cats, https://www.kaggle.com/code/uysimty/keras-cnn-dog-or-cat-classification.  
Step 1. First, you need to classify the data for training_set & test_set. The training_set is including "cats" & "not cats", and the test_set is also.  
Step 2. Split 80% of training_set data for training, 20% of training_set data for validation.  
Step 3. Mark the "cats" as "0", and "not cats" as "1".  
<Note> Transfer file path to image and show it in the Jupyter notebook.  
Step 4. Data preparation: Data augmentation, resize and dimension confirm which depends on various training model.  
Step 5. Set up the model. (You can do this after Step 3)  
Step 6. Training model.  
Step 7. Pick the data from test_set to predict, and check the prediction accuracy.  
<Note> Check the accuracy. If it's low or incorrect, revise the model and re-training.  
Step 8. Save the model .h5 file.  
