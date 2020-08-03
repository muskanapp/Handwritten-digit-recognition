# Handwritten-digit-recognition
![working-model](https://github.com/muskanapp/Handwritten-digit-recognition/blob/master/GIF-200803_061436.gif) 
* Digit recognition system is the working of a machine to train itself or recognizing the digits from different sources like emails, bank cheque, papers, images, etc. and in different real-world scenarios for online handwriting recognition on computer tablets or system, recognize number plates of vehicles, processing bank cheque amounts, numeric entries in forms filled up by hand (say-tax forms) and so on.
* First I have done some exploratory data analysis to discover certain features of the data.Then with a little pre-processing and re-shaping of the data,I have made the data fit for CNN model.
* I have first tried a logistic regression model which gave a 91% accuracy,the I have tried a basic CNN model which gave aroun 99% accuracy and finally a well built CNN which gave around 99.6% accuracy.
* Then I have deployed the model using flask on my local machine.I have uploaded all the files including the model json and h5,css,html,js,python files used in this project.
# Some Implementation details
* Download and install Anaconda using this documentation https://docs.anaconda.com/anaconda/install/
* I have used **Kaggle** instead of my local computer so as to improve the computational speed,since the dataset is quite large,your local machine might hang.
* After running **Digit_Recognizer_10(1).ipynb** on Kaggle,two files namely **model.h5** and **model.json** are generated,download these two files to your local computer.
* It's a good practice to use virtual environment.Create a virtual environment in Anaconda.To learn how use this link- https://heartbeat.fritz.ai/creating-python-virtual-environments-with-conda-why-and-how-180ebd02d1db
* Activate the virtual environment and install Flask using pip (pip install Flask)
* Create a separate folder and then subfolders containing the files as follows namely 
    * model
       * load.py(python file)
       * model.h5(downloaded earlier)
       * model.json(downloaded earlier)
    * static(files created using notepad and saved with the required extensions)
       * index.js
       * style.css
    * templates(files created using notepad and saved with the required extensions)
       * index.html
* Create the python file **app.py**,type the code for deployment of model to flask.
* Go to Anaconda Terminal and run app.py by simply typing app.py in the terminal.
* This should run the application and launch a simple server. 
* Run http://127.0.0.1:5000/ to see the final deployed model.
