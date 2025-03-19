**Overview of the analysis: <br>** 
The purpose of this analysis is to help the nonprofit foundation Alphabet Soup decide on applicants to fund for their ventures. We will do this by creating a binary classifier to determine if the applicant would be succesful with funding using machine learning and neural networks.<br>
<br>
**Results:<br>**
<br>
**Data Preprocessing<br>**
<br>
**What variable(s) are the target(s) for your model? <br>**
The target variable in this dataset is the IS_SUCCESSFUL column, (1) being successful while (0) is unsuccessful <br>
<br>
**What variable(s) are the features for your model? <br>**
From the dataset, the feature variables would be all the columns aside from the IS_SUCCESSFUL column. These include: <br>
EIN<br>
NAME<br>
APPLICATION_TYPE<br>
AFFILIATION<br>
CLASSIFICATION<br>
USE_CASE<br>
ORGANIZATION<br>
STATUS<br>
INCOME_AMT<br>
SPECIAL_CONSIDERATIONS<br>
ASK_AMT<br>
<br>
**What variable(s) should be removed from the input data because they are neither targets nor features?**
The EIN and NAME variables were removed from the input data set because they are merely identifiers for each organization which doesn't have an impact on whether it would be successful or not with funding.<br>
<br>
**Compiling, Training, and Evaluating the Model**
<br>
**How many neurons, layers, and activation functions did you select for your neural network model, and why?**<br>
For the first attempt, I used 2 hidden layers, with 80 neurons in the first layer and 30 in the second. Both layers used the relu activation function.<br>
![image](https://github.com/user-attachments/assets/6b23e2d5-a762-4e8b-ae38-88b06c233b39) <br>

For the second attempt, I used 2 hidden layers, with 80 neurons in the first and second layer. Both layers also used the relu activation function.<br>
![image](https://github.com/user-attachments/assets/4607195a-8d9f-4f10-aa54-473eab248d8c) <br>

The third attempt, I kept 2 hidden layers, but increased the number of neurons to 100 in both layers, and I decided to try out the tanh activation function.<br>
![image](https://github.com/user-attachments/assets/10a81f4a-5cf3-4164-a398-3d3033d77697) <br>

The fourth and final attempt included the same number of layers and the same number of neurons, but I decided to use the relu function again.<br>
![image](https://github.com/user-attachments/assets/3588523c-53ad-4949-a466-f65a6f82b038) <br>

Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
