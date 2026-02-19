# Spam_Message_Detection
Spam Message Classification using Deep Learning (RNN)

Project Overview
This project focuses on building a **Spam Message Classification system** using **Deep Learning** techniques.  
A **Recurrent Neural Network (RNN)** model is implemented to classify Messages as **Spam** or **Not Spam** based on textual content.

Problem Statement
With the increasing volume of emails, identifying spam manually is inefficient.  
This project automates spam detection using **Natural Language Processing (NLP)** and **Deep Learning**.

Technologies Used
- Python
- TensorFlow / Keras
- Natural Language Processing (NLP)
- Recurrent Neural Networks (RNN)
- NumPy
- Pandas

- Model Architecture
- Embedding Layer (Vocabulary Size: 5000, Output Dimension: 64)
- SimpleRNN Layer with 64 units
- Dense Output Layer with Sigmoid Activation

- Implementation Details
- Text data is tokenized and padded to a fixed length.
- Word embeddings are learned during training.
- Binary classification is performed using a sigmoid activation function.
- Model optimized using **binary cross-entropy loss**.

- Results
- Successfully classifies Messages into spam and non-spam categories.
