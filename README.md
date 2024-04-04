# Deep-Learning-Challenge
# Overview:
The Foundation Alphabet Soup wants a tool that will help determine the applicants success if it were to be funded by the foundation.
This is important because it helps the Foundation find great applicants whom will actually make very good use of the donation by becoming successful. 
# Results: 
The target for our model was to found wether the applicant will be succesful or isn't. 
## Data Preprocessing
I first imported the datset `charity_data.csv`, and made it into a df to better understand the data. I then, dropped  2 coulumns from the dataset `EIN` and `NAME` because it wasn't necessary. 
To help contribute to the classification if it's successful or isn't, I found the different `application types` and the `classification` for each type. Then, The data was split into training and test subsets with `Classification` and `Type`. 
## Compiling, Training, and Evaluating the Model
I compiled, and trained my model once.
My model's accuracy was a 73% which was really close to the target of 75%.
To get to a higher accuracy, I would probably need to train my model a few more times to reach the target of 75%.
# Summary:
The accuracy was off the target by 2%. Therefore, I failed. To meet the target goal, I could keep trainig data in order to meet the target goal of `75%`. If the results keep being similar of an accuracy below 75% and around 73%, the model might be needed to be modified.
# Challenges
I encounter many challenges in the Compile, Train and Evaluate section. I overcame them by asking for help to ChatGDP, looking at previous class recordings, and going back to class activities.
The first challenge I enounter was figuring out the hidden notes like where was a great place to separe the data. I figured it was best between where there was a noticeable gap in the amount.  The second challenge was evaluating the model using the test data. My code seem right, but there was still an issue. Consequently, I looked at Class Activieties, and my work seem right. To fix my error, I just refreshed my Google Colab Notebook. The last challenge I encounter was figuring out how to export the model to HDF5 file. I looked at class activies, but it seemed like we had just imported HDF5, so I went over to ChatGDP and received help on how to import it. 
