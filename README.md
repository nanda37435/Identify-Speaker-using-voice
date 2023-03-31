# Identifying Speaker Using Voice


Steps to follow to execute the project
* Download the repository
* Install all the python packages present in requirements.txt file using pip install -r requirements.txt
* Execute the Identify_Speaker.py file using python3 interpretor


How it works
* On execution, it shows the menu to choose one of the following: Record audio for Training, Record audio for Testing, Train model, Test model
* For each person, model requires five audio clips each with 10 seconds human voice in it for training
* Once training is done, we can test our model with one 10 seconds voice clip at a time and see the results if it predicts the correct person based on the training set.
* We have separate folders for storing the training data, testing data and pickle files of trained models.
* Also, we store the names of persons whose voice is used in training of the model in a .txt file.
* As far as now, we can test only 1 audio clip at once.

