# Data-Challenge---CEFR-prediction

## Data Challenge - Prediction of the CEFR Level of English Texts

### Points to be addressed by team members:

| Date       | Member  | Tasks                                                                  |
|------------|---------|------------------------------------------------------------------------|
| 20 February| Yasser  | - Push the code for RobertA-base <br> - Test for Mistral <br> - Test for Gpt2 |
| 20 February| Yaniv   | - Push codes: preprocessing <br> - TF_idf                             |
| 20 February| Gabriel | - Exploratory data analysis for further preprocessing                  |

### Additional Ideas:

- **Yasser**: Instead of fine-tuning BERT, use it as an embedding generator, and train using nonlinear ML models.
- **Gabriel**: Re-work on calibration of data: analyze mails in data for further insights.


### Point 20 February 14🕝
- **Yanniv**: Augmentation of data by doubling from different classes to have same number 350000/class --> TFIDF--> SVM.
   TODO :   Generer avec les SMOTE pour reequilibrer, Tester le Bert/Robert (@Gabriel) sur les 35k (généré avec Doubling), puis Test sur SMOTE
- **Yasser** :  XLnet, simpleTransformers with GPT2
  TODO: unify notebook for data preprocess , have running code for two XLNET / GPT2 , Augmenter les donnees avec GPT2
- **Gabriel** : did run robertA, Distilbert
- ToDO: unify notebook for data preprocess , share on github avec DistilBert, Bert, Preprocess with stopwords, submit test. 



### FineTune {model}
1. preprocess with/without stopwords
2. test Bert, Distlibert on yanniv_preprocess
3. unbalanced/Balanced Dataset: SMOTE/GPT2
4. Tokyo/External Dataset

| Date       | Member  | Tasks                                                                  |
|------------|---------|------------------------------------------------------------------------|
| 20 February| Yasser  | RobertA, XLnet, GPT2 -- >  
| 20 February| Yaniv   | TFIDF, SVM, SMOTE                |
| 20 February| Gabriel | DistilBert, RobertA      |
