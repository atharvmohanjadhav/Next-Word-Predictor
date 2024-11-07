# Next Word Prediction 
This repository contains a deep learning project for Next Word Prediction using an LSTM (Long Short-Term Memory) model. The model is designed to predict the most likely next word based on a given sequence of words, trained on a text corpus to learn word patterns and contexts.

**📚Project Overview-**

This project aims to develop a Next Word Prediction model that can autocomplete sentences or suggest the next word based on context. Using an LSTM model helps capture long-term dependencies in sequences, making it suitable for text-based tasks.

**🤖Model Architecture-**
The LSTM-based model is designed to process sequences of words and predict the next word in the sequence. Key layers include:
- Embedding Layer: Maps each word to a vector representation.
- LSTM Layer(s): Capture sequential dependencies and long-term context.
- Dense Layer: Provides a fully connected layer for output prediction.
- Softmax Activation: Outputs a probability distribution over the vocabulary for the next word.

**📈Results-**

The model achieves the following results:

- Accuracy: 81.44 % 
- Loss: 0.90

Sample predictions:
- Input: "The next"
- Prediction: "big"

**Future Work-**
- Experiment with different model architectures, such as GRU or Transformer-based models.
- Implement beam search for improved prediction accuracy.
- Expand vocabulary and handle out-of-vocabulary (OOV) words.
  
**Contributing-**
Contributions are welcome! If you have ideas for improvement or additional features, feel free to open an issue or submit a pull request
