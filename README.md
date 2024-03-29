# BERT-TFIDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset

# Instructions:
The provided code performs the following tasks for text classification using various algorithms:

1. **Library Installation and Imports**:
   - The code starts by installing necessary libraries like TensorFlow and Transformers using pip. Then, it imports required modules and libraries.

2. **Defining Tweet Class and Methods for Data Loading and Cleaning**:
   - A class called `Tweet` is defined to represent tweets with attributes like UID, content, and sentiment.
   - Methods for cleaning tweet content, loading stop words, and reading files containing tweets are defined.

3. **Defining Method for Showing Results**:
   - A method is defined to plot confusion matrix and display F1 score.

4. **Data Loading and Preprocessing**:
   - Tweet data is loaded, preprocessed, split into training and testing sets, tokenized, and sequences are padded to have the same length.

5. **Hyperparameter Optimization (Optional)**:
   - An optional step where hyperparameters are optimized using the hyperopt library and the TPE algorithm. This step aims to find the best hyperparameters for the model.

6. **Model Training**:
   - A model, typically an LSTM model, is trained with the best hyperparameters obtained from hyperparameter optimization or with predefined hyperparameters.

7. **Visualizing Training History**:
   - Training and validation accuracy, as well as loss, are plotted over epochs to visualize the model's performance during training.

8. **Model Evaluation**:
   - The trained model is evaluated on the test set to calculate the F1 score and display evaluation results including the confusion matrix.

9. **Output**:
   - The code provides output such as the best hyperparameters and their performance obtained from hyperparameter optimization (if performed), as well as the model's performance metrics like accuracy, loss, and F1 score.

This comprehensive approach covers various aspects of text classification, from data preprocessing to model evaluation, and optionally includes hyperparameter optimization to improve model performance.

# TFIDF Results:
![Screenshot (21)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/64167b52-3bef-4322-a1d2-c271245cab11)
![Screenshot (23)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/9389d90f-e490-415f-98c3-7ab3c3ea346d)
![Screenshot (22)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/e2a0bf04-7bfa-4ace-991d-a2d4121da169)

# TSPE Results:
![Screenshot (17)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/0516ffb7-3b6a-47c6-affc-0316a4e4ac9a)
![Screenshot (16)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/99280fb7-f645-4769-aa2b-7dbf22950fb8)
![Screenshot (15)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/dad3fc07-ea37-4781-a6d5-d4a56add5c85)

# Word2Vec Results:
![Screenshot (18)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/92a780f2-6787-45a5-88c9-a959adc294ca)
![Screenshot (20)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/4cc6c1ae-aaad-46fa-b484-dbeb20070892)
![Screenshot (19)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/3bd740bf-5dd2-4af1-a42f-9389c9c5c6d7)

# BERT Results:
![Screenshot (14)](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/ea8ca343-28ea-471e-b96a-90b28797b48b)


# Graphs:

![actual](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/3bfc57c2-9b4e-4a17-9257-a28d9e4d5472)
![predicted](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/5bf0f212-77a2-466c-afd4-c456386b9260)
![line](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/228a925c-948c-47c6-bd0f-5e9bbc622743)
![bar](https://github.com/ArsalMirza007/BERT-TF-IDF-TSPE-SWN-Based-Models-on-Hinglish-semi-evaluation-2020-Dataset/assets/121928372/49b9380f-715d-4992-ac1a-a745f11f8e65)
