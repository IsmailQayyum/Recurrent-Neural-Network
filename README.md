# Recurrent Neural Network for Question Answering

This project demonstrates the use of Recurrent Neural Networks (RNNs) to answer questions based on a small dataset of 100 unique question-answer pairs. The model is trained to predict answers to questions provided by the user.

## Dataset

The dataset consists of 100 unique question-answer pairs stored in a CSV file named `100_Unique_QA_Dataset.csv`. Here are a few examples from the dataset:

| Question                                      | Answer          |
|-----------------------------------------------|-----------------|
| What is the capital of France?                | Paris           |
| Who wrote 'To Kill a Mockingbird'?            | Harper-Lee      |
| What is the largest planet in our solar system? | Jupiter         |
| What is the boiling point of water in Celsius? | 100             |
| Who painted the Mona Lisa?                    | Leonardo-da-Vinci|

## Notebook

The main implementation is in the Jupyter Notebook `rnn.ipynb`. The notebook includes the following steps:

1. **Data Preprocessing**: Loading and preprocessing the dataset.
2. **Model Building**: Constructing the RNN model using PyTorch.
3. **Training**: Training the model on the dataset.
4. **Prediction**: Using the trained model to predict answers to user-provided questions.

### Example Usage

To predict the answer to a question, you can use the `predict` function as shown below:

```python
predict(model, 'What is the largest planet in solar system')
