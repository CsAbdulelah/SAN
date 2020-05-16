

**************************************************  DETECT TOXIC COMMENTS  ****************************************************

*************************************************** DSI7 capstone project  ****************************************************


Abdulelah Alkesaiberi
Norah Alsharif
Sarah Aljudaibi

                           *******************************************************************


Problem statement:

Cyberbullying is an international issue that threatens a teenager's life. 85% of the teens are connected to social media and about half of them have experienced some form of cyberbullying causing a lot of psychological problems producing suicide cases among them. The unsupervised open social environment caused by the internet and hiding behind fake profiles worsening the problem, this all could be through negative comments, posts, memes, and even the regular conversation can be turned into a toxic one and leads to bigger problems.


Introduction:

Today the social media has grown to be a necessary tool for communicating on a personal and practical level but this has consciousness In social platforms it’s possible to be hidden behind fake Identity and can't be recognized. As a result, the internet community becomes more comfortable turning any conversation into a negative one because they know that they can getaway easily from the causes of their behavior.

Our capstone project focus on a model that can identify the toxicity of the conversation on the internet. Using natural Language Processor, we will experience with three models RNN, Bert and XLM Roberta to classify the toxicity of different languages comments like a rude, obscene, insult, threat, identity attack, and normal comments


Objective:

 This Project created to enhance the environment of Social Media and eliminate any toxicity leads to Imbalance in society by showing hatred and fear of self-expression, which in turn leads to killing creative ideas and creating a society with a single order, devoid of creativity and full of negativity.

This all can be achieved by developing an AI model that can detect the toxicity of the comment or sentence and it should also detect toxicity from different languages other than English. It can be implemented in any environment to make it capable of understanding and do the right action at the right time.


Data Dictionary:

### Training Data set-8 col

The dataset is made up of English comments from Wikipedia’s talk page edits.

| Column Name | Description | Type
| :---------- | :---------- | :----|
| Id  | ID | id |
| Commente _text| Comment text need to be examine |String |
| Toxic  | Is’t toxic or not | Integer |
| sever_toxic | Type of toxicity means "is't very toxic" | Integer |
| Obscene | The comment fall under the Obscene Category| Integer |
| Threat  | This comment include Threatening | Integer |
| Insult  | This comment include Insulting | Integer |
| identity_hate| This comment include hate speech or identity hate | Integer |

### Validation Data-4 col

comments from Wikipedia talk pages in different non-English languages.

| Column Name | Description | Type
| :---------- | :---------- | :----|
| Id  | ID | id |
|Commente_text| Comment text need to be examine |String |
| Lang  | The language of the comment | String |
| Toxic  | Is’t toxic or not | Integer |


### Testing Data-3 col

comments from Wikipedia talk pages in different non-English languages.

| Column Name | Description | Type |
| :---------- | :---------- | :----|
| Id  | ID | id |
|Content| Comment text need to be examine |String |
| Sever_toxic | Type of toxicity means "is't very toxic" | Integer |
| Lang  | The language of the comment | String |


                           *******************************************************************

Jupiter NoteBooks:

To run the notebooks smoothly you will have to install a lot of libararies packages beside to own a powerful GPU
we suggest to use Kaggle notebooks links we provided for easier running


**********  NOTES  *************


* you can run the preprocessing EDA in Jupiter, but for the rest we recommend kaggle

* in Kaggle make sure you turn on the TPU for "bert and xlm models" to avoid Memory constrains, you will find it on the right box inside the notebook "setting >> accelerator"

* in Kaggle make sure you turn on the GPU for "LSTM models" to avoid Memory constrains, you will find it on the right box inside the notebook "setting >> accelerator"


**********  NOTEBOOKS  ************

1__Preprocessing EDA, Data Cleaning

Kaggle link: https://www.kaggle.com/sarahaljudaibi/1-preprocessing-eda-data-cleaning

2__Bidirectional Lstm model for toxic classification comments

kaggle link: https://www.kaggle.com/norahsh/2-lstm-model-for-toxic-classification-comments

3__bert-model-for-classification-toxic-comments

Kaggle link:  https://www.kaggle.com/sarahaljudaibi/3-bert-model-for-classification-toxic-comments


4__xlm-r-model-for-classification-toxic-comments

kaggle link: https://www.kaggle.com/csabdulelah/4-xlm-r-model-for-classification-toxic-comments



********** Article link ************


https://medium.com/@CsAbdulelah/bert-step-by-step-b7ff47fcfbe

***** NOTE *****

after we publish the article it was used immediately by MC.AI, and this link for MC.AI


https://mc.ai/bert-step-by-step/


********************************************* Final Note ********************************************

Thank you never enough for your efforts, you were always there when we needed you, caring for our learning journey and welling to help.

