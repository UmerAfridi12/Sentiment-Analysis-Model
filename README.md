
Developed a Sentiment Analysis Model:
Built a deep learning model using LSTM (Long Short-Term Memory) networks to classify text reviews as positive or negative.

Data Preparation and Preprocessing:
Processed and tokenized textual data using Keras Tokenizer, converting text into sequences and applying padding to standardize input length.
Replaced categorical sentiment labels with binary encoding to facilitate binary classification.

Model Architecture Design:
Designed a sequential neural network model with an Embedding layer for word embeddings, an LSTM layer for sequence learning, and a Dense layer with a sigmoid activation function for binary classification.

Model Training and Evaluation:
Trained the model using an 80-20 train-validation split, leveraging the Adam optimizer and binary cross-entropy loss function to optimize model performance.
Evaluated the model on a separate test set, achieving accuracy.

Prediction and Deployment:
Implemented a custom function to preprocess and predict sentiment for new reviews using the trained model, enabling real-time sentiment analysis.

Tools and Technologies Used:
Python, Keras, TensorFlow, Pandas, NumPy, Natural Language Processing (NLP), Deep Learning, LSTM.
