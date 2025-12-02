# My Portfolio 
- This contains a selection of projects, more can be found in at my GitHub, https://github.com/jmcinern
- To get in touch: mcinerjo@tcd.ie
## V1 Bilingual Irish and English 8B parameter LLM that I developed.
<h3 align="center">Qomhrá LLM Demo</h3>
<div align="center">
  <video src="./Qomhra_Cropped.mp4" width="100%" controls autoplay muted loop>
    Your browser does not support the video tag.
  </video>
</div>


- Continued pre-training on an existing multilingual model on Irish language data. 
- Included high proportion of English data, as similar efforts reported degredation in English performance.
- Designed custom data scheduling for adaption efficiency, presenting the model with "easier" data first.
- Instruction tuned and optimized L1-speaker-aligned preference data to provide a user-friendly chatbot.
- Quantized with respect to most important parameters for English and Irish generation to reduce inference cost.
- The model is deployed: https://huggingface.co/spaces/jmcinern/Qomhra



## RAG Model for Irish Politics

 ![image](https://github.com/user-attachments/assets/022e82c0-d1bd-4ec4-88ca-96ca88684c1b)

- Personal project to empower the Irish public to interact with primary political sources, removing the subjective framing of the news media.
- Collected 100 years of data, including 1B words of English and 10M words of Irish.
- Tagged language proportion per debate.
- Created a semantic database, to allow an LLM to answer questions with the most relevant parliamentary contributions as context.
- Set up interface, using LangChain for few-shot prompting to ensure responses included direct quotes and debate citations.
- Deployment in the works.

 
## Corpus Map of French Speaking African News-Media
  
 ![image](https://github.com/user-attachments/assets/63546352-035e-42b2-8b96-f85ccfbe90f9)

 - Undergraduate thesis (72%), combining computer science, linguistics and French with new knowledge of econometrics.
- Collected a corpus of French-speaking African new media, covering 23 countries and over 50M words 
- Classified articles as to whether the subject was France.
- Measured the negative sentiment of these articles using multiple lexicons.
- Collected the CAC 40 market price for the same time period, calculated daily returns, acting as a proxy for the French stock market.
- Tested statisticsl assumptions of stationarity, heteroscedasticity and multi-colinearity, before performing parsimonious Vector Autogregressive (VAR) experiments.
- Measured the impact of negative sentiment on the stock market, identifying the significant relationship, that returns were positive when no negative sentiment detected.
  

## A Visualisation of Multicolinearity - Spectral Data for Virus Classification

 ![image](https://github.com/user-attachments/assets/b8014aa7-bce6-4ce3-8945-ec569c5a065e)

## Comparing Distributions of Language Complexity Across Writing Styles

- Using average maximium syntactic dependancy as a proxy for language complexity to compare language complexity across genres of text that was generated synthetically.

<img width="804" height="199" alt="image" src="https://github.com/user-attachments/assets/b7d48f12-5009-47f6-aff9-1293fe455cfb" />

![image](https://github.com/user-attachments/assets/ec8738f8-602e-4fc5-884d-de8b4ee5dc05)

## PCA Analysis of Immune Genes and SVM Bias-Variance Analysis

- Trying to classify immune subtypes relevant to cancer based on gene expression.

![image](https://github.com/user-attachments/assets/2b971a7b-54d3-4c93-a61f-993a92f127a7)

![image](https://github.com/user-attachments/assets/ee51607d-123a-438b-b3ec-32754ee8ab84)

- Feature projection to prevent convergence instability from multicolinearity.

<img width="1460" height="990" alt="image" src="https://github.com/user-attachments/assets/0751e43c-cbde-4ab4-a93f-e4d7352023d6" />

- Hyperparameter grid search for classifier

## Topology of a Bayesian Network

- Modelling PrimeKG medical database as a knowledge graph, modelling multiple probabilities.

![image](https://github.com/user-attachments/assets/6c68bf6c-ffea-4a24-b7d6-b7070234a487

## Potuguese Grade Feature Correlation Matrix

- Regression analysis, showing that the best predictor of the next exam result is previous exam results and not other features such as parents education, indicating that there are other factors that are not factored into the model.

<img width="753" height="531" alt="image" src="https://github.com/user-attachments/assets/9ddde9be-ac4c-42a3-9e05-d5643cfdb753" />

## Image Classification with Convolutional Neural Network (CNN)

- Data augmentation was used to increase diversity of training images and dropout was added to reduce overfitting.

### Before Dropout - Overfitting 

- CNN overfits to training data and diverges from test illustrated by the models loss accuracy during training.  

<img width="1095" height="468" alt="image" src="https://github.com/user-attachments/assets/815ebfa5-85ca-449e-aeae-f676e4025c85" />


### With Dropout

- Dropout layer injects noise during training, mimicing unseen test data to prevent overfitting, where the model learns to memorize the test data.

<img width="1098" height="465" alt="image" src="https://github.com/user-attachments/assets/f7824393-2a16-4647-9899-6eff431c17be" />







