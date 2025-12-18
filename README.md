Project Summary – Next Word Prediction using MLP

Built a word-level next-word prediction model using a Multi-Layer Perceptron (MLP).

Used The Adventures of Sherlock Holmes dataset from Project Gutenberg as the text source.

Cleaned the raw text by converting it to lowercase and removing special characters.

Tokenized the text into words and created a vocabulary from unique words.

Converted words into numerical indices so they can be processed by a neural network.

Generated training data using a sliding context window approach.

Each training example consists of a fixed number of previous words as input and the next word as the target.

Implemented a custom Dataset class to generate training examples dynamically and save memory.

Used DataLoader to train the model in batches with shuffled data.

Designed an MLP model with:

An embedding layer to represent word meanings

Fully connected layers to learn word patterns

Dropout to reduce overfitting

Trained the model using Cross Entropy Loss and the Adam optimizer.

Evaluated model performance using a separate validation dataset.

Implemented a prediction function to return the top-k most likely next words with probabilities.

Built a Streamlit web app to interactively test next-word predictions.

Observed and analyzed overfitting behavior due to limited context and model simplicity.

The project demonstrates core concepts of language modeling, embeddings, and neural network training.
